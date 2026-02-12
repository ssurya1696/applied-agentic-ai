# Applied Agentic AI

Practical, production-oriented implementations of **Agentic AI systems**,
focusing on autonomous planning, execution, validation, memory and multi-agent collaboration.

---

## What is Agentic AI?

Agentic AI systems are capable of:
- Planning tasks autonomously
- Executing actions using tools
- Maintaining internal state and memory
- Validating and refining outputs
- Working toward long-horizon goals

---

## Projects

| # | Project | Notebook | Description |
|---:|--------|----------|-------------|
| 1 | Autonomous Task Planner Agent | `agentic_task_planner.ipynb` | A goal-driven agent that decomposes high-level objectives into actionable steps and executes them using a plan–execute–verify loop. |
| 2 | Multi-Agent RAG System | `multi_agent_rag_langgraph.ipynb` | A multi-agent retrieval-augmented generation system where retrieval, answer generation, and critique are handled by separate agents to reduce hallucinations. |
| 3 | Self-Reflecting Agent with Memory | `self_reflecting_agent_langgraph.ipynb` | An agent that critiques its own outputs, records failures, and improves responses over time using reflection memory. |
| 4 | Tool-Using Agent | `tool_using_agent_langgraph.ipynb` | An agent that decides when to invoke external tools, executes them, and integrates tool outputs into final responses. |
| 5 | Re-Ranking Agent in RAG | `reranking_agent_rag_langgraph.ipynb` | A RAG system enhanced with a re-ranking agent to refine retrieved documents and improve answer relevance. |
| 6 | Long-Horizon Goal Agent | `long_horizon_goal_agent_langgraph.ipynb` | An agent that decomposes long-term goals into milestones, tracks progress, and adapts plans based on feedback. |
| 7 | Persistent Memory Agent | `persistent_memory_agent_langgraph.ipynb` | An agent with vector-based persistent memory that retrieves past experiences to influence decisions across runs. |
| 8 | Multi-Agent Collaboration System | `multi_agent_collaboration_langgraph.ipynb` | A system of specialized agents that collaborate through planning, execution, and review to produce higher-quality outcomes. |
| 9 | Self-Evaluating Agent with Metrics | `self_evaluating_agent_langgraph.ipynb` | An agent that evaluates its own outputs using explicit quality metrics and refines responses based on measured performance. |
| 10 | Semantic Graph Memory Agent | `semantic_graph_memory_agent_langgraph.ipynb` | An agent that stores knowledge as a semantic graph (nodes and relationships) and answers questions by reasoning over structured memory. |
| 11 | Enterprise Agent Orchestrator with Observability | `enterprise_agent_orchestrator_langchain.ipynb` | A production-grade LLM orchestration pipeline using LangChain’s ChatOpenAI with environment-based configuration, retry logic, model fallback routing, cost tracking, and structured observability. |
| 12 | Supervisor-Controlled Routing Architecture | `supervisor_controlled_routing_langgraph.ipynb` | A LangGraph-based supervisor architecture where a central governance agent dynamically routes tasks to specialized agents based on intent classification and policy rules. |
| 13 | Planner–Executor–Verifier Architecture | `async_planner_executor_verifier_langgraph.ipynb` | An asynchronous LangGraph-based Planner–Executor–Verifier agent architecture. |
| 14 | Event-Driven Agent Architecture | `event_driven_agent_architecture_langgraph.ipynb` | A LangGraph-based event-driven agent system where agents react to emitted events through conditional routing. |
| 15 | Blackboard Multi-Agent Architecture | `blackboard_agent_architecture_langgraph.ipynb` | Independent specialist agents collaborate by reading and writing to shared memory instead of directly invoking one another. |
| 16 | Distributed Agent Execution | `distributed_agent_execution_simulation_langgraph.ipynb` | A LangGraph-based distributed agent execution simulator that parallelizes task processing across worker pools using asynchronous orchestration. |

---

## Notes

- All projects are implemented using **LangGraph** for explicit control flow and state management.
- The focus is on **reliability, explainability and production-oriented agent design**, not just prompt chaining.
