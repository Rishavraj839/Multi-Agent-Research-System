# Multi-Agent-Research-System
Four specialised AI agents — Search · Reader · Writer · Critic — collaborate in sequence to produce deep, structured research on any topic.


## 🚀 Live Demo
👉 https://multi-agent-research-system-zryspmkbbjdwczaqb8ezp3.streamlit.app/

This project is an **AI-powered multi-agent research system** that autonomously performs deep research on any given topic.

It mimics how a human researcher works by breaking the task into multiple specialized agents:

- 🔍 Search Agent → Finds relevant information
- 📖 Reader Agent → Extracts detailed content from sources
- ✍️ Writer Agent → Generates structured report
- 🧠 Critic Agent → Reviews and improves the report

The system follows a **pipeline-based architecture**, enabling modular and scalable AI workflows.


## 🏗️ Architecture

User Query
   ↓
Search Agent → Fetches relevant sources
   ↓
Reader Agent → Scrapes & extracts content
   ↓
Writer Agent → Generates report
   ↓
Critic Agent → Reviews & improves output
   ↓
Final Output



## 🔄 Pipeline Flow

The system is orchestrated via `pipeline.py`:

1. Search Agent retrieves relevant information
2. Reader Agent selects and extracts content from top sources
3. Writer Agent generates a structured research report
4. Critic Agent evaluates and refines the report

State is maintained across steps to pass context between agents.


## 🛠️ Tech Stack

- LangChain / LangGraph (for agent orchestration)
- LLM APIs (Groq / HuggingFace / OpenAI)
- Streamlit (for UI deployment)
- Python


## ✨ Features

- Multi-agent architecture (not a single LLM)
- Autonomous research pipeline
- Tool usage (search + scraping)
- Modular and extensible design
- Real-time research generation



