# Applied Agentic AI

Practical, production-oriented implementations of Agentic AI systems,
focusing on autonomous planning, execution, validation, and multi-agent collaboration.

## What is Agentic AI?

Agentic AI systems are capable of:
- Planning tasks autonomously
- Executing actions using tools
- Maintaining internal state and memory
- Validating and refining outputs
- Working toward long-horizon goals

## Projects

### 1. Autonomous Task Planner Agent

A goal-driven agent that decomposes high-level objectives into actionable steps,
executes them sequentially, and validates results using a plan–execute–verify loop.

Notebook: `agentic_task_planner.ipynb`

**Key concepts:**
- Planning loops
- Agent state and memory
- Validation and reflection

### 2. Multi-Agent RAG System

A retrieval-augmented generation system built using a multi-agent architecture,
where independent agents handle retrieval, answer generation, and critique to
reduce hallucinations and improve answer quality.

Notebook: `multi_agent_rag_langgraph.ipynb`

**Key concepts:**
- Multi-agent system design
- Retrieval-augmented generation (RAG)
- Hallucination detection using a critic agent
- Explicit control flow with LangGraph

### 3. Self-Reflecting Agent with Memory

An autonomous agent that evaluates its own outputs, records failures,
and uses reflection memory to improve future responses over time.

Notebook: `self_reflecting_agent_langgraph.ipynb`

**Key concepts:**
- Self-reflection and critique loops
- Failure memory and learning from mistakes
- Iterative answer refinement
- Agent state persistence with LangGraph

### 4. Tool-Using Agent

An autonomous agent that decides when to invoke external tools, executes them,
and incorporates tool outputs into its final response.

Notebook: `tool_using_agent_langgraph.ipynb`

**Key concepts:**
- Tool selection and invocation
- Action–observation loop
- Agent decision-making
- Explicit control flow with LangGraph

### 5. Re-Ranking Agent in RAG

A retrieval-augmented generation system that introduces a re-ranking agent to
refine retrieved documents before answer generation, improving relevance and
reducing hallucinations.

Notebook: `reranking_agent_rag_langgraph.ipynb`

**Key concepts:**
- Multi-stage retrieval
- Document re-ranking
- Improved context selection
- Explicit control flow with LangGraph