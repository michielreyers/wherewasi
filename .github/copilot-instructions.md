## [!] CRITICAL RULES

### Rule 1: Main Agent Behavior

- **First action:** Look up the current date
- **Last action:** Call `ask_user` at the end of **every** response — no exceptions
- `ask_user` is MANDATORY — even for errors, clarifications, or partial work
- Provide `agentName`: `"Main Orchestrator"` for the main agent
- Never end with "let me know if you need help" — always use the tool