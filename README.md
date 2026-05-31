⚡ SwiftMind
A ChatGPT-style AI chat app built with Streamlit and LangChain, powered by LLaMA 3.1 8B on Groq.

🚀 Getting Started
1. Clone the repo
bashgit clone https://github.com/your-username/swiftmind.git
cd swiftmind
2. Install dependencies
bashpip install streamlit langchain-groq langchain-core
3. Run
bashstreamlit run app.py

📦 Requirements
streamlit>=1.35.0
langchain-groq>=0.1.6
langchain-core>=0.2.0

📁 Project Structure
swiftmind/
├── app.py            # Main app
├── requirements.txt  # Dependencies
└── README.md

🔗 Live App: [AI Agent (Streamlit)](https://aiagent-dkmjkcy9632mbypgbppnbs.streamlit.app/#ai-agent-powered-by-l-la-ma-3-1-groq)
⚙️ Switching Models
Change the model in app.py:
pythonllm = ChatGroq(model="llama-3.1-8b-instant", api_key=API_KEY)
ModelSpeedllama-3.1-8b-instantFastestllama-3.1-70b-versatileBalancedmixtral-8x7b-32768High quality

🛠 Built With

Streamlit
LangChain
Groq
LLaMA 3.1 — Meta AI


SwiftMind — Fast answers. Zero wait.

