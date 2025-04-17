# 🤖 smart-hr-multi-agent-recruitment

**SmartHR** is a multi-agent AI system that automates CV analysis and candidate evaluation. It extracts personal data, qualifications, and summaries, then scores candidates based on job criteria. Built using [n8n](https://n8n.io), SmartHR streamlines hiring workflows and integrates easily with Google Sheets and HR tools.

---

## 📄 Project Description

**SmartHR: Multi-Agent AI-Powered CV Analysis & Candidate Evaluation Pipeline**

SmartHR is an automated recruitment pipeline powered by a modular, multi-agent AI system designed to analyze CVs, extract structured data, and evaluate candidates against job profiles. Each AI agent handles a dedicated task—from parsing to scoring—creating a seamless, scalable hiring workflow.

---

## 🔍 Key Features

- ⚙️ **Multi-AI Agent Architecture**  
  Specialized agents for personal data extraction, qualification parsing, summarization, and evaluation.

- 📄 **Automated CV Parsing**  
  Extracts structured information from uploaded resumes.

- 📊 **Profile Matching & Scoring**  
  AI HR Expert evaluates candidates based on predefined job criteria.

- 🧠 **Human-readable Summaries**  
  Auto-generated candidate summaries for quick assessment.

- 📥 **Structured Output**  
  Data is parsed into a clean format ready for export or integration.

- 🔗 **n8n Integration**  
  Open-source automation platform handles the entire process—from file intake to final output.

---

## 🧠 Agents

| Agent Name                  | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **Personal Data Agent**     | Extracts name, contact info, and other personal details from CVs.            |
| **Qualifications Agent**    | Identifies and interprets academic degrees, certifications, and skills.      |
| **Summarization Agent**     | Condenses the CV into a brief, structured summary for quicker review.        |
| **HR Expert Agent**         | Evaluates candidates against job criteria and provides scoring/feedback.     |
| **Structured Output Parser**| Formats AI output into a structured, machine-readable form.                  |
| **OpenAI Backend Model**    | Supports core NLP tasks across multiple agents.                              |

---

## 📌 Use Cases

- HR teams aiming to automate and scale resume screening.
- Startups and enterprises building intelligent hiring pipelines.
- Developers creating custom AI-driven HR applications.

---

## 📤 Output & Documentation

- 📊 **Output File**: [Google Sheet](https://docs.google.com/spreadsheets/d/1k4mcb_2oYaKucNYsVVDW7EJc-5AQhvq-Y2q6nxMvFpQ/edit?usp=sharing)  
- 📚 **Project Docs**: [SmartHR Docs](https://docs.google.com/document/d/18mpAJp2NqQXKPvB311t5RGJSh8QoVGdub9k2u4Jt1Oc/edit?usp=sharing)

---

## 📦 Tech Stack

- **n8n** – Workflow automation
- **OpenAI GPT Models** – NLP tasks (extraction, summarization, scoring)
- **Google Sheets** – Output integration
- **Custom Prompts & Chains** – For agent-specific functionality

---

## 🛠️ Setup (Coming Soon)

Instructions on setting up the n8n workflow and required environment variables will be added in the next update.

---

## 🚀 Contributing

Interested in improving SmartHR or adapting it for your company’s hiring process? Contributions, suggestions, and forks are welcome!

---

## 📬 Contact

For questions or collaboration opportunities, open an issue or reach out via the documentation link.

