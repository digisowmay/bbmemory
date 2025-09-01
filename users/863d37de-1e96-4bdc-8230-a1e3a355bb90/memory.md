## Communication Patterns
### Durable (established, 3+ reinforcements)
- prefers concise, one-line commands and follow-ups like “now?” or “sync and try again” to refresh data; 14× (stable since 2025-08-31) [refs: repeated "sync and try again" loops chatId:`12ea94ff333843`; endpoint update command chatId:`21794fdee3394d`; agent creation chatId:`c8d6c6e913d541`]
- expects rapid, real-time updates from tools; 8× (promoted from emerging) [refs: immediate retry requests chatId:`12ea94ff333843`; sync failure follow-up chatId:`c8d6c6e913d541`]

### Emerging (new signals, 1-2 reinforcements)
- prefers context-rich yet concise questions that reference specific past details; 1× (first: 2025-09-01) [ref: instruction to craft short context-rich question chatId:`da5144d6dd564f`]

## Knowledge & Context
### Durable (core expertise, established over time)
- developer at Upsurge Labs working on Bhindi agents; 4× [refs: global instructions introduction; prior chats about role]

### Emerging (recent learning, current focus)
- configuring and troubleshooting Bhindi agents (kg-pdf, kg-bl) and variables; 6× (since 2025-09-01) [refs: kg-auth & kg-pdf setup chatId:`12ea94ff333843`; kg-bl creation chatId:`c8d6c6e913d541`]
- managing a Google Form for recruiting Video Editor Interns; 1× (started: 2025-08-31) [ref: request to see responses]

## Thinking & Working Style
### Durable (core thinking patterns)
- iterative checking approach: asks for updates repeatedly until satisfied; 9× [refs: multiple “sync and try again” loops chatId:`12ea94ff333843`; endpoint update command chatId:`21794fdee3394d`; sync follow-up chatId:`c8d6c6e913d541`]

### Emerging (recent behavioral shifts)
- values up-to-date data accuracy over summary explanations; 3× (last: 2025-09-01) [refs: insisted on continued retries despite error chatId:`12ea94ff333843`; sync failure follow-up chatId:`c8d6c6e913d541`]

## Platform Usage & Queries
### Durable (regular platform activities)
- uses Google Forms agent for listing forms and retrieving response counts; 3× [refs: initial list forms request; multiple getResponses calls]

### Emerging (new query patterns)
- configuring Bhindi agents & variables frequently; 6× (since 2025-09-01) [refs: kg-auth & kg-pdf setup chatId:`12ea94ff333843`; kg-bl creation chatId:`c8d6c6e913d541`]
- monitors recruitment form responses frequently; 2× (since 2025-08-31) [refs: repeated getResponses checks]