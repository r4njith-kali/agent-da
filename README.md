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

### Local Setup

```bash
git clone https://github.com/your-username/ai-data-scientist.git
cd ai-data-scientist
pip install -r requirements.txt