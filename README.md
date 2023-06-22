## LLM Chatbot
This is a web application that allows you to interact with GPT, augmented with a graph database based on PubMed. 
Base code and idea from: https://medium.com/towards-artificial-intelligence/using-large-language-models-to-build-a-biomedical-chatbot-and-deploying-it-af7818a0ab7f

### Installation
```bash
conda create -n llm_chatbot python=3.9.7
pip install requirements.txt
```

### How to run?
```bash
streamlit run streamlit_app.py
```

### How to use?
Enter a query in the text box and press enter to receive a response.

Ex query: "Give me an article from 2023 published in The lancet. Gastroenterology & hepatology."

### How does it look like?
![Prototype](https://github.com/Koris/llm_chatbot/blob/main/prototype.jpg?raw=true)