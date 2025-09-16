# AI Agent Developer Assessment

This project implements a multi-agent system for analyzing a candidate CV against job market demands.

## Agents
1. **CV Parsing Agent** – parses a `.txt` CV into structured JSON/dict.
2. **Skill Analyzer Agent** – infers explicit, implicit, and transferable skills.
3. **Market Intelligence Agent** – fetches/simulates job postings and extracts in-demand skills.
4. **Report Agent** – produces a Markdown skill gap analysis and upskilling plan.

## Orchestrator
The agents are chained in `orchestrator.py` to form a complete workflow.

## How to Run
```bash
pip install -r requirements.txt
python orchestrator.py
