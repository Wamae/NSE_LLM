# Leveraging NSE and OpenAI or any Large Language Model to ask pdf questions

This project uses the following technologies:
- ChromaDB
- Langchain
- OpenAI (No preference at all here)

This project highlights how to leverage a ChromaDB vectorstore in a Langchain pipeline to create *drumroll please* a GPT Investment Banker (ergh, I cringed as I wrote that, but alas it's actually pretty practical). You can load in a pdf based document and use it alongside an LLM without the need for fine tuning. 

## How to run the project
-1. Install the required dependencies: `pip install -r requirements.txt`
-2. Add your: `OpenAI APIKey to line 22 of app.py`
-3. Start the app: `streamlit run app.py`




## Reference:
https://github.com/nicknochnack
