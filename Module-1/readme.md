Module 1

Video 1 – Motivation
Learned that LangGraph combines the reliability of fixed control flows (chains) with the flexibility of agents. It enables building structured, customizable, and partially autonomous AI systems that balance deterministic logic with adaptive behavior. (No code was included for this video.)

Video 2 – Simple Graph
Learned about the concept of graph state and how to create a function to track textual differences and timestamp updates each time a node changes. This introduced the idea of monitoring state transitions dynamically within a graph workflow.

Video 3 – LangGraph Studio
Learned how to use the LangGraph Studio UI in a browser to visualize and interact with nodes directly. Explored how to view and modify the graph state within the interface and understood the recursion limits when creating and running assistants in the studio environment.

Video 4 – Chain
Learned how to use messages as state, which enables chat models and tools to interact in a structured, adaptable conversation. Understood that binding tools to a chat model allows the model to request and execute structured tool calls and incorporate the tool outputs back into the message stream for context-aware reasoning.

Video 5 – Router
Learned how LangGraph can route between direct LLM responses and tool executions by inspecting model outputs and using conditional edges. Also learned how ToolNode and tools_condition allow models to make structured tool calls that are executed and integrated back into the message flow, maintaining a smooth reasoning process.

Video 6 – Agent
Learned how a ReAct-style loop allows the model to call tools, observe their outputs, and reason further by feeding the tool responses back into the assistant node. Also explored using MessageState with tool binding and inspecting agent execution in LangSmith to understand how outputs evolve with each reasoning step.

Video 7 – Agent with Memory
Learned how to integrate memory into agents so that they can retain context across interactions. This allows for more coherent and continuous reasoning over multiple steps or sessions, enhancing the agent’s adaptability and performance within LangGraph workflows.
