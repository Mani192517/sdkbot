# SDKBot - Security Incident Management Bot

## 📌 Overview
SDKBot is an AI-powered security incident reporting and management bot. It integrates with **Supabase** for storing incident reports and **Gmail SMTP** for sending email notifications to the security team.

## 🚀 Features
✅ **Incident Reporting** - Logs security incidents in Supabase.
✅ **Incident Retrieval** - Fetches incident details from the database.
✅ **Email Alerts** - Sends email notifications to the security team.
✅ **Secure Configuration** - Uses environment variables for security.

---

## 🔧 Setup Instructions
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Mani192517/sdkbot.git
cd sdkbot
```

### **2️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **3️⃣ Configure `config.py`**
Edit `config.py` and replace the placeholder values with your actual **Supabase credentials** and **Gmail SMTP details**:
```python
SUPABASE_URL = "https://vwgxemecrmhzzatskjch.supabase.co"
SUPABASE_KEY = "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImhqYWliemRydWR2dHFjaXpnYXp1Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDA4NzQwNDIsImV4cCI6MjA1NjQ1MDA0Mn0.WYxnwzJaaa1a_NigDEpR0jqlxTBkLIRnIJx6PNsXNGI"
EMAIL_USERNAME = "zayn8010311@gmail.com"
EMAIL_PASSWORD = "ehisbztewfkravww"
EMAIL_TO = ["manikumarpagadala003@gmail.com"]
```
> ⚠ **Use a Gmail App Password instead of your regular password!**

---

## 📌 Usage
### **Run SDKBot**
```sh
python sdkbot.py
```

### **Test Incident Reporting**
SDKBot will automatically insert a test incident and send an email notification.

---

## 🛠 Troubleshooting
❌ **Email Not Sending?**
- Make sure **Less Secure Apps** is **disabled** in your Gmail settings.
- Use a **Gmail App Password** instead of your normal password.

❌ **Supabase Not Connecting?**
- Double-check **SUPABASE_URL** and **SUPABASE_KEY** in `config.py`.
- Ensure your Supabase database is properly set up.

---

## 📌 Future Improvements
🔹 Add AI-based incident categorization.  
🔹 Integrate a chatbot interface.  
🔹 Implement voice-activated reporting.

---

## 📞 Contact
For support, contact **Mani Kumar Pagadala** at **manikumarpagadala003@gmail.com**
