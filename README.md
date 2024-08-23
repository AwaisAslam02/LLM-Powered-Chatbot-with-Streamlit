# LLM-Powered-Chatbot-with-Streamlit
This repository demonstrates the integration of advanced Large Language Models (LLMs) with the Streamlit framework to create an interactive chatbot. The chatbot is designed to provide helpful responses to user queries using the power of LLMs like Ollama's model and the LangChain library


Key Features:
LangChain Integration: Utilizes langchain_openai for seamless prompt management and interaction with the LLM.
Ollama's Llama2 Model: Implements the Ollama class to leverage the capabilities of the Llama2 model for natural language processing tasks.
Streamlit Interface: Provides a simple and interactive user interface using Streamlit, making it easy to input queries and receive responses.
Environment Configuration: Uses dotenv to manage API keys and environment variables securely.
How It Works:
Prompt Template: The chatbot uses a prompt template defined with ChatPromptTemplate to structure the interaction.
Model Invocation: The input is processed by the Llama2 model through the Ollama interface.
Response Generation: The chatbot generates responses based on the user's input and displays them in the Streamlit app.
Getting Started:
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Set up your environment variables in a .env file, including your LANGCHAIN_API_KEY.
Run the Streamlit app using streamlit run app.py.
This project is an excellent example of how to build and deploy AI-powered chatbots with modern NLP models and interactive web frameworks. Explore the code to learn more about integrating LLMs into your applications!
