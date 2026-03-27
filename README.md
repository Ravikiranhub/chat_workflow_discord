# Lead Sniper - High Value GitHub Lead Tracker

## 📌 Description
This project is an automated workflow built using n8n that tracks GitHub users who star a repository and identifies high-value leads.

##  Workflow
1. Fetch stargazers from a GitHub repository
2. Retrieve user profile data using GitHub API
3. Filter users based on
4. Generate a sales pitch (AI / fallback logic)
5. Send lead details to Discord using webhook

## 🛠️ Tools Used
- n8n (workflow automation)
- GitHub API
- Discord Webhook
- AI Model (or fallback logic)

## 📸 Output
- Discord message with:
  - Name
  - Company
  - Bio
  - Sales Pitch

## ▶️ How to Run
1. Import workflow JSON into n8n
2. Add GitHub API token in HTTP headers
3. Configure Discord webhook URL
4. Execute workflow

## ✅ Conclusion
This workflow demonstrates API integration, filtering logic, and real-time notification of high-value leads.
