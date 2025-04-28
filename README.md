# Enterprise-grade, agentic RAG over complex real-world docs

The project uses EyelevelAI's state of the art document parsing and retrieval system GroundX. It's integrated as a custom tool with CrewAI.

Before you start, quickly test it on your own document [here](https://dashboard.eyelevel.ai/xray)

GroundX can also be deployed completely on premise as well, the code is open-source, here's their [GitHub repo](https://github.com/eyelevelai/groundx-on-prem).

Grab your API keys's here.
- [GroundX API keys](https://docs.eyelevel.ai/documentation/fundamentals/quickstart#step-1-getting-your-api-key)
- [SERPER API keys](https://serper.dev/)

---
## Setup and installations

**Setup Environment**:
- Paste your API keys by creating a `.env`
- Refer `.env.example` file


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install groundx crewai crewai-tools
   ```
**Running the app**:
```bash
streamlit run app_deep_seek.py
```


