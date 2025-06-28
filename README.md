This n8n workflow demonstrates how to create an agent using LangChain and SQLite. The agent can understand natural language queries and interact with a SQLite database to provide accurate answers. 💪

🚀 Setup
Run the top part of the workflow once.
It downloads the example SQLite database, extracts from a ZIP file and saves locally (chinook.db).

🗣️ Chatting with Your Data
Send a message in a chat window.
Locally saved SQLite database loads automatically.
User's chat input is combined with the binary data.
The LangChain Agend node gets both data and begins to work.
The AI Agent will process the user's message, perform necessary SQL queries, and generate a response based on the database information. 🗄️

🌟 Example Queries
Try these sample queries to see the AI Agent in action:

"Please describe the database" - Get a high-level overview of the database structure, only one or two queries are needed.
"What are the revenues by genre?" - Retrieve revenue information grouped by genre, LangChain agent iterates several time before producing the answer.
The AI Agent will store the final answer in its memory, allowing for context-aware conversations. 💬
