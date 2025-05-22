# Supervisor-MultiAgent-WorkFlow
LangGraph MultiAgent WorkFlow

# 🧠 Supervisor Multi-Agent Workflow with LangGraph

This project demonstrates a dynamic multi-agent system built using [LangGraph](https://www.langchain.com/langgraph) and [LangChain](https://www.langchain.com/), where autonomous agents collaborate to execute complex tasks. The workflow leverages OpenAI’s language models and integrates research, enhancement, coding, and validation agents coordinated by a central supervisor.

## 🚀 Project Overview
The system is designed as a message-passing graph where each agent performs a specialized function:

- **Supervisor** – Orchestrates the overall flow and delegates tasks to other agents.
- **Researcher** – Conducts web searches using the Tavily API to gather relevant information.
- **Enhancer** – Refines and enhances user queries for improved clarity and effectiveness.
- **Coder** – Generates Python code using OpenAI's GPT models.
- **Validator** – Reviews the final output or code for accuracy and quality.

## 🛠️ Technologies Used

- **LangGraph** – For building the multi-agent message-passing graph.
- **LangChain** – To implement agents and tool usage.
- **OpenAI GPT Models** – For natural language understanding and code generation.
- **TavilySearchResults** – A web search tool to fetch real-time information.
- **PythonREPLTool** – Enables agents to execute Python code dynamically.
- **Pydantic** – For state management and type safety.
- **dotenv** – For managing environment variables securely.

## 📌 Features

- Modular agent nodes (Supervisor, Researcher, Enhancer, Coder, Validator).
- ReAct-style reasoning framework.
- Fully dynamic and extensible agent graph using `StateGraph` and `MessagesState`.
- Supports autonomous reasoning and multi-step workflows.

🤝 Contributing
Contributions are welcome! Feel free to open issues or pull requests to improve the system or add new agents.

📄 License
This project is licensed under the MIT License.

Feel free to connect with me on LinkedIn if you have questions or suggestions!
- https://www.linkedin.com/in/brijesh-kapadiya-data-science/










