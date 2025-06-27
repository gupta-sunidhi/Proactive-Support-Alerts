# Proactive Support Alerts

This project is a browser-based tool to detect and alert on clusters of similar support tickets using AI (TensorFlow.js and Universal Sentence Encoder). It helps proactively notify support teams when multiple similar issues occur in a short time window.

## 🌟 Features

- 🧠 Uses AI to detect similar tickets
- 📬 Sends email alerts when a cluster exceeds threshold
- ⏱️ Time window and check interval configurable
- 📂 JSON file input for support ticket data
- 💌 EmailJS integration for alerting

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/gupta-sunidhi/Proactive-Support-Alerts.git
cd proactive-support-alerts
```

2. Open public/index.html directly in a web browser.

3. Configure:
       Time window (hours)
       Cluster alert threshold (number of similar cases)
       Your email address
       Check interval

4. Upload a JSON file of tickets (must contain fields like subject, created_at etc.)

5. Receive proactive alerts when clusters form!

# Setting up EmailJS
1. Sign up for EmailJS: https://www.emailjs.com/
2. Create an Email Service and Email Template
3. Replace the following in the HTML:
          "YOUR_PUBLIC_KEY" → your EmailJS Public Key
          "YOUR_SERVICE_ID" → your EmailJS Service ID
          "YOUR_TEMPLATE_ID" → your EmailJS Template ID

  

# PROJECT STRUCTURE

```bash
/public
  └── index.html       ← Main frontend logic
README.md              ← You are here!
.gitignore             ← Ignore system files
LICENSE                ← MIT by default
```




