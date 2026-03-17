
# Recruitment Automation Workflow using n8n

## Overview
This project demonstrates an **automated recruitment workflow** built using [n8n](https://n8n.io/).  
It connects a **Google Form** (via Google Sheets) to **Gmail**, automatically sending new candidate submissions to the recruiter with all relevant details.

---

## Features
- Fetch new candidate submissions from Google Forms via Google Sheets trigger.
- Process candidate information (name, email, education, resume link) using a **JavaScript Code Node**.
- Automatically send a **notification email** to the recruiter with candidate details.
- Fully configurable for any Google Sheets and Gmail account.

---

## Workflow Nodes
1. **Google Sheets Trigger**  
   Detects new rows added to the linked Google Sheet.
2. **Code Node (JavaScript)**  
   Extracts candidate details from the row for further processing.
3. **Gmail Node**  
   Sends a professional HTML email with the candidate’s information and resume link.

---
