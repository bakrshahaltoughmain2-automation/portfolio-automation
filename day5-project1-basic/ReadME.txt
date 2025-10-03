# Project 1 — Lead Capture & Follow-up (Basic)

**Goal:** Build a simple automation to capture leads and send a confirmation email.  
This is the *basic version* of the Lead Capture project before adding AI personalization.

---

## 🔧 Tools Used
- **Google Forms** → Collects lead details (name, email, company, product interest).
- **Zapier** → Automation platform to connect everything.
- **Airtable** → Stores lead submissions.
- **Gmail** → Sends an automated confirmation email.

---

## ⚙️ Workflow
1. A user submits the Google Form.
2. Zapier adds the new entry into Airtable.
3. Zapier sends an email to the lead using Gmail (static template).

---

## 🧪 Testing
- I submitted **5 dummy entries** into the form.
- Each entry successfully:
  - Appeared in the Airtable database.
  - Triggered a Gmail confirmation email.

---

## 📸 Screenshots
- Zapier dashboard setup:  
  ![Zapier Dashboard](./FAE-sc-1.png)

- Example of email received:  
  ![Email Screenshot](./FAE-sc-2.png)

---

## ✅ Results
- The automation works end-to-end.  
- This demonstrates **basic lead capture and follow-up automation** for small businesses.  
- Future improvements:
  - Add ChatGPT to personalize the email.
  - Log leads in both Airtable & Google Sheets.
  - Send Slack notification when a new lead arrives.
