# TCE Chat Assistant

Hey there, everyone! 👋

It's me, **Akash**,  
I’m excited to share that I’ve built a **smart AI-powered Chat Assistant** specifically for our **TCE.edu community**! 🎓

This assistant is designed to help students, staff, and visitors get **quick and intelligent answers** to their questions using **semantic search** and **Google Gemini Pro**, with context from our official college website (https://tce.edu/).

![TCE Chat Assistant UI](Testing.png)

---

## 🚀 Features

- ✅ **Semantic Search** with Pinecone Vector DB  
- 🤖 **AI Chat** powered by Gemini Pro (Generative Language API)  
- 💻 **Streamlit Interface** – clean, interactive, and minimal  
- 🌐 **Deployable on Hugging Face Spaces** easily  

---

## 🔐 Environment Variables (Secrets)

Create a `.env` file with the following keys before running the app:

| Name                     | Description                                        |
|--------------------------|----------------------------------------------------|
| `PINECONE_API_KEY`       | Your Pinecone API key                              |
| `GOOGLE_API_KEY`         | Your Gemini Pro (Generative Language API) key      |
| `HUGGINGFACEHUB_API_TOKEN` | (Optional) Your Hugging Face API token if using language models |

---

## 🧑‍💻 Run Locally

### 1. Clone the repository

```bash
git clone [https://huggingface.co/spaces/akashbs/tcechat](https://huggingface.co/spaces/akashbs/tce-chat-assistant)
cd tce-chat-assistant
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Create the `.env` file

Inside the root directory, create a `.env` file and add your keys:

```env
PINECONE_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
```

### 4. Start the application

```bash
streamlit run app.py
```

---

## 💬 Example Queries

> “What is the mission of the college?”  
> “What is the email ID of Abirami mam from the IT department?”

✅ The assistant uses semantic search to fetch accurate, AI-generated responses from institutional documents!

---

## 👨‍💻 Author

**Akash BS**  
TCE Student & Developer  

---

## 📄 License

This project is open-sourced for academic and research purposes.

---

## ❤️ Special Thanks

- TCE College Unit  
- Hugging Face  
- Google Gemini  
- LangChain  


---

If you spot any bugs or want to contribute, feel free to ping me.  
Thanks for checking it out, and happy coding! 🚀

**Cheers,  
Akash**
