# n8n LinkedIn Content Creation & Publishing Workflow Automation

🚀 End-to-end automation for creating and publishing LinkedIn content with AI.  
This workflow streamlines the full process: from **researching topics** to **generating posts and visuals**, and finally **publishing automatically**.

## 🔄 Workflow Overview
1. **Research**: Fetches trending AI topics via the Perplexity API.  
2. **Content Generation**: Uses OpenAI GPT-4o to craft LinkedIn posts + matching image prompts.  
3. **Duplication Check**: Reads from Google Sheets to avoid repeating topics.  
4. **Visuals**: Generates unique images with DALL·E 3.  
5. **Publishing**: Posts text + visuals to LinkedIn via the LinkedIn API.  

## 📂 Files in this Repo
- `workflow.json` → Exported n8n workflow file.  
- `screenshots/` → Workflow screenshots.  
- `README.md` → This file.  

## 🛠️ Tech Stack
- **n8n** (workflow automation)  
- **Perplexity API** (AI research)  
- **OpenAI GPT-4o** (text generation)  
- **Google Sheets API** (history check)  
- **OpenAI DALL·E 3** (image generation)  
- **LinkedIn API** (publishing)  

## 📸 Example Workflow
<img width="1405" height="530" alt="Screenshot 2025-08-16 at 10 04 53" src="https://github.com/user-attachments/assets/f60ee87b-152f-4b63-aafc-29054e592a95" />
