Module 3

Video 1 – Streaming
Learned about multiple streaming modes: values mode streams the full graph state after each node executes, updates mode streams only the changes to the state, messages mode supports message-based workflows, and astream_events enables real-time token streaming.

Video 2 – Breakpoints
Learned that breakpoints allow human-in-the-loop workflows by pausing graph execution at specific nodes using interrupt_before, enabling inspection, debugging, and approval before critical operations. Also learned how to resume execution after breakpoints.

Video 3 – Editing State and Human Feedback
Learned that state editing allows direct modification of the graph state during breakpoints using the update_state function, making it possible to correct the agent’s behavior during execution.

Video 4 – Dynamic Breakpoints
Learned that dynamic breakpoints using NodeInterrupt enable runtime-based conditional interruptions with custom error messages, providing more flexible control than compile-time breakpoints and supporting self-interruption based on logic evaluated within nodes.

Video 5 – Time Travel
Learned that time travel enables debugging through inspection of state history using get_state_history(), allowing replay of past states or branching into new execution paths from any checkpoint without losing the original branch.
