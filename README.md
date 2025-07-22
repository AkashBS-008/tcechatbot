# TCE Chat Assistant

Hey there, everyone! 

It's me, Akash,  
I’m excited to share that I’ve built a **smart AI-powered Chat Assistant** specifically for our **TCE.edu community**! 🎓

This assistant is designed to help students, staff, and visitors get quick and intelligent answers to their questions using data from our official college website (https://tce.edu/) resources.
 answer student and staff queries intelligently using semantic search and Gemini Pro.

![alt text](Testing.png)

---

##  Features

-  **Semantic Search** with Pinecone Vector DB
-  **AI Chat** powered by Google Gemini Pro via LangChain
-  **Streamlit Interface** user friendly UI
-  **Deployable on Hugging Face Spaces**

---

---

##  Environment Variables (Secrets)

| Name              | Description                              |
|-------------------|------------------------------------------|
| `PINECONE_API_KEY`| Your Pinecone API key                    |
| `GOOGLE_API_KEY`  | Your Gemini Pro (Generative Language API) key |
| `HUGGINGFACEHUB_API_TOKEN`  | for language model  |

---

##  Run Locally

1. Clone the repo:

```bash
git clone https://huggingface.co/spaces/akashbs/tce-chat-assistant
cd tce-chat-assistant

pip install -r requirements.txt
Create .env file:

Edit
PINECONE_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
Run the app:

streamlit run app.py

---

🧪 Example Use Case
"What is the mission of college?"
"what is the email id of Abirami mam of IT department?"

✅ AI replies using semantic similarity from institutional docs.

👨‍💻 Author
Akash BS – TCE Student & Developer

📄 License
This project is open-sourced for academic purposes.
---
❤️ Special Thanks
TCE NSS Unit

Hugging Face

Google Gemini

LangChain

---

If you spot any bugs or want to contribute, feel free to ping me.  
Thanks for checking it out, and happy coding! 🚀

Cheers,  
Akash


