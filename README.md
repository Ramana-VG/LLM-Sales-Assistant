# LLM-Sales-Assistant: LLM-powered Personal Sales Enablement Assistant

🚀 Project Overview
SaleCoach is an intelligent agent designed to empower sales representatives with AI-driven insights and memory. Built using Large Language Models (LLMs) and LangGraph, this notebook demonstrates how to build an AI Sales Assistant that can:

Store and update sales rep profiles and preferences.

Maintain both semantic memory (contextual knowledge) and procedural memory (specific instructions).

Fetch data dynamically from multiple sources — such as the web, local databases, CRM, or internal knowledge bases (vector DB).

Personalize its coaching style based on the rep’s evolving needs.

🧩 Key Features
✅ Semantic & Procedural Memory Management
✅ Customizable Coaching Styles & Content Formats
✅ Dynamic Web & Knowledge Base Access
✅ Uses LangGraph for short-term and long-term memory storage
✅ Integrates with MySQL for conversation storage (DB setup steps are described)

📚 What’s Inside
This notebook includes:

Conceptual goals for the SaleCoach agent.

Example steps to configure databases.

Python code cells to connect to MySQL.

Tool calling for memory storage and knowledge retrieval.

Use of LangGraph for memory orchestration.

🛠️ How to Use
Clone the Repository

git clone https://github.com/Ramana-VG/LLM-Sales-Assistant.git
cd LLM-Sales-Assistant
Install Requirements
Make sure you have Python 3.10+ and install dependencies:

pip install -r requirements.txt
Configure Database

The notebook assumes a MySQL database connection.

Update your credentials in the code cells.

Run the Notebook
Open salesagent_toolcall.ipynb in Jupyter or VSCode and follow the cells step by step.

🔍 Example Use Case
“Hey SaleCoach, I prefer short bullet-style rebuttals for hesitant leads.”

SaleCoach will update the rep’s preferences and tailor its advice accordingly!

⚙️ Tech Stack
🧠 LLMs (OpenAI/GPT)

🔗 LangGraph (Memory Orchestration)

💾 MySQL (Conversation Storage)

🗃️ Vector DB (Semantic Search)

📈 Future Improvements
Add full conversational UI.

Connect to live CRM systems.

Deploy as a cloud microservice.

Implement RAG (Retrieval-Augmented Generation).

👨‍💻 Author
Created by Ramana — showcasing applied LLM workflows for smart agent development.

Happy Selling! ✨
