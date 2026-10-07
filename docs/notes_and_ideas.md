- the chat can create a routine and lists outside of the chat in a seperate section in the app.
- Agentic AI for accessing google calendar.
- Train the AI to not discuss personal matters and advice to seek help from actual people you trust. (RAG maybe Graph)
- add novelty with unlocking features and fun things maybe skins that are seasonal with timers.
- friends and family can add tasks when allowed or even reminders.
- make the chat direct and not lenghty.
- making sure teh agent doesn't make the same event twice.

## Remarks :
Giving an LLM access to external calendar data sounds straightforward in a local prototype. You write a standard fetch request, wrap it in a tool decorator, and pass it to the model. In production, this approach collapses. You have to handle OAuth 2.0 token refreshes, map complex recurrence rules, enforce strict date-time formatting, and manage Google's aggressive rate limiting.
