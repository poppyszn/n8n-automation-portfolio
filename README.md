# n8n Automation Portfolio

![n8n Diagram](./n8n.png)

A collection of workflow automation projects built with n8n, demonstrating practical automation solutions for real-world business problems, from simple data transformations to AI-powered assistants.

## 🎯 About This Repository

This repository showcases my journey learning workflow automation and building practical solutions that streamline business processes. Each project demonstrates different integration patterns, data flows, automation strategies, and progressive skill development - from basic webhooks to advanced AI agents.

## 📁 Projects

### [Lead Qualification Automation](./lead-qualification)
Automated lead capture and routing system that filters prospects by budget and sends personalized responses.

**Key Features:**
- Form submission capture and Google Sheets logging
- Budget-based lead filtering and routing
- Personalized email responses with calendar booking
- Sales team notifications

**Technologies:** n8n, Google Sheets, Gmail, Webhooks  
**Complexity:** ⭐⭐⭐ Intermediate

---

### [Webhook Data Transformer](./webhook-transformer)
Simple webhook receiver that captures form submissions, transforms nested JSON data, and forwards to external endpoints.

**Key Features:**
- Webhook endpoint for form submissions
- Data extraction from nested JSON structures
- HTTP request forwarding with custom body parameters
- Request debugging with RequestCatcher

**Technologies:** n8n, Webhooks, HTTP Requests, Tally Forms  
**Complexity:** ⭐ Beginner

---

### [Daily Lead Digest](./daily-lead-digest)
Scheduled automation that queries Google Sheets for new leads, filters and aggregates them, then sends a formatted daily summary email.

**Key Features:**
- Time-based scheduling (daily at 7 PM)
- Dynamic date filtering for today's leads
- Boolean logic filtering (excludes called/rejected leads)
- JavaScript-based data formatting
- Automated email digest delivery

**Technologies:** n8n, Google Sheets, Gmail, JavaScript, Cron  
**Complexity:** ⭐⭐ Intermediate

---

### [AI Task & Calendar Manager](./ai-task-manager)
Conversational AI agent powered by GPT that manages tasks and calendar events through natural language chat.

**Key Features:**
- Natural language task and event creation
- Smart calendar event search and management
- Google Sheets task tracking with priorities
- Conversation memory for context awareness
- Multi-tool coordination (Calendar + Sheets)

**Technologies:** n8n, LangChain, GPT (OpenRouter), Google Calendar, Google Sheets  
**Complexity:** ⭐⭐⭐⭐ Advanced

---

## 🛠️ Tech Stack

### Core Technologies
- **n8n** - Workflow automation platform and orchestration engine
- **Google Sheets** - Data storage and lightweight CRM
- **Gmail** - Email automation and notifications
- **Google Calendar** - Event and appointment management

### Advanced Integrations
- **LangChain** - AI agent framework
- **OpenRouter/GPT** - Large language models
- **Webhooks** - Real-time event triggers
- **HTTP APIs** - External service integration
- **JavaScript/Code Nodes** - Custom data transformations

## 💡 Skills Demonstrated

### Foundational
- ✅ Workflow design and optimization
- ✅ API integrations and OAuth
- ✅ Webhook handling and HTTP requests
- ✅ Data mapping and transformation
- ✅ Conditional logic and filtering

### Intermediate
- ✅ Scheduled automations (cron)
- ✅ Multi-step data pipelines
- ✅ JavaScript for custom logic
- ✅ Error handling and validation
- ✅ Email template design

### Advanced
- ✅ AI agent development
- ✅ Natural language processing
- ✅ Multi-tool orchestration
- ✅ Conversation memory management
- ✅ LangChain integration

## 🚀 Getting Started

Each project folder contains:
- `README.md` - Comprehensive documentation
- `*.json` - n8n workflow file (importable)
- `screenshots/` - Visual workflow diagrams

### Quick Start
1. Install [n8n](https://n8n.io/) (local or cloud)
2. Navigate to desired project folder
3. Import the `.json` file into n8n
4. Follow project-specific setup in README
5. Configure credentials (Google, APIs, etc.)
6. Test and activate the workflow

### Prerequisites
- n8n instance (self-hosted or cloud)
- Google account (for Sheets/Gmail/Calendar projects)
- Basic understanding of APIs and webhooks
- For AI projects: LLM API key (OpenRouter/OpenAI)

## 📈 Project Progression

This portfolio is organized to show skill progression:

1. **Webhook Transformer** (Start Here)  
   → Learn webhook basics and data transformation

2. **Lead Qualification**  
   → Add conditional logic and multi-step workflows

3. **Daily Lead Digest**  
   → Master scheduling and data aggregation

4. **AI Task Manager**  
   → Combine everything with AI capabilities

## 🎓 Learning Resources

**Recommended for Beginners:**
- [n8n Documentation](https://docs.n8n.io/)
- [n8n Community Forum](https://community.n8n.io/)
- [Webhook Testing Tools](https://requestcatcher.com/)

**Advanced Topics:**
- [LangChain Documentation](https://js.langchain.com/)
- [OpenRouter API](https://openrouter.ai/)
- [Google APIs Explorer](https://developers.google.com/apis-explorer)

## 📊 Stats

- **Total Workflows:** 4
- **Total Nodes Used:** 35+
- **APIs Integrated:** 6 (Google Sheets, Gmail, Calendar, OpenRouter, Webhooks, HTTP)
- **Lines of Code:** 100+ (JavaScript)
- **Automations Running:** 4

## 🏆 Achievements

- ✅ Built first webhook receiver
- ✅ Implemented conditional workflow routing
- ✅ Mastered Google API OAuth
- ✅ Created custom JavaScript transformations
- ✅ Deployed AI agent with LangChain
- ✅ Integrated multiple services in single workflow

## 📄 License

This project is open source and available for learning purposes. Feel free to use these workflows as templates for your own automation projects.

---

⭐ **If you find these workflows helpful, please consider starring this repository!**