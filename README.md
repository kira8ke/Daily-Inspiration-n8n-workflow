📖 Bible n8n Automation Project

This project contains an n8n workflow that automatically fetches Bible verses and sends them via email. It’s designed to help you (or your users) receive inspirational verses directly in the inbox.

✨ Features

🔄 Automated workflow built in n8n

📜 Fetches Bible verses dynamically

📧 Sends verses through email notification

⚡ Ready-to-import workflow JSON

🚀 Setup Instructions

Clone or download this repository.

Open your n8n instance.

Navigate to Workflows → Import from File.

Upload the file located at:

workflows/BibleWorkflow.json

Configure your Email node with valid SMTP credentials (e.g., Gmail, Outlook, or custom).

Activate the workflow and let it run automatically.

📂 Repository Structure
workflows/
└── BibleWorkflow.json # Exported n8n workflow for Bible automation
README.md # Project documentation

📧 Example Email

Subject: 📖 Today’s Bible Verse
Body:

John 3:16  
For God so loved the world, that he gave his only begotten Son,  
that whosoever believeth in him should not perish, but have everlasting life.

⚠️ Notes

Make sure your email provider allows SMTP / App Passwords (Gmail requires enabling 2FA + App Password).

If using Gmail OAuth2, configure the OAuth Consent Screen and add yourself as a Test User.
