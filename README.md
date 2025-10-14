# CHATINVIS

ChatInVis provides a platform to facilitate information-seeking through a browser extension that enhances the MindMeister online mind mapping application. This tool integrates a large language model (LLM) to guide exploration processes and allow users to retrace their explorations seamlessly. Through a series of interactive interfaces, ChatInVis supports users in accessing, assessing, and expanding their information landscape efficiently.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/2e392513-16b8-49cc-bc8a-5592461bc9a1" />

---

## What is ChatInVis?

ChatInVis is a browser extension designed to support **exploratory information-seeking** in MindMeister using Large Language Models (LLMs). Unlike traditional LLM interfaces like ChatGPT, which present information sequentially, ChatInVis addresses key challenges by:

- **Representing search trails as mind maps**: Enables users to see multiple exploration branches simultaneously
- **Incorporating analytic provenance**: Documents and traces the user's reasoning process during information seeking
- **Providing structured organization**: Groups related content and highlights connections between information pieces
- **Facilitating revisitation**: Makes it easy to return to previous points of interest in the exploration

### Research Background

This tool emerged from research on enhancing LLM-based information seeking. A user study with 20 participants demonstrated that ChatInVis:
- Helps users **retrace their search trails** and reflect on discoveries
- Enables **identification of connections** between different concepts
- Supports **navigation of complex information** spaces
- Provides **structured guidance** during exploratory tasks
- Achieved a **System Usability Scale (SUS) score of 88.87** (well above the 68 threshold for above-average usability)

---

# END-USERS MANUAL

## Purpose

ChatInVis is a browser extension designed to support exploratory information-seeking in MindMeister using Large Language Models (LLMs). By harnessing the power of LLMs, ChatInVis helps you explore the landscape of your initial questions and offers different insights to understand and conceptualize complex topics. The tool addresses key limitations of traditional LLM interfaces, such as difficulty in revisiting information and lack of structural organization, by representing search trails as interactive mind maps enhanced with analytic provenance.

## How It Works

ChatInVis adds a mind map template in MindMeister to start your exploration journey. After defining your initial question, ChatInVis introduces the dynamic intelligence of LLMs to enrich your information-seeking process through an interactive exploration interface. It transforms initial, often vague, questions into clearly structured exploration paths. Through an interactive process, ChatInVis helps you:

- **Navigate Complex Information**: Visualize your exploration process with branching paths that allow you to see different inquiry directions
- **Expand Your Knowledge**: Discover new areas of interest through LLM-driven follow-up questions and diverse perspectives
- **Retrace Your Search Trail**: Review your exploration history, reflect on discoveries, and identify connections between concepts
- **Integrate External Knowledge**: Incorporate PDFs and research papers directly into your exploration with source citations
- **Manage Information Overload**: Summarize and cluster related questions and answers to maintain focus

### Key Benefits

- **Efficiency**: By integrating LLM insights directly into your MindMeister workflow, ChatInVis significantly reduces the time needed for information gathering
- **Clarity**: It clarifies the exploration process, helping you move from a broad understanding of topics to specific, actionable insights
- **Traceability**: Enables you to document and revisit your reasoning during the search process through analytic provenance
- **Enhanced Understanding**: With the support of LLMs and visual organization, you gain access to a wide range of knowledge and perspectives, enhancing creativity and depth in information-seeking

---

## Installation and Setup

Follow these steps to get ChatInVis up and running:

### Step 1: Requirements

Ensure your computer meets the minimum requirements for running ChatInVis:

- **Google Chrome browser**
- **MindMeister account** (the free version allows you to create 3 maps at most)
- **LLM API key**: ChatInVis allows you to interact with GPT and Claude models, therefore, ensure you have an **OpenAI** or **Anthropic** API key
  - Get an OpenAI API key at: https://platform.openai.com/api-keys
  - Get an Anthropic API key at: https://console.anthropic.com/

### Step 2: Install the ChatInVis Extension

- Open your web browser and navigate to the ChatInVis extension page on the [Chrome Web Store](https://chromewebstore.google.com/detail/chatinvis/fimamihiakhbnopcnnlndkmljmbpcmhi)
- Click the "Add to Browser" or "Install" button to begin the installation process
- Once the installation is complete, you will see a ChatInVis icon appear in your browser's toolbar. This indicates that ChatInVis is successfully installed

### Step 3: Setup

Open ChatInVis's options panel by right-clicking on the ChatInVis browser toolbar icon:

In this page, you have to complete the following information:

1. Grant access to MindMeister
2. Select your Large Language Model and include your API key
3. Establish the number of answers you want to retrieve by each prompting

Finally, check if the ChatInVis template appears in MindMeister:

---

## Getting Started

### Creating Your First Exploration

Upon accessing the MindMeister homepage, ChatInVis provides a new mind map template to initiate the exploration. Once the map is loaded, users can input their initial question in the root mind map node. The **question mark icon (?)** can be used to seek answers and initiate exploration.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/fd1f49d4-5b63-4628-aa11-614ea39c129e" />

### Understanding the Conceptual Model

ChatInVis organizes your search trail around several key elements that work together to create a traceable exploration process:

<img width="696" height="381" alt="model (3)" src="https://github.com/user-attachments/assets/ac343c65-2655-4206-9fda-525a32006752" />

The conceptual model shows how different components interact:

- **Interaction**: The central hub capturing all your exploration activities
- **Questions**: Can originate from multiple sources
  - User Questions: Your own typed questions
  - LLM-Driven Questions: Generated by the AI based on context
  - Framework-based: Structured questions (e.g., 5W1H)
  - Previous Questions: Selected from logs of past explorations
- **Answers**: Responses that can be
  - LLM Answers: From the model's knowledge
  - Resource-Based Answers: Derived from uploaded PDFs
- **Feedback**: Your ratings (0-4) and annotations
- **Clusters**: Grouped questions or answers to manage complexity

### Understanding the Search Trail Elements

ChatInVis uses distinct visual representations to help you perceive different types of questions, answers, and sources:

<img width="1005" height="430" alt="design" src="https://github.com/user-attachments/assets/e4a7902a-0425-4ad4-bbe5-ff44dee2238a" />

**Visual Coding System:**

- **User interactions**: Depicted with **square shapes**
- **LLM-generated elements**: Shown as **circles**
- **System log elements**: Displayed as **cloud shapes**
- **Questions, answers, and clusters**: Distinguished using different icons and background colors
- **Resource-based answers**: Indicated by an **attachment icon**
- **Feedback annotations**: Appear as text within the answer
- **Ratings (0-4)**: Visually represented through border colors, from red to dark green, in a traffic light color scale

### Complete Interaction Workflow

<img width="1163" height="858" alt="interaction (4)" src="https://github.com/user-attachments/assets/d146c3ae-8d3f-4c41-bbeb-6b3a0115089d" />

**Question-answer interaction in ChatInVis:**

- **(A)** Initial question - where your exploration begins
- **(B)** One of the answers for first question; the right button inside each node allows users to view the complete answer
- **(C)** User input question - add your own follow-up questions
- **(D)** Previous question - questions from your exploration logs
- **(E)** LLM own question - AI-generated follow-up questions
- **(F)** Framework-based question - structured questions (e.g., 5W1H)
- **(G)** All sources can be viewed in the note attached to each node, together with a description

**How the interaction works:**

1. **Ask a question**: Start by typing your question in the root node
2. **Get answers**: Click the question mark icon to generate multiple answers
3. **Explore deeper**: Click the magnifier icon on any answer to get follow-up questions
4. **Choose your path**: Select from user-defined, LLM-generated, framework-based, or previous questions
5. **Continue exploring**: Each answer opens new branches of exploration

### Exploring with LLM-Generated Answers

When the LLM-generated answers are displayed, the system highlights previously considered answers and identifies those well-rated. Users can explore different answers by displaying notes which provide descriptions and sources. Additionally, users may input their own answers into the square-shaped node.

### Deepening Your Exploration

If users encounter something intriguing, they can click the **magnifier icon** to delve deeper into the selected answer. The LLM will generate related questions based on various sources. Users can identify the sources by the question's shape and view more details by examining the note.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/36570294-5f03-452f-bf81-c3c9e5ed9e70" />

### Asking Follow-up Questions

Users can locate nodes to input their questions, including:

- **User-defined questions**: Type your own questions in square nodes
- **System-suggested questions**: From logs of previous explorations
- **LLM-generated questions**: Based on the current context

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/4e74e9c0-e6e6-4049-ac22-68eb6bac7043" />

### Using Question Frameworks

Additionally, users can frame questions based on a user-defined questioning framework. The interaction can be customized in the question configuration menu, allowing users to add, edit, or delete question models (e.g., 5W1H framework: Who, What, When, Where, Why, and How).

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/ea74f96c-87f4-4a56-ae9f-94f980880109" />

### Configuration Options

Users have the option to configure various settings such as the type and number of displayed nodes, or whether to incorporate logs.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/968b7b05-649d-4e0d-a995-92dcf9dfe7e2" />

In this stage, user input nodes disappear once answers are retrieved.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/657165f0-faab-473e-9c0c-cc258bad5c70" />

Previously configured question models now display questions based on the five W1H: who, what, where, when, why, and how.

---

## Key Features

### Providing Feedback

<img width="1340" height="647" alt="feedback" src="https://github.com/user-attachments/assets/ae61660d-a52d-4222-896f-55cb6ee7f09f" />

**Setting feedback in ChatInVis:**
1. Users right-click in node and select 'Set user record'
2. User provides an annotation and rating
3. The node appearance is updated with the feedback

Users can add annotations and assign ratings to mind map nodes. These ratings are visually represented with different colors within the mind map, allowing for quick navigation and identification of key insights or areas of interest.

**Feedback helps you:**
- Document your thoughts during exploration
- Rate answers on a scale from 0 to 4
- Quickly identify valuable information through color-coding
- Enable the system to suggest well-rated answers to other users
- Create a record of your reasoning process for future reference

During interactions with the LLM, users have the opportunity to provide feedback on the answers to express their reasoning and thoughts.

<img width="444" height="334" alt="image" src="https://github.com/user-attachments/assets/e3146c33-3934-44f1-a167-969c8ac3c94f" />

<img width="444" height="334" alt="image" src="https://github.com/user-attachments/assets/3acc85d8-9052-4f54-9ca2-c06e11f30f39" />

### Integrating External Knowledge

<img width="811" height="680" alt="pdf" src="https://github.com/user-attachments/assets/ccf8b9bd-1be6-4205-a19a-5eaac01d0644" />

**Adding external knowledge in ChatInVis:**
1. Select attachment and upload a PDF in a question node
2. Select 'Ask GPT'
3. Answers have the source attached and notes show the answer description and an excerpt from the document

While interacting with ChatInVis, responses are initially generated from the LLM's knowledge. However, the system allows users to expand this knowledge by uploading external sources such as PDFs. In these cases, the answers derive from the provided PDFs.

<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/c0015281-e513-4c01-b990-f86f33282b91" />

By examining the source of a node, users can access:
- A description of the answer
- A text excerpt from the PDF that supports the answer
- Direct links to specific sections in the source document

Users can also request additional answers from the LLM to explore different perspectives, enabling them to compare information from various sources.

### Summarizing Information

<img width="925" height="532" alt="summarize" src="https://github.com/user-attachments/assets/89cc09a5-b8a4-4c31-965f-58d9f0d17d5b" />

**Summarizing questions in ChatInVis:**
1. User selects 'Summarize'
2. They select the number of clusters
3. Questions are grouped in the indicated number of nodes, they maintain the previous data in the node to retrace the transformation. Interaction is the same for summarizing answers

The system provides the capability to group questions into various clusters, which simplifies organization and makes it more manageable.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/40576f1b-102f-404c-8d37-3d53269cb08f" />

The LLM efficiently summarizes and clusters similar questions. These summarized questions are easily identified by the interrogation mark. You can view the grouped questions within each node by checking the note.

<img width="523" height="328" alt="image" src="https://github.com/user-attachments/assets/0c4bb676-9505-4e88-b8a4-a8a4e4aa42c6" />

The system can cluster both questions and answers from various sources, helping to:

- Reduce information overload
- Maintain focus on key concepts
- Integrate information from multiple sources
- Create top-level taxonomies of related concepts

### Retracing Your Exploration

In ChatInVis, information is systematically organized, enabling users to explore different branches and follow various search paths. Users can review annotations to deepen their understanding and use ratings for quick navigation to identify key points of interest.

<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/370a10e5-ef89-4015-97cc-05a568887924" />

**Benefits of retracing:**
- **Reflect on discoveries**: Review your exploration history to understand your thought process
- **Identify connections**: See how different concepts relate to each other
- **Understand provenance**: Track where information came from and how it was derived
- **Learn from exploration**: Understand what questions led to valuable insights
- **Explain your reasoning**: Document and share your decision-making process

### Viewing Exploration Logs

Users have the option to request logs of the current mind map, which provides a review of how the search trail was constructed. These logs encompass details such as:

- **Selected answers**: Which answers you chose to explore further
- **Consulted nodes**: What information you reviewed
- **Timestamps**: When each action occurred
- **Node values**: The content of questions and answers
- **User actions**: askQuestion, selectAnswer, setFeedback, summarize, consultNote
- **Context**: The state of the mind map when actions were taken

<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/5bbec616-b097-4b5d-a74c-fd9a076197fc" />

Logs can be exported and imported in JSON format, enabling sharing of exploration data for collaboration or future analysis.

**Use cases for logs:**
- Generate reports to review your analysis process
- Identify obstacles encountered during exploration
- Reproduce interactions for analysis
- Support collaboration through log sharing
- Reuse successful exploration patterns in new contexts

---

## Advanced Usage

### Managing Information Overload

The tool proposes multiple follow-up questions and answers that can help exploration but may also overwhelm users. Strategies to manage this:

1. **Configure question types**: Enable/disable specific question sources in settings
2. **Adjust answer count**: Reduce the number of answers generated per question
3. **Use summarization frequently**: Cluster information before it accumulates
4. **Collapse nodes**: Use MindMeister's built-in collapsing to hide branches
5. **Focus on ratings**: Navigate using color-coded feedback to find key insights

### Collaborative Exploration

ChatInVis supports collaborative information-seeking:

- **Share mind maps**: Export and share your exploration with team members through MindMeister's sharing features
- **Reuse logs**: Import logs from colleagues to understand their reasoning and exploration paths
- **Feedback sharing**: See well-rated answers from other users (when logs are shared)
- **Collective intelligence**: Build on explorations of others with similar research interests

**Current limitations:**
- Log sharing requires manual export/import
- Logs are stored locally in Chrome's storage
- Future versions may include integrated sharing mechanisms

### Using Previous Questions

The system can suggest questions from your past explorations:

- **Automatic suggestion**: LLM selects relevant questions from logs based on current context
- **Cross-topic application**: Reuse successful question patterns in new domains
- **Learning support**: Understand what questions led to valuable insights in the past

---

## Tips for Effective Use

### For Exploring Unknown Topics

- Start with a broad question to get oriented
- Review multiple answers to get diverse perspectives
- Use the magnifier icon to drill deeper into interesting points
- Let LLM-generated questions guide your exploration
- Summarize frequently to maintain a high-level overview
- Add annotations to capture your thoughts as you learn

### For Research and Analysis

- Upload relevant PDFs early in the process
- Use framework-based questions (5W1H) for comprehensive coverage
- Annotate answers with your reasoning and critique
- Rate answers to track most valuable insights
- Export logs for documentation and reporting
- Compare answers from LLM knowledge vs. external documents

### For Collaborative Work

- Share mind maps with clear annotations explaining your thinking
- Use consistent rating scales within your team
- Export and share logs when transferring knowledge
- Review others' exploration trails to learn different approaches
- Build upon existing explorations rather than starting from scratch

### When ChatInVis is Most Effective

**Ideal for:**
- Exploring unfamiliar topics that require building conceptual understanding
- Complex questions with multifaceted relationships between concepts
- Research requiring integration of multiple sources (LLM + documents)
- Collaborative knowledge building and sharing
- Documentation of reasoning processes for later review
- Open-ended exploration where the path is unclear

**Not ideal for:**
- Simple factual queries or definitions (use traditional LLM chat for these)
- Time-sensitive tasks requiring quick answers
- Situations where exploration structure adds unnecessary complexity

---

## Support and Resources

- **Email Support**: xabier.garmendiad@ehu.eus
- **Video Tutorial**: [7-minute demo](https://drive.google.com/file/d/1aaF5p2dJ937bAass8I8sG15DYCp5M5N2/view?usp=sharing) - Highly recommended for new users
- **Example Maps**: [Sample explorations created with ChatInVis](https://docs.google.com/document/d/1liPEni_1E7nwpLqcZN4sE_DnGSYGupJ7rqfIQaxQcYw/edit?usp=sharing)

---

## Available LLMs

- **OpenAI**: GPT-4, GPT-3.5-turbo
- **Anthropic**: Claude 2.0

*Note: You need a valid API key for your chosen model. API costs are determined by the respective providers and charged separately.*

---

## Frequently Asked Questions

**Q: Do I need to pay for the LLM API?**  
A: Yes, you need an API key from OpenAI or Anthropic, which have associated costs based on usage. Check their pricing pages for current rates.

**Q: Can I use ChatInVis offline?**  
A: No, ChatInVis requires internet connectivity to communicate with LLM APIs and MindMeister.

**Q: How is my data stored?**  
A: Exploration logs are stored locally in Chrome's local storage. Mind maps are stored in your MindMeister account. Neither ChatInVis nor the developers have access to your data.

**Q: Can I export my exploration?**  
A: Yes, you can export mind maps from MindMeister in various formats, and logs can be exported in JSON format from ChatInVis.

**Q: Is there a limit to the number of maps I can create?**  
A: This depends on your MindMeister plan. The free plan allows up to 3 maps. Upgrade to MindMeister Pro for unlimited maps.

**Q: Can I use my own LLM models or open-source models?**  
A: Currently, only OpenAI and Anthropic models are supported through their APIs. Support for local and open-source models is planned for future versions.

**Q: What happens if I run out of API credits?**  
A: The extension will show an error when trying to generate responses. You'll need to add credits to your OpenAI or Anthropic account.

---

# DEVELOPERS MANUAL

## Architecture Overview

<img width="456" height="177" alt="architecture" src="https://github.com/user-attachments/assets/00c7f1df-3ef3-4245-8354-c6961be3557e" />

ChatInVis is a browser extension developed with web development technologies: JavaScript, Node.js, and Gulp. It is developed using Manifest version 3: https://developer.chrome.com/docs/extensions/develop/migrate/what-is-mv3

The web extension follows the standard browser extension architecture with:
- **Content script modules**: Manage web content
- **Background scripts**: Manage local storage, MindMeister, and LLM communications

## System Architecture

ChatInVis acts as a bridge between the user, MindMeister, and the LLM. The extension:

- Communicates with the LLM through specific prompts that request responses in JSON format
- Renders the responses as question and answer nodes in the mind map
- Stores logs of user interactions and feedback in Chrome's local storage for later retrieval

The technology used for LLM communication is **LangChain**, which facilitates seamless integration of different LLM models. Users can configure various models in the extension options page, including:

- OpenAI models (GPT-4, GPT-3.5-turbo)
- Anthropic models (Claude 2.0)

### Key Design Principles

The system was designed following five interrelated stages of **analytic provenance**:

1. **Perceive**: Visual differentiation of question types, answer sources, and feedback
2. **Capture**: Semantic information through user annotations and ratings
3. **Encode**: Logging of user actions with timestamps and context
4. **Recover**: Retrieval of all recorded actions and interactions
5. **Reuse**: Automatic suggestions based on past interactions

## Development Environment

To develop from the source code, you will need to install Node.js and Gulp to build the extension. Required versions:

- **Node v12.22**
- **Gulp v4**

## API Documentation

ChatInVis makes use of different APIs:

- **MindMeister API**: Used to manage the maps - https://developers.mindmeister.com/
  - Handles map creation, node manipulation, and data retrieval
  - Provides authentication and authorization
  
- **LangChain**: Used to interact with different LLM APIs through the LangChain JS library - https://js.langchain.com/docs/get_started/introduction
  - Provides unified interface for multiple LLM providers
  - Handles prompt formatting and response parsing
  - Supports streaming responses and error handling

## Code Structure

The artifact code is organized as follows:
```
chatinvis/
├── images/          # Images within the browser extension
├── pages/           # HTML files of the extension
├── resources/       # Mind map templates and pdf.js library to process PDFs
└── scripts/         # Main component with scripts to make the extension work
    ├── content_script.js      # Executed when MindMeister is accessed
    ├── background.js          # Initializes background scripts for communications
    ├── options.js             # Executed when the option page is opened
    ├── chatin/               # Scripts executed in MindMeister
    │   ├── HomePageManager.js # Adds button to create ChatInVis map
    │   ├── MindmapManager.js  # Handles ChatInVis functionality (MOST IMPORTANT)
    │   └── [model files]      # Define node names, question templates, prompt styles
    ├── llm/                  # LLM communication scripts
    │   └── LLMManager.js      # Communications with LangChain and local storage
    ├── mindmeister/          # Scripts to communicate with MindMeister API
    └── utils/                # Helper functions for reusable code
```

**Main components:**

- **Content Script**: `content_script.js` - executed when MindMeister is accessed
- **Service worker**: `background.js` - initializes all background scripts to enable communications
- **Options file**: `options.js` - executed when the option page is opened
- **MindmapManager.js**: The most important file - orchestrates all ChatInVis functionality
- **LLMManager.js**: Establishes communications with LangChain for asking questions to an LLM

## Building and Testing

To compile the project, execute the following lines (ensure you have the correct Node.js and Gulp versions):
```bash
$ npm install
$ gulp default
```

## Usage

Run `$ gulp --watch` and load the `dist` directory into Chrome.

## Entry Files (Bundles)

There are two kinds of entry files that create bundles:

1. All js-files in the root of the `./app/scripts` directory
2. All css-, scss- and less-files in the root of the `./app/styles` directory

## Build Tasks

### Build
```bash
$ gulp
```

**Build Options:**

| Option         | Description                                                                                                                                           |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| `--watch`      | Starts a livereload server and watches all assets. <br>To reload the extension on change include `livereload.js` in your bundle.                      |
| `--production` | Minifies all assets                                                                                                                                   |
| `--verbose`    | Log additional data to the console.                                                                                                                   |
| `--vendor`     | Compile the extension for different vendors (chrome, firefox, opera, edge). Default: chrome                                                           |
| `--sourcemaps` | Force the creation of sourcemaps. Default: !production                                                                                                |

### Pack

Zips your `dist` directory and saves it in the `packages` directory:
```bash
$ gulp pack --vendor=firefox
```

### Version

Increments version number of `manifest.json` and `package.json`, commits the change to git and adds a git tag:
```bash
$ gulp patch      # => 0.0.X
$ gulp feature    # => 0.X.0
$ gulp release    # => X.0.0
```

## Globals

The build tool defines a variable named `process.env.NODE_ENV` in your scripts. It will be set to `development` unless you use the `--production` option.

## Extending ChatInVis

### Adding a New LLM Provider

1. Update `llm/LLMManager.js` to include the new provider via LangChain
2. Add provider configuration options in `pages/options.html`
3. Update prompt formatting if needed for provider-specific requirements
4. Test thoroughly with various question types

### Adding New Question Frameworks

1. Define framework structure in the appropriate model file
2. Create prompt templates for the framework
3. Add UI controls in the configuration panel
4. Test with various contexts and question types

### Customizing Node Appearance

1. Modify node rendering logic in `chatin/MindmapManager.js`
2. Update icon mappings in `resources/` directory
3. Adjust color schemes for different node types
4. Ensure visual differentiation remains clear

## Testing Checklist

**Manual Testing:**
- [ ] Install extension in Chrome
- [ ] Configure with valid API keys (OpenAI and Anthropic)
- [ ] Create new ChatInVis map from template
- [ ] Test question-answer interaction flow
- [ ] Test PDF upload and querying functionality
- [ ] Test feedback mechanism (annotations and ratings)
- [ ] Test summarization feature for questions and answers
- [ ] Test log generation and export
- [ ] Verify all node types render correctly
- [ ] Test with multiple LLM providers
- [ ] Test in different MindMeister account types (free/pro)
- [ ] Verify local storage functionality
- [ ] Test configuration options

---

## Contribution Guidelines

To contribute please contact: **xabier.garmendiad@ehu.eus**

Please include:
- Description of proposed feature or bug fix
- Use case or rationale
- Technical approach (if applicable)
- Any relevant research or references

---

## Roadmap and Future Plans

This project has been developed in a research setting. The aim is to explore the benefits of AI for exploratory information-seeking. Future plans include:

### Short-term Goals
- Evaluating the artifact in real-world settings beyond research
- Improving information overload management mechanisms
- Enhancing log analysis and visualization capabilities

### Long-term Goals
- **Open-source LLM integration**: Support for local and open-source models
- **Enhanced collaboration**: Built-in sharing and synchronization features
- **Improved scalability**: Better handling of large-scale explorations
- **Advanced analytics**: Deeper insights from provenance data
- **Mobile support**: Extension for mobile browsers
- **Additional external sources**: Support for web pages, videos, and other document formats
- **Multi-language support**: Interface and documentation in multiple languages

---

## Research Background

### The Problem

While Large Language Models (LLMs) have significantly advanced information-seeking processes, their traditional text-based interfaces pose challenges:

1. **Difficulty in Revisiting Information**: LLMs deliver information sequentially, making it difficult to return to previous points of interest
2. **Lack of Structural Organization**: LLMs struggle to group related content and highlight connections between information pieces

These issues make it hard for users to maintain and review their **search trails** - the sequences of steps, decisions, and interactions that document their exploration.

### The Solution

ChatInVis addresses these challenges through:

- **Mind map visualization**: Represents search trails as hierarchical, branching structures
- **Analytic provenance**: Documents and traces the user's reasoning process
- **Exploration guidance**: Provides LLM-driven follow-up questions
- **External knowledge integration**: Incorporates PDFs and documents
- **Information summarization**: Manages information overload through clustering

### User Study Results

A study with 20 participants (Ph.D. students, researchers, and professors) evaluated ChatInVis for:
- Usability and effectiveness in facilitating exploration
- Ability to retrace search paths
- Support for exploration and sensemaking

**Key Findings:**
- **High usability**: System Usability Scale (SUS) score of 88.87 (well above the 68 threshold)
- **Effective retracing**: Users could revisit their exploration and understand their reasoning
- **Connection discovery**: Helped identify relationships between concepts
- **Navigation support**: Facilitated exploration of complex information spaces
- **Structured guidance**: LLM-driven questions aided deeper exploration

**Participant Feedback:**
- *"You have your history of exploration, and you can directly see the research branch"*
- *"It gives you access to vocabulary and associated taxonomy, which can be useful when you do not have much knowledge on the topic"*
- *"I enjoyed using mind maps; they allow exploration and interaction with questions/answers and keep track of the exploration path"*

### When to Use ChatInVis

**Most effective for:**
- Exploring open-ended questions where relationships among concepts are complex
- Understanding not just definitions but components, sources, and applications
- Tasks requiring reflection, decisions, and exploration of different dimensions
- Explaining search processes and reasoning to others

**Less effective for:**
- Simple factual queries or quick definitions
- Situations requiring direct, immediate answers
- Tasks where exploration structure adds unnecessary complexity

---

## License

This project is released under the **MIT License**.

---

## Acknowledgments

ChatInVis builds upon the MindMeister platform and leverages the capabilities of Large Language Models through LangChain integration. We thank the research participants who contributed to the evaluation and improvement of this tool.


**Version**: 1.0.0  
**Maintained by**: Onekin Research Group  
**Contact**: xabier.garmendiad@ehu.eus
