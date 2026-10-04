# Capability boundaries

The documented procedure is a supervised, browser-mediated handoff to an existing personal dot. It does not install a background bridge, scheduler, native dots API, MCP server, or new account connection.

Check current official documentation when capabilities matter:
- Messaging routes: https://learn.chatgpt.com/docs/dots/channels
- Task and memory behavior: https://learn.chatgpt.com/docs/dots/tasks-and-memory
- Pause and control semantics: https://learn.chatgpt.com/docs/dots/controls
- MCP Events: https://developers.openai.com/plugins/build/mcp-events
- Usage distinctions: https://learn.chatgpt.com/docs/dots

MCP Events supplies subscribed events; receipt of an event is not completion of a requested task. Do not invent task submission/status/cancellation endpoints from that mechanism. Dot conversations and delegated Work/Codex tasks have different usage treatment; preserve existing allowance/billing boundaries and measure actual savings before claiming them.
