# Local ChatGPT with Llama-3 memory

These steps are to build an LLM application with memory using Llama-3 to run locally on your computer. This is facilitated with the help of LM Studio. It is an application like VS Code for experimenting with local and open-source Large Language Models (LLMs).

1. Install & import the necessary Python libraries: **openai** and **streamlit** <br/>
 ***Streamlit***  is an open-source Python library that lets you create interactive web apps easily, perfect for data science and machine learning projects.
2. Now, deploy Llama-3 locally &  create OpenAI like API :<br/>
   a) Download and Install LMStudio App<br/>
   b) Download Llama-3 8B Instruct Model<br/>
   c) Start the server<br/>

3. To build a chatting application similar to ChatGPT, we use Streamlit which lets us create interactive user interfaces with Python: <br/>
   a) Setup the Streamlit App <br/>
   b) Point the local server setup to LM Studio <br/>
   c) Initialize and display chat history <br/>
   d) Accept the user input <br/>
   e) Generate response and display <br/>

   ***To accomplish the above steps, we use the below streamlit methods*** : <br/><br/>

   **i)** ***session_state:*** allows you to store and manage state across different user interactions and sessions. This is particularly useful for preserving information like user inputs that needs to persist between reruns of the script. <br/><br/> 
   **ii)** ***chat_message:*** refers to the messages exchanged in a chat-like interface.<br/><br/>
   **iii)** ***markdown:*** is used to format text in the app.<br/><br/>

   **To run the application, use the following command: 'streamlit run local_chatgpt_memory.py'** <br/><br/>
   ![image](https://github.com/BhanuTeja-007/Local_LLM_App/assets/61819785/6bb2b836-bec8-48dd-88f3-af8b13a76313)

   
   
   
