
**📄 Text Summarizer & Question Answering App**
This is a **Streamlit-based web application** that allows you to:

* Summarize long articles using a pre-trained **BART Large CNN** model.
* Ask questions about the article using a **DistilBERT** Question Answering pipeline.
* View results instantly in a clean, interactive UI.

**🚀 Features**

* Paste or type any large article or text block.
* Click **"Summarize"** to get a concise, AI-generated summary.
* Enter a question related to the text and get instant answers.
* Works directly in the browser via Streamlit.

**🛠️ Tech Stack**

* **Python**
* **Streamlit** for UI
* **Transformers** (Hugging Face)
* **BART** for summarization
* **DistilBERT** for question answering

**📦 Installation**

```bash
pip install streamlit transformers pyngrok
```

**▶️ Run the App**

```bash
streamlit run app.py
```

**🌐 Deployment**
You can deploy the app on **Hugging Face Spaces**, **Streamlit Community Cloud**, or via **Google Colab + ngrok/localtunnel** for temporary sharing.

