Auto-Gen AutoReportGenerator 🤖📊
An automated intelligence system built with AutoGen and RAG (Retrieval-Augmented Generation) to analyze data, generate visualizations, and send comprehensive marketing and sales reports via HTML email.

🌟 Features
Multi-Agent Orchestration: Utilizes AutoGen agents to collaborate on data analysis and report writing.

RAG Integration: Uses vector_db.py and rag_retrieval.py to query internal knowledge bases for context-aware reporting.

Automated Visualizations: Automatically generates performance charts (PNGs) for sales, ROI, and regional trends.

HTML Email Engine: Sends polished, templated reports directly to stakeholders.

Task Scheduling: Includes a scheduler to automate daily and quarterly reporting cycles.

🏗️ Project Structure
Plaintext

├── agent.py               # AutoGen agent configurations
├── report_generator.py    # Main logic for compiling reports
├── vector_db.py           # Vector database management (ChromaDB)
├── visualizations.py      # Matplotlib/Seaborn logic for charts
├── config.py              # Environment and API configurations
├── email_sender_html.py   # SMTP/Email logic
└── requirements.txt       # Project dependencies
🚀 Getting Started
1. Prerequisites
Python 3.10+

OpenAI API Key (or other LLM provider)

2. Installation
Clone the repository and set up the virtual environment:

Bash

git clone https://github.com/Dhamodharam-vk/Auto-Gen-AutoReportGenerator.git
cd Auto-Gen-AutoReportGenerator
python -m venv .venv
source .venv/bin/scripts/activate  # On Windows use: .venv\Scripts\activate
pip install -r requirements.txt
3. Configuration
Create a .env file in the root directory (this is ignored by Git) and add your credentials:

Plaintext

OPENAI_API_KEY=your_api_key_here
EMAIL_PASSWORD=your_app_password
SMTP_SERVER=smtp.gmail.com
4. Usage
To trigger the report generation agent:

Bash

python agent.py
🛠️ Built With
AutoGen: For agentic workflow.

ChromaDB: For vector storage and retrieval.

Pandas/Matplotlib: For data processing and visualization.

Python-dotenv: For secure configuration management.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

How to add this to your GitHub:
Create a new file in your local folder named README.md.

Paste the content above into it and save.

Run these commands:

PowerShell

git add README.md
git commit -m "Add project documentation"
git push origin main
