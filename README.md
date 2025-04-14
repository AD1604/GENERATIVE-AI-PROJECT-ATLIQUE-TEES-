T-Shirt Inventory Q&A Chatbot (Powered by Google Gemini)

This project is a command-line chatbot designed to answer natural language questions about a t-shirt inventory database. It leverages Google’s Gemini Pro Generative AI model to generate SQL queries and provide human-like responses. The backend database is a MySQL server containing t-shirt inventory data.

📌 Project Overview

The chatbot allows users to interact with an inventory database using natural language. You can ask questions about stock levels, discounts, sizes, or other t-shirt-related data, and the chatbot will convert those into SQL queries, fetch results, and return a human-readable response.

Key Features:
Natural Language Processing: It interprets questions and converts them into SQL queries.

Database Integration: Connects to a MySQL database to fetch inventory data.

Smart Responses: The chatbot uses Google Gemini to convert database results into readable text.

🛠️ Tools & Technologies

Python 3.7+
Google Gemini Pro (Generative AI Model)
LangChain: For integration with AI models and databases.
MySQL: Database for storing t-shirt inventory.
dotenv: For loading environment variables.
Tenacity: For implementing retry logic on failed attempts.
