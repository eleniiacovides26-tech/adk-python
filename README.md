# adk-python
*By Eleni Iacovides - eleniiacovides26-tech*

Python toolkit for building AI agents with Google's ADK.

Forked from google/adk-python — open-source, code-first toolkit for building, evaluating, and deploying AI agents.

My chain:
- Sep 2025: earthengine-api - satellite/location
- Oct 2025: Gemini CLI codelab
- Dec 2025: adk-docs + n8n-docs - docs & automation
- Now: adk-python - actual Python code for Countess Project

> Official: https://github.com/google/adk-python

### Use for
- Triangulation & location workflows
- Earth Engine + Gemini integration
- Countess Project automation

```python
from google.adk import Agent
agent = Agent(model="gemini-2.0")
agent.run("Map location with Earth Engine")
