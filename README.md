# Google-Sheets-AI-Agent
An n8n AI agent that analyzes Google Sheets data through chat and automatically emails a structured HTML report when requested

This project is an AI-powered data analysis workflow built with n8n. It uses a chat trigger, Google Gemini Chat Model, Simple Memory, Google Sheets, and Gmail to create a conversational spreadsheet assistant. Users can ask questions about data stored in a connected Google Sheet, such as customer counts, city-wise analysis, summaries, trends, or insights. The AI Agent reads the latest spreadsheet data, analyzes it based on the user’s request, and returns a clear response in the chat. When the user asks to send the result by email in the same prompt, the agent automatically generates a professional HTML report and sends it through the configured Gmail account. The email includes a clear title, short introduction, structured sections, bullet points, highlighted values, and key takeaways. This workflow helps automate spreadsheet analysis and reporting without manually copying data, writing emails, or preparing reports.
Main features:
- Chat-based AI data analyst
- Reads live data from Google Sheets
- Uses Google Gemini for analysis and answers
- Remembers conversation context with Simple Memory
- Generates structured insights from spreadsheet data
- Sends professional HTML reports through Gmail on request
- Automatically creates email content from a single user prompt
- Useful for customer analysis, sales reports, city-wise summaries, counts, and business insights
