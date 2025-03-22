# AI Data Scientist Agent

An intelligent, modular, and interactive **agentic software system** that assists data analysts and engineers in exploring, validating, and analyzing datasets — just like a real data scientist would. Built with human-in-the-loop design and explainability at its core, it offers natural language interaction, visible reasoning, and flexible data connectivity.

---

## Project Overview

**AI Data Scientist Agent** is a desktop or web-based application that:
- Accepts data from uploaded files or databases
- Analyzes and profiles the data (EDA)
- Identifies and justifies feature selection
- Guides users through each decision step with visual and textual insights
- Learns and adapts from user feedback
- Presents its “thought process” in a sidebar notebook for full transparency

---

## Key Features

| Feature                       | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| Conversational UI             | Natural language chat interface to guide analysis                          |
| Data Handling                 | Upload CSV/XLSX files or connect to PostgreSQL with schema-based access     |
| EDA Agent                     | Performs data profiling, null detection, statistical summaries              |
| Feature Selection Agent       | Correlation, missingness, and signal analysis to identify key features      |
| Thought Notebook              | Transparent logging of agent decisions and logic                            |
| Visualization Support         | Interactive charts (Plotly/Matplotlib) to justify suggestions               |
| Human-in-the-Loop             | User confirms each decision or suggests alternatives                        |
| Modular Architecture          | Each agent is plug-and-play; easily extendable                              |

---

## Getting Started

✅ CSV and Excel (.csv, .xlsx)

✅ PostgreSQL (via credentials)

🧪 Future: MongoDB, APIs, Snowflake, BigQuery


📈 Example Use Case
"I have a table in my PostgreSQL database with motor readings. I want to know how long each motor has been running over the past 4 years."

The agent will:

Connect to the database, pull the specified table

Profile features like current, torque, state_run

Identify the most reliable signal (e.g., torque) based on data quality

Show a time-series plot of torque vs. time

Estimate runtime by analyzing threshold-based operation periods

Ask: “Should I proceed with torque as your runtime indicator?”

Log all thoughts, suggestions, and alternatives in the notebook


🧠 Agent System (MVP)
Data Agent: Handles file uploads and database ingestion

EDA Agent: Profiles the data and finds patterns

Feature Agent: Ranks and explains useful features

Controller: Orchestrates the flow and user interaction

🚧 Roadmap
 CSV/XLSX ingestion

 PostgreSQL schema-aware ingestion

 EDA agent with plots

 Feature selector agent (mutual info, chi2)

 Modeling agent (AutoML + interpretability)

 Full UI with Copilot-style chat + notebook

 Multi-user session support

 Cloud deployment option


### Local Setup

```bash
git clone https://github.com/your-username/ai-data-scientist.git
cd ai-data-scientist
pip install -r requirements.txt


📜 License
MIT License © 2025 Ranjith