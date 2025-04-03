# Chatbot-Assistant

An AI chatbot built using LangChain, LangGraph, and Streamlit, featuring real-time web search, memory retention, and interactive streaming responses.

✨ Key Features:

✅ LLM-Powered Conversations – Seamless chatbot interactions using state-of-the-art language models.
✅ Real-Time Web Search – Fetches up-to-date information for accurate responses.
✅ Memory Retention – Remembers past interactions for context-aware conversations.
✅ Streaming Responses – Displays text dynamically while generating answers.
✅ Interactive UI – Built with Streamlit for a smooth user experience.
✅ Ngrok Integration – Enables easy deployment and public access.

🛠️ Tech Stack

Python – Core programming language

LangChain – For AI-powered conversational logic

LangGraph – For managing the chatbot’s flow

Groq AI – Backend LLM powering responses

Streamlit – Web UI for user interaction

Ngrok – Secure tunneling for public access

Tavily API – Web search integration

📂 Project Structure

📂 AI-Chatbot  
│── 📄 chatbot.py             # Main chatbot logic  
│── 📄 ui.py                  # Streamlit-based user interface  
│── 📄 requirements.txt       # Project dependencies  
│── 📄 README.md              # Project documentation  
│── 📂 models                 # LLM integration scripts  
│── 📂 utils                  # Helper functions  
│── 📂 assets                 # Images & other resources  

🚀 Getting Started

⚙️ Running the Chatbot on Google Colab

1️⃣ Open the Colab Notebook

🔗 Google Colab Notebook Link (https://colab.research.google.com/drive/1Xzd0Eb5Dqsfr7o3QPw5QESPXFfPDmXta?usp=sharing)

2️⃣ Install Dependencies (Run this in a Colab cell)

!pip install streamlit langchain langgraph pyngrok tavily

3️⃣ Run Streamlit in the Background

!streamlit run ChatBot_Assistant.py & npx localtunnel --port 8501

🔗 The chatbot UI will be accessible via a public URL.

🌍 Exposing the Chatbot with Ngrok

Since Colab runs in an isolated environment, use Ngrok to expose it publicly.

1️⃣ Authenticate Ngrok (if using a free account)

!ngrok authtoken YOUR_NGROK_AUTH_TOKEN

2️⃣ Run Ngrok to Get a Public URL

!ngrok http 8501

🔗 The generated URL will allow public access to your chatbot.

💡 Future Enhancements

🔹 Multi-language support
🔹 Voice-based interactions
🔹 Improved memory retention
🔹 Customizable themes

🙌 Contributing

1️⃣ Fork the repository
2️⃣ Create a new branch
3️⃣ Make your changes and commit
4️⃣ Open a Pull Request

💡 Contributions are always welcome!

⭐ If you found this helpful, give it a star! ⭐

🎯 Let's build something amazing together! 😃🔥
