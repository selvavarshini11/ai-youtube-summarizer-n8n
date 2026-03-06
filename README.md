# 🎥 AI YouTube Video Summarizer (n8n)

An AI-powered YouTube video summarizer built using workflow automation and Large Language Models.

## 🚀 Tech Stack

- ⚡ n8n (Workflow Automation)
- 🤖 Groq API (Llama 3.1 LLM)
- 📜 Supadata API (YouTube Transcript Extraction)
- 📊 Google Sheets (Summary Storage)

---

## 🔄 How It Works

1. User provides a YouTube URL  
2. Supadata API fetches the video transcript  
3. Transcript is sent to Groq LLM  
4. AI generates a structured summary  
5. Summary is automatically stored in Google Sheets  

---

## ⚙️ Setup Instructions

1. Import the provided workflow JSON file into n8n  
2. Replace the placeholders with your credentials:

   - `YOUR_GROQ_API_KEY`
   - `YOUR_SUPADATA_API_KEY`
   - `YOUR_GOOGLE_SHEET_URL`

3. Configure Google Sheets Service Account credentials in n8n  
4. Execute the workflow  

---

## 📌 Features

- Automated transcript extraction  
- AI-generated concise summaries  
- Direct Google Sheets integration  
- No manual summarizing required  

---



---



---

## 👩‍💻 Author

Selvavarshini  
Built as an automation + AI integration project.
