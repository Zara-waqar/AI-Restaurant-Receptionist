# AI Restaurant Receptionist

This project is an AI-powered restaurant receptionist built using **n8n** and **GPT-5 mini**. It was created to automate the everyday conversations restaurants have with their customers while reducing manual work for staff.

The assistant can answer questions about the restaurant, help customers book tables, update or cancel reservations, and send confirmation emails automatically. It also uses a **Supabase Vector Store** so it can answer restaurant-specific questions based on the restaurant's own information instead of relying only on the language model.

> **Note:** The workflow was built for Instagram integration. The public deployment is currently inactive.

---

## What this assistant can do

- Answer customer questions about the restaurant
- Help customers book a table
- Update existing reservations
- Cancel reservations
- Answer questions about the menu
- Provide opening hours and restaurant information
- Retrieve information about deals and promotions from the knowledge base
- Send reservation confirmation emails
- Create reservation events in Google Calendar
- Store reservation details in Google Sheets

---

## Technologies Used

- **n8n**
- **GPT-5 mini (OpenAI)**
- **Supabase Vector Store**
- **Google Calendar**
- **Google Sheets**
- **Gmail**
- **Instagram**
- **HTTP APIs**

---

## How the workflow works

When a customer sends a message, the AI first understands what the customer wants.

If the customer wants to make a reservation, the assistant collects the required details, creates a booking in Google Calendar, stores the reservation in Google Sheets, and sends a confirmation email.

If the customer asks about the restaurant, such as the menu, opening hours, or available deals, the assistant searches the restaurant knowledge base stored in Supabase before generating a response.

---

## Why I built this project

I wanted to build something that solves a real business problem rather than a simple chatbot. Restaurants receive many repetitive customer queries every day, and this workflow shows how AI agents can automate those conversations while integrating with existing business tools.

The project also helped me gain hands-on experience with AI agents, RAG, vector databases, API integrations, and workflow automation using n8n.

---

## Skills Demonstrated

- AI Agent Development
- Workflow Automation
- Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- Vector Database Integration
- API Integration
- Google Workspace Automation
- LLM Applications
- Business Process Automation

---

## Repository Contents

- `workflow.json` – Exported n8n workflow
- `README.md` – Project documentation
- `screenshots/` – Images of the workflow and project
- `architecture/` – Workflow architecture diagram *(coming soon)*

---

## Future Improvements

Some features I plan to add in the future include:

- Voice-based reservations
- WhatsApp integration
- Multi-language support
- Admin dashboard for reservation management
- Analytics and reporting

---

## Author

**Zara Bukhari**

BS Software Engineering Student

Interested in AI Automation, LLM Applications, and Workflow Engineering.
