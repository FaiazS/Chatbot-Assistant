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
⚙️ Installation
1️⃣ Clone the Repository

git clone https://github.com/FaiazS/Chatbot-Assistant.git
cd AI-Chatbot

2️⃣ Create a Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install Dependencies

pip install -r requirements.txt
🎯 Usage
Run the Chatbot Locally

streamlit run ui.py
🚀 This will start the chatbot interface, accessible at http://localhost:8501/

Run with Ngrok for Public Access

ngrok http 8501

🔗 Copy the generated URL and access the chatbot from anywhere.

🛠️ Deployment
Using Docker

1️⃣ Build the Docker Image

docker build -t ai-chatbot .

2️⃣ Run the Container

docker run -p 8501:8501 ai-chatbot

Deploying on Cloud

✅ Google Cloud Run
✅ AWS EC2 / Lambda
✅ Azure App Service

💡 Future Enhancements

🔹 Multi-language support
🔹 Enhanced memory retention
🔹 Voice-based interactions
🔹 Integration with external APIs

🙌 Contributing

1️⃣ Fork the repository
2️⃣ Create a new branch
3️⃣ Make your changes and commit
4️⃣ Open a Pull Request

🎯 Let's build something amazing together! 😃🔥
