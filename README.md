💾 Savey — Your Personal Password Manager

A simple, local, and secure password manager with a cute and friendly Gradio UI.

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

⚙️ Installation

💻 Prerequisites
Python 3.8 or above

pip (Python package manager)

📦 Install Dependencies
bash
Copy
Edit
pip install gradio pycryptodome

🚀 Running Savey
1️⃣ Download or clone this repository
bash
Copy
Edit
git clone https://github.com/yourusername/savey.git
cd savey

2️⃣ Run the app
bash
Copy
Edit
python passkeep_app.py
3️⃣ Open in your browser

After running, Gradio will automatically open a local link (usually http://127.0.0.1:7860/).
You’ll see Savey's cute and simple interface to start managing your passwords!

Important ; The Default decryption key is 'password123' you can change it once you get in the web app.

🏗️ File Structure
pgsql
Copy
Edit
passkeep_app.py       # Main app file
passwords.db          # Encrypted local database (auto-created after first run)
💡 Usage Flow
Decrypt Database — Enter your key and unlock your credentials.

Add — Save a new username, password, and platform.

Edit — Update an existing record.

Delete — Remove unwanted records.

Change DB Password — Change the encryption key securely.

Generate Password — Get a strong random password.

Backup — Create a local backup file.

Erase — Wipe all data if needed.

Send Email — Email your credentials securely.

⚠️ Important
Always remember your decryption key! Without it, your data cannot be recovered.

Use strong keys (at least 10 characters) for better security.

All data is stored locally — no data is uploaded anywhere.

💌 Contact & Support
Feel free to reach out if you have questions, ideas, or want to collaborate!

⭐ Contributing
We welcome contributions!
If you'd like to add new features or fix bugs, just fork the repo, make changes, and open a pull request.


❤️ Thank you for using Savey!
