## Agentic Research Writer
### Capabilities:
- Assistant (Supervisor Agent 1)
- Web search (Agent 2)
- Document RAG (Agent 3)
    - Web docs
    - PDF docs
    - Docx docs
- SQL RAG (Agent 4)
- Documentation (Agent 5)

### Workflow
1. The user talks to the Assistant, which is a supervisor agent that delegates tasks to other agents, and responds to the user in an understandable way.
2. Based on user query, the Assistant will formulate and delegate tasks to:
3. Web search agent to search the web and retrieve information.
4. Document RAG agent to retrieve information from user provided docs.
5. SQL RAG agent to retrieve information from a user provided database.
6. Documentation agent to structure generated content in a document and write to a file.
7. The Assistant will receive information where necessary and respond to the user.

### Current Version
- Assistant agent
- Web search agent
- Document Retrieval agent (Web docs, PDF docs)
- SQL agent

### How to run:
- From project root, run ```pip install -r requirements```
- You can use ```uv``` to manage your packages for this project.
- Then, from the project root, do ```uv run python src/app.py``` for a minimal interface to test capabilities.
