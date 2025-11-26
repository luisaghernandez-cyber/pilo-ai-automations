# pilo-ai-automations
Automations built with n8n and AI to streamline workflows for content, trading education and productivity. Includes reusable workflows, code examples and documentation.


This repository contains automation workflows built with **n8n**, **JavaScript**, and **AI tools**.  
The goal is to demonstrate how simple but powerful automations can streamline real-world tasks related to content creation, trading education, analytics, and productivity.

All workflows are exported as JSON files, fully documented, and ready to be imported directly into n8n (cloud or self-hosted).

---
flows/
**Workflow 1:** Trading Content Calendar Generator

**Location:** `flows/content-calendar-trading.json`  
**Trigger:** Manual Trigger  
**Built with:** n8n (free version) + JavaScript inside the *Run Code* node  

 
 **What it does**
This workflow generates a **10-day social media content calendar** focused on trading education.  
For each day it outputs:

- `day_number`  
- `date`  
- `content_topic`  
- `content_type` (e.g., “Educational Reel”)  
- `platform` (Instagram / TikTok)  
- `status` (Idea)

It can be extended to send data to Google Sheets, Notion, email, or any other integration supported by n8n.

---
 **Why this workflow matters**

- Demonstrates practical automation logic  
- Uses clean and reusable JavaScript in n8n  
- Shows understanding of workflow design  
- Can be adapted for marketing teams, trading desks, or educational pages  
- Works entirely on the free n8n tier  

---
**How to import the workflow in n8n**

1. Download the JSON file from `/flows/`.
2. Open n8n → **Import from File**.
3. Load the JSON.
4. Run the workflow using **Execute Workflow**.
5. Review results in the *Output* panel of the Run Code node.

---


## License

This repository currently has **no license**, meaning all rights are reserved.  
If you wish to use this code publicly or commercially, please open an issue or contact the repository owner.

