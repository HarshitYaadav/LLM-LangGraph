
Module 2

Video 1 – Simple Schema
Learned about typed state schemas using TypedDict, dataclass, and Pydantic, which ensure every node follows a consistent contract so that LangGraph graphs remain predictable.

Video 2 – Simple Reducers
Learned that reducers allow parallel nodes to safely merge updates, maintaining a deterministic state. Also learned how annotated keys can switch between overwrite, append, or custom merge behaviors without needing to rewrite nodes.

Video 3 – Multiple Schemas
Learned that private states allow nodes to exchange temporary (scratch) variables without affecting the public schema or final output. Also explored how dedicated input/output schemas define what data enters and leaves the graph, while an internal schema retains all working fields for logic and computation.

Video 4 – Trim Filter Messages
Learned that message reducers, filters, and trimmers control how much of the conversation log reaches the model at each turn. Maintaining consistent message channels allows reshaping of chat threads without disrupting the LangGraph structure.

Video 5 – Chatbot with Summarizing Messages and History
Learned that a running outline enables the chatbot to compress conversation history, while LangGraph ensures persistence across steps and threads. Also learned about conditional edges, which determine when to refresh the outline so the model receives structured context without reprocessing the entire conversation.

Video 6 – Chatbot with Summarizing Messages and External Memory
Learned how external checkpointers such as SQLite can persist each thread’s state, allowing the chatbot to resume conversations with retained memory and reduce token usage.
