# AI-MultiSearch-Agent
A LangChain-powered AI search engine that combines Groq LLM, Wikipedia, Arxiv, and DuckDuckGo to provide intelligent multi-source answers through an interactive Streamlit interface. The agent autonomously decides which knowledge source to use, enabling fast research-style responses similar to Perplexity AI.
🚀 AI Multi-Search Agent

An intelligent AI research assistant that searches multiple knowledge sources and synthesizes answers using LLMs and tool-based reasoning.

Instead of simple keyword search, the system uses a LangChain agent that dynamically selects tools such as Wikipedia, Arxiv, and DuckDuckGo to gather information and produce contextual responses.

Built with Groq ultra-fast inference, the system delivers real-time AI powered search.

✨ Features

🤖 LLM Powered Agent

🔎 Multi-Source Search

📚 Wikipedia Integration

🧪 Arxiv Research Paper Search

🌐 DuckDuckGo Web Search

⚡ Groq High-Speed Inference

💬 Interactive Streamlit UI

🔧 Modular LangChain Architecture

🧠 Architecture

User Query
↓
LangChain Agent
↓
Tool Selection

Wikipedia Tool

Arxiv Tool

DuckDuckGo Tool

↓
Groq LLM Reasoning
↓
Final Synthesized Answer

🛠️ Tech Stack

Python

LangChain

Groq LLM

Streamlit

DuckDuckGo Search

Wikipedia API

Arxiv API

📦 Installation

Clone the repository

git clone https://github.com/yourusername/AI-MultiSearch-Agent.git
cd AI-MultiSearch-Agent

Install dependencies

pip install -r requirements.txt
🔑 Environment Variables

Create a .env file

GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
▶️ Run the Application
streamlit run app.py
📂 Project Structure
AI-MultiSearch-Agent
│
├── app.py
├── tools.py
├── agent.py
├── requirements.txt
├── .env
└── README.md
🎯 Use Cases

AI research assistant

Academic paper discovery

Knowledge search engine

AI powered learning assistant

Developer research tool

🔮 Future Improvements

RAG with PDF knowledge base

Vector database integration

Chat history memory

Source citations

Multi-agent architecture
