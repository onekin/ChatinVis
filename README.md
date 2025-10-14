# CHATINVIS
ChatInVis provides a platform to facilitate information-seeking through a browser extension that enhances the MindMeister online mind mapping application. This tool integrates a large language model (LLM) to guide exploration processes and allow users to retrace their explorations seamlessly. Through a series of interactive interfaces, ChatInVis supports users in accessing, assessing, and expanding their information landscape efficiently. ChatInVis is designed to enhance your exploration process and also supports retracing your exploration journey. It is a browser extension that integrates with the MindMeister online mind mapping application, offering an interactive interface powered by a large language model for information-seeking purposes.


<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/2e392513-16b8-49cc-bc8a-5592461bc9a1" />



# END-USERS MANUAL
Purpose: ChatInVis is a browser extension designed to support exploratory information-seeking in MindMeister using Large Language Models (LLMs). By harnessing the power of LLMs, ChatInVis helps you explore the landscape of your initial questions and offers different insights to understand and conceptualize complex topics. The tool addresses key limitations of traditional LLM interfaces, such as difficulty in revisiting information and lack of structural organization, by representing search trails as interactive mind maps enhanced with analytic provenance.

How It Works: ChatInVis adds a mind map template in MindMeister to start your exploration journey. After defining your initial question, ChatInVis introduces the dynamic intelligence of LLMs to enrich your information-seeking process through an interactive exploration interface. It transforms initial, often vague, questions into clearly structured exploration paths. Through an interactive process, ChatInVis helps you:

- Navigate Complex Information: Visualize your exploration process with branching paths that allow you to see different inquiry directions
- Expand Your Knowledge: Discover new areas of interest through LLM-driven follow-up questions and diverse perspectives
- Retrace Your Search Trail: Review your exploration history, reflect on discoveries, and identify connections between concepts
- Integrate External Knowledge: Incorporate PDFs and research papers directly into your exploration with source citations
- Manage Information Overload: Summarize and cluster related questions and answers to maintain focus

Key Benefits:

- Efficiency: By integrating LLM insights directly into your MindMeister workflow, ChatInVis significantly reduces the time needed for information gathering
- Clarity: It clarifies the exploration process, helping you move from a broad understanding of topics to specific, actionable insights
- Traceability: Enables you to document and revisit your reasoning during the search process through analytic provenance
- Enhanced Understanding: With the support of LLMs and visual organization, you gain access to a wide range of knowledge and perspectives, enhancing creativity and depth in information-seeking




## Installation and Setup
Follow these steps to get ChatInVis up and running:
### Step 1: Requirements
Ensure your computer and you meet the minimum requirements for running Chatin.

- Google Chrome browser
- MindMeister account (the free version allows you to create 3 maps at most)
- LLM API key: ChatInVis allows you to interact with GPT and Claude models, therefore, ensure you have an OpenAI or Anthropic API key

### Step 2: Install the ChatinVis Extension
- Open your web browser and navigate to the ChatinVis extension page on the [[Browser Extension Store/Marketplace](https://chromewebstore.google.com/detail/chatinvis/fimamihiakhbnopcnnlndkmljmbpcmhi)].
- Click the "Add to Browser" or "Install" button to begin the installation process.
- Once the installation is complete, you will see a Chatin icon appear in your browser’s toolbar. This indicates that Chatin is successfully installed.

### Step 3: Setup
Open ChatInVis's options panel by right-clicking on the ChatInVis browser toolbar icon:

<img width="521" alt="Screenshot 2024-03-21 at 17 21 05 1" src="https://github.com/onekin/Chatin/assets/31988855/118f2ef8-0a34-4ba5-baff-75064f3f23c3">

In this page, you have to complete the following information:

1. Grant access to MindMeister
2. Select your Large Language Model and include your API key
3. Establish the number of answers you want to retrieve by each prompting

<img width="750" alt="Screenshot 2024-03-21 at 17 33 04" src="https://github.com/onekin/Chatin/assets/31988855/76b378d3-2036-48d5-b5d5-a10867bb6cc3">

Finally, check if the ChatInVis template appears in MindMeister:

<img width="1067" alt="Screenshot 2024-03-21 at 17 38 00" src="https://github.com/onekin/Chatin/assets/31988855/09f7e556-9def-461f-aaac-f13a28434e79">

## Getting Started
Upon accessing the MindMeister homepage, ChatInVis provides a new mind map template to initiate the exploration. Once the map is loaded, users can input their initial question in the root mind map node. The question mark icon can be used to seek answers and initiate exploration.


<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/fd1f49d4-5b63-4628-aa11-614ea39c129e" />

### Understanding the Search Trail Elements
ChatInVis uses distinct visual representations to help you perceive different types of questions, answers, and sources:

- User interactions: Depicted with square shapes
- LLM-generated elements: Shown as circles
- System log elements: Displayed as cloud shapes
- Questions, answers, and clusters: Distinguished using different icons and background colors
- Resource-based answers: Indicated by an attachment icon
- Feedback annotations: Appear as text within the answer
- Ratings (0-4): Visually represented through border colors, from red to dark green, in a traffic light color scale

### Exploring with LLM-Generated Answers
When the LLM-generated answers are displayed, the system highlights previously considered answers and identifies those well-rated. Users can explore different answers by displaying notes which provide descriptions and sources. Additionally, users may input their own answers into the square-shaped node.

  
<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/1ecf37d0-0036-4990-9ba2-5751c86f0bc4" />
### Deepening Your Exploration

If users encounter something intriguing, they can click the magnifier icon to delve deeper into the selected answer. The LLM will generate related questions based on various sources. Users can identify the sources by the question's shape and view more details by examining the note.

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/36570294-5f03-452f-bf81-c3c9e5ed9e70" />

### Asking Follow-up Questions
Users can locate nodes to input their questions, including:

- User-defined questions: Type your own questions in square nodes
- System-suggested questions: From logs of previous explorations
- LLM-generated questions: Based on the current context

<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/4e74e9c0-e6e6-4049-ac22-68eb6bac7043" />

### Using Question Frameworks

Additionally, users can frame questions based on a user-defined questioning framework. The interaction can be customized in the question configuration menu, allowing users to add, edit, or delete question models.
<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/ea74f96c-87f4-4a56-ae9f-94f980880109" />

### Configuration Options
Users have the option to configure various settings such as the type and number of displayed nodes, or whether to incorporate logs.
<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/968b7b05-649d-4e0d-a995-92dcf9dfe7e2" />
In this stage, user input nodes disappear once answers are retrieved.
<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/657165f0-faab-473e-9c0c-cc258bad5c70" />
Previously configured question models now display questions based on the five W1H: who, what, where, when, why, and how.
This process outlines how to efficiently summarize and organize numerous questions into clusters for improved management and comprehension. By using this approach, you can leverage the system's capabilities to structure questions effectively, enhance interactions with the LLM, and incorporate external sources for a more comprehensive understanding.
The system provides the capability to group questions into various clusters, which simplifies organization and makes it more manageable.
<img width="580" height="328" alt="image" src="https://github.com/user-attachments/assets/40576f1b-102f-404c-8d37-3d53269cb08f" />
The LLM efficiently summarizes and clusters similar questions. These summarized questions are easily identified by the interrogation mark. You can view the grouped questions within each node by checking the note.
<img width="523" height="328" alt="image" src="https://github.com/user-attachments/assets/0c4bb676-9505-4e88-b8a4-a8a4e4aa42c6" />
The system can cluster questions from various sources, such as challenges. During interactions with the LLM, users have the opportunity to provide feedback on the answers to express their reasoning and thoughts.
<img width="444" height="334" alt="image" src="https://github.com/user-attachments/assets/e3146c33-3934-44f1-a167-969c8ac3c94f" />
Users can add annotations and assign ratings to the mind map nodes. These ratings are visually represented with different colors within the mind map, allowing for quick navigation and identification of key insights or areas of interest.
<img width="444" height="334" alt="image" src="https://github.com/user-attachments/assets/3acc85d8-9052-4f54-9ca2-c06e11f30f39" />
While interacting with ChatinVis, responses are generated from the LLM's knowledge. However, the system allows users to expand this knowledge by uploading external sources such as PDFs. In these cases, the answers derive from the provided PDFs.
<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/c0015281-e513-4c01-b990-f86f33282b91" />
By examining the source of a node, users can access a description and a text excerpt from the PDF that supports the answers. Users can also request additional answers from the LLM to explore different perspectives, enabling them to compare information from various sources.
In ChatVis, information is systematically organized, enabling users to explore different branches and follow various search paths. Users can review annotations to deepen their understanding and use ratings for quick navigation to identify key points of interest.
<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/370a10e5-ef89-4015-97cc-05a568887924" />
Users have the option to request logs of the current mind map, which provides a review of how the search trail was constructed. These logs encompass details such as selected answers, consulted nodes, timestamps, and node values, offering valuable insights for further analysis.
<img width="436" height="330" alt="image" src="https://github.com/user-attachments/assets/5bbec616-b097-4b5d-a74c-fd9a076197fc" />

## Key Features
### Providing feedback
Users can add annotations and assign ratings to mind map nodes. These ratings are visually represented with different colors within the mind map, allowing for quick navigation and identification of key insights or areas of interest.
Feedback helps you:
- Document your thoughts during exploration
- Rate answers on a scale from 0 to 4
- Quickly identify valuable information through color-coding
- Enable the system to suggest well-rated answers to other users
### Integrating External Knowledge
While interacting with ChatInVis, responses are initially generated from the LLM's knowledge. However, the system allows users to expand this knowledge by uploading external sources such as PDFs. In these cases, the answers derive from the provided PDFs.
By examining the source of a node, users can access:
- A description of the answer
- A text excerpt from the PDF that supports the answer
- Direct links to specific sections in the source document
Users can also request additional answers from the LLM to explore different perspectives, enabling them to compare information from various sources.
### Summarizing Information
The system provides the capability to group questions into various clusters, which simplifies organization and makes it more manageable.
The LLM efficiently summarizes and clusters similar questions. These summarized questions are easily identified by the interrogation mark. You can view the grouped questions within each node by checking the note.
The system can cluster both questions and answers from various sources, helping to:

- Reduce information overload
- Maintain focus on key concepts
- Integrate information from multiple sources
- Create top-level taxonomies of related concepts

### Retracing Your Exploration
In ChatInVis, information is systematically organized, enabling users to explore different branches and follow various search paths. Users can review annotations to deepen their understanding and use ratings for quick navigation to identify key points of interest.
### Viewing Exploration Logs
Users have the option to request logs of the current mind map, which provides a review of how the search trail was constructed. These logs encompass details such as:

- Selected answers
- Consulted nodes
- Timestamps
- Node values
- User actions (askQuestion, selectAnswer, setFeedback, summarize, consultNote)

Logs can be exported and imported in JSON format, enabling sharing of exploration data for collaboration or future analysis.


## Support and Resources
- You can ask support in the following mail: xabier.garmendiad@ehu.eus

- Here there is a video demo: [Drive link](https://drive.google.com/file/d/1aaF5p2dJ937bAass8I8sG15DYCp5M5N2/view?usp=sharing)

- Here you can find some map examples created with Chatin: https://docs.google.com/document/d/1liPEni_1E7nwpLqcZN4sE_DnGSYGupJ7rqfIQaxQcYw/edit?usp=sharing

## Available LLMs
- OpenAI. GPT4 and GPT3.5
- Anthropic. Claude2.0

# DEVELOPERS MANUAL
## Architecture Overview
ChatInVis is a browser extension developed with web development technologies: JavaScript, Node.js, and Gulp. It is developed using Manifest version 3: https://developer.chrome.com/docs/extensions/develop/migrate/what-is-mv3
The web extension follows the standard browser extension architecture with:
- Content script modules: Manage web content
- Background scripts: Manage local storage, MindMeister, and LLM communications

## System Architecture
ChatInVis acts as a bridge between the user, MindMeister, and the LLM. The extension:

- Communicates with the LLM through specific prompts that request responses in JSON format
- Renders the responses as question and answer nodes in the mind map
- Stores logs of user interactions and feedback in Chrome's local storage for later retrieval

The technology used for LLM communication is LangChain, which facilitates seamless integration of different LLM models. Users can configure various models in the extension options page, including:

- OpenAI models (GPT-4, GPT-3.5)
- Anthropic models (Claude 2.0)

## Development Environment
To develop from the source code, you will need to install Node.js and Gulp to build the extension. Required versions:

- Node v12.22
- Gulp v4

## API Documentation
ChatInVis makes use of different APIs:

- MindMeister API: Used to manage the maps - https://developers.mindmeister.com/
- LangChain: Used to interact with different LLM APIs through the LangChain JS library - https://js.langchain.com/docs/get_started/introduction

## Code Structure
The artifact code is organized as follows:

- ![chatin](https://github.com/onekin/Chatin/assets/31988855/ee3f42df-1472-433e-9b87-16dafccb80d7)

These are the main components:
- images. This folder contains the images within the browser extension.
- pages. This folder contains the html files of the extension.
- resources. This folder contains mind map templates and the pdf.js library to process pdfs.
- scripts. This is the main component, it contains the scripts to make the extension work. Based on a web extension architecture this is the main classes:
  - Content Script: content_script.js, this is the script that is executed when MindMeister is accessed
  - Service worker: background.js, this script initializes all the background scripts to enable the communications
  - Options file: options.js, this is the script executed when the option page is opened
  - The rest of scripts are organized in the following folders.
     	- chatin. This folder contains the scripts that are executed in MindMeister.
    		- HomePageManager is executed in MindMeister home page to add the button to create a Chatin map.
    		- MindmapManager is executed when opening a MindMeister map and it handles Chatin's functionality. This is the most important file.
    		- The rest of the files in this folder are classes imported in the two above classes and define the Chatin model (e.g., node names, question templates, prompt styles...)
  	- llm. The main class in this folder is LLMManager, which is executed at the background to establish the communications with Langchain for asking questions to a LLM and with the local storage to manage the variables from the Options page.
     	- mindmeister. This folder contains the scripts to communicate with MindMeister API functionalities
        - utils. This folder contains helper functions which are small pieces of reusable code designed to perform a specific task that supports larger code structures.
Main components:

Content Script: content_script.js - executed when MindMeister is accessed
Service worker: background.js - initializes all background scripts to enable communications
Options file: options.js - executed when the option page is opened

## Building and Testing
To compile the project, you only need to execute the following lines, but make sure you have the node and gulp versions specified in the Development Enviroment section.

	$ npm install
	$ gulp default

## Usage

Run `$ gulp --watch` and load the `dist`-directory into chrome.

## Entryfiles (bundles)

There are two kinds of entryfiles that create bundles.

1. All js-files in the root of the `./app/scripts` directory
2. All css-,scss- and less-files in the root of the `./app/styles` directory

## Tasks

### Build

    $ gulp


| Option         | Description                                                                                                                                           |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| `--watch`      | Starts a livereload server and watches all assets. <br>To reload the extension on change include `livereload.js` in your bundle.                      |
| `--production` | Minifies all assets                                                                                                                                   |
| `--verbose`    | Log additional data to the console.                                                                                                                   |
| `--vendor`     | Compile the extension for different vendors (chrome, firefox, opera, edge)  Default: chrome                                                                 |
| `--sourcemaps` | Force the creation of sourcemaps. Default: !production                                                                                                |


### pack

Zips your `dist` directory and saves it in the `packages` directory.

    $ gulp pack --vendor=firefox

### Version

Increments version number of `manifest.json` and `package.json`,
commits the change to git and adds a git tag.


    $ gulp patch      // => 0.0.X

or

    $ gulp feature    // => 0.X.0

or

    $ gulp release    // => X.0.0


## Globals

The build tool also defines a variable named `process.env.NODE_ENV` in your scripts. It will be set to `development` unless you use the `--production` option.


## Contribution Guidelines
To contribute please contact xabier.garmendiad@ehu.eus.

## License
This project is released under the MIT License.

## Acknowledgments
ChatInVis builds upon the MindMeister platform and leverages the capabilities of Large Language Models through LangChain integration. We thank the research participants who contributed to the evaluation and improvement of this tool.
