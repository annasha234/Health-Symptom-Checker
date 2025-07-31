# 🩺 Agentic AI – Health Symptom Checker

## 📌 Overview

**Agentic AI – Health Symptom Checker** is an AI-powered virtual assistant designed to help users understand potential causes behind common symptoms. Built with IBM Watsonx.ai and free-tier IBM Cloud services, it analyzes natural language symptom input and responds with possible conditions, urgency levels, home care advice, and when to consult a doctor.

---

## 🚀 Features

- **Symptom Analysis** – Understands queries like “I have body pain and shortness of breath.”
- **Trusted Sources** – Uses CDC, WHO, and MoHFW-approved symptom datasets (e.g., Epi-CASE Symptom PDF).
- **No Self-Diagnosis** – Offers educational info, not medical decisions.
- **Prompt-Based** – Built using Watsonx Prompt Lab with curated instructions.
- **Free Deployment** – Runs on IBM Cloud Lite with no paid services.

---

## 💡 Usage Options

### 1. Prompt Lab Testing
- Open your agent in **IBM Watsonx.ai Prompt Lab**.
- Enter symptom-based queries in the test interface.
- Get immediate structured feedback (e.g., urgency, suggestions).

### 2. Deployment Preview
- Launch a **deployed instance** of the agent.
- Access the **Preview** mode or Web Chat preview.
- Ask health-related questions (non-diagnostic).

---

## 💬 Example Prompts

- “I have fever and chills.”
- “What could cause dizziness and headache?”
- “I have a sore throat and difficulty breathing.”
- “Suggest home remedies for a runny nose.”

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio  
- IBM Granite Model  
- Watsonx Vector Index  
- IBM Cloud Lite Account  
- IBM Object Storage  
- Prompt Lab  
- Deployment Space  

---

## ⚙️ How It Works

- **Vector Indexing**: Medical PDFs like Epi-CASE are uploaded and vectorized for retrieval.
- **Prompt Engineering**: Carefully crafted prompts interpret symptom context.
- **Model Selection**: Built on `mistral-large` or IBM Granite foundation model.
- **No Training Required**: Uses zero-shot/few-shot prompting.

---

## ✅ Do’s and Don’ts

### ✅ Do:
- Ask about common symptoms or conditions
- Expect educational, structured suggestions
- Use for awareness and early action planning

### 🚫 Don’t:
- Use it for emergency care
- Input personal health records
- Treat as medical diagnosis

---

## 🙏 Acknowledgements

Built as part of an IBM SkillsBuild project on IBM Cloud. Powered by Watsonx AI and Prompt Lab with publicly available medical data.
