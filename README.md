This repository contains chatbots built with LangChain & Chainlit. The chatbot can answer questions based on a provided Document or plan dynamic Trip itineraries.



https://github.com/VikramDesai/langchain-llama_index-chainlit-LLMagent-chatbots/assets/8145375/216a812a-4f10-42de-8cba-4a0fe865d9bf

Installation: 

1. Clone the repository:
  ``` 
  git clone https://github.com/VikramDesai/langchain-llama_index-chainlit-LLMagent-chatbots.git
  ```
3. To run the examples, you will need to install the following dependencies:
  ```
  !pip install langchain openai tiktoken duckduckgo-search
  ```
4. Once you have installed the dependencies, you can run the example
  ```
  python3 -m  chainlit run HitchHikersGuide.py
  ```
Usage:
 
1.Set your openAI token key inside the file : 
  ```
  os.environ["OPENAI_API_KEY"] = "<openai-key>"
  ```
