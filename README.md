## Prerequisites

- Node.js version 18 or higher
- OpenAI API key (obtain from https://platform.openai.com/account/api-keys)
- SERP API key (obtain from https://serpapi.com/)

## Getting Started

1. Clone the repository:
   
   git clone 

2. Install dependencies:
 
   npm install langchain hnswlib dotenv
 

3. Create a `.env` file in the root directory and add your API keys:
 
   OPENAI_API_KEY=your_openai_api_key
   SERPAPI_API_KEY=your_serp_api_key


4. Run the `index.js` script to see AutoGPT in action:

   node index.js
  

## How It Works

The `index.js` script performs the following steps:

- Imports necessary modules from Langchain, including AutoGPT, ReadFileTool, WriteFileTool, SerpAPI, NodeFileStore, HNSWLib, OpenAIEmbeddings, and ChatOpenAI.
- Configures dotenv to manage environment variables.
- Instantiates NodeFileStore, tools for file operations and SERP API, and HNSWLib with OpenAI embeddings.
- Creates an AutoGPT instance with the ChatOpenAI model, tools, and memory.
- Demonstrates how to use AutoGPT to perform tasks and generate content.

