🗝️ SAVEY — Your Personal Password Manager

A simple, local, and secure password manager with a friendly Gradio UI.

🌟 Features
✅ Store and manage all your credentials securely
✅ AES encryption & local storage (no cloud!)
✅ Add, edit, and delete records easily
✅ Generate strong random passwords
✅ Backup and erase your database anytime
✅ Change your database key/password securely
✅ Send credentials to your email in one click

🖼️ Screenshots
💻 Main Dashboard

🔐 Decrypt & View Credentials

➕ Add Credentials

🚀 How to Run
bash
Copy
Edit
pip install gradio pycryptodome
python passkeep_app.py
Your browser will open automatically. Enjoy!

🏗️ File Structure
pgsql
Copy
Edit
passkeep_app.py       # Main app file
passwords.db          # Encrypted local database (auto-created)
⚙️ Usage Flow
Decrypt Database — Enter your key and unlock your credentials.

Add — Save a new username, password, and platform.

Edit — Update an existing record.

Delete — Remove unwanted records.

Change DB Password — Change the encryption key securely.

Generate Password — Get a strong random password.

Backup — Create a safe local backup file.

Erase — Wipe all data if needed.

Send Email — Send specific credentials to your email.

💡 Tech Stack
Python 🐍

Gradio — for a clean and easy-to-use web interface

PyCryptodome — for AES encryption and secure storage

SMTP (Gmail) — for sending credentials via email

⚠️ Important
Always remember your decryption key! Without it, you cannot access your data.

Use strong keys (at least 10 characters).

Your data stays local. No cloud storage = no third-party snooping.

💌 Contact & Support
Feel free to reach out if you face any issues or have ideas to improve!

⭐ Contributing
If you'd like to add new features (like browser autofill, mobile app, etc.), open a PR or suggest in issues.


❤️ Thank you for using Savey!
****
