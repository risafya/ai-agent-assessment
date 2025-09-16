# AI-Powered Skill Gap Analyst

This is my submission for the take-home assessment for the AI Developer position at Krenovator.  
The system implements a multi-agent pipeline to parse a CV, analyze skills, compare with market demand, and generate a skill gap report.

---

## 📁 Project Structure
├── agents_parse_cv.py # Agent for parsing .txt CV into structured data
├── agents_skill_analyzer.py # Agent for inferring explicit, implicit, and transferable skills
├── agents_market_agent.py # Agent for gathering market demand for a given role
├── agents_report_agent.py # Agent for synthesizing final Markdown report
├── orchestrator.py # Script that chains all agents to run the full workflow
├── sample_cv.txt # Sample input CV file
├── sample_report.md # Example output report
└── README.md # This file

## ⚙️ Requirements

- Python **3.8+**  
- Third-party libraries:

- Standard libraries: `json`, `os`, `collections`


---

## ▶️ How to Run

```bash
# Clone repo and move to project folder
git clone https://github.com/risafya/ai-agent-assessment.git
cd ai-agent-assessment

# (Optional) Install requirements
pip install requests

# Run pipeline
python orchestrator.py

# This will:
# - Read input from sample_cv.txt
# - Generate output report in sample_report.md
# - Print the report to console

