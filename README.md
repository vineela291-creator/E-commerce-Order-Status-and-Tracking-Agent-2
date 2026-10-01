🛒 E-commerce Order Status & Tracking Agent

📌 Project Overview

The E-commerce Order Status & Tracking Agent is an AI-powered automation workflow built using n8n. It helps customers get their order status and tracking information through chat.

The agent receives a customer's order-related message, identifies the order ID, retrieves the corresponding order details from Google Sheets, and uses an AI model to provide a clear and simple response.

🎯 Project Goal

The main goal of this project is to automate customer order-status queries and provide quick, accurate, and easy-to-understand tracking information.

✨ Key Features

- 💬 Accepts customer order-status questions through Telegram.
- 🔎 Identifies the customer's Order ID.
- 📊 Retrieves order information from Google Sheets.
- 🤖 Uses an AI Agent to process the request.
- 🧠 Uses the MiniMax Chat Model for AI-powered responses.
- 📦 Provides order status and tracking information.
- ⚡ Reduces manual customer-support work.
- 💡 Gives customers quick and clear responses.

🛠️ Technologies Used

- n8n – Workflow automation
- Telegram – Customer chat interface
- Google Sheets – Order information storage
- AI Agent – Processes customer requests
- MiniMax Chat Model – Generates AI responses

🔄 Workflow

Customer
   ↓
Telegram Message
   ↓
AI Agent
   ↓
Identify Order ID
   ↓
Google Sheets
   ↓
Retrieve Order Details
   ↓
MiniMax Chat Model
   ↓
Generate Response
   ↓
Customer receives Order Status

📋 Example

Customer Message:

«Where is my order? My Order ID is ORD1001.»

Agent Process:

1. Receives the message through Telegram.
2. Extracts the Order ID.
3. Searches the order information in Google Sheets.
4. Retrieves the current order status and tracking details.
5. Generates a simple response using the AI model.

Example Response:

«Your order ORD1001 is currently shipped and is in transit. The latest tracking information is available in the order details.»

📊 Order Data

The Google Sheet contains information such as:

- Order ID
- Customer Name
- Product
- Order Status
- Tracking ID
- Delivery Status
- Expected Delivery Date

🚀 Benefits

- Faster customer support
- Automated order-status checking
- Easy access to order information
- Reduced manual effort
- Simple and user-friendly interaction
- Scalable automation workflow

👥 Team

This project was developed as a team project using n8n and AI-powered automation.

📌 Conclusion

The E-commerce Order Status & Tracking Agent demonstrates how AI and workflow automation can be combined to improve e-commerce customer support. By connecting Telegram, Google Sheets, n8n, and an AI model, the system can automatically process customer queries and provide relevant order-tracking information.
