# n8n-intro
n8n Learning ep 1
Goal: Understand what n8n is and its basic concepts.

🌟 What is n8n?</br>
n8n (pronounced "n-eight-n") is a powerful workflow automation platform that enables you to integrate APIs, services, and databases using a no-code/low-code interface.</br>
It's like having your own customizable automation engine for cloud, CI/CD, alerts, infrastructure monitoring, and more!</br>

🛠 Why I'm Learning n8n for DevOps
Here’s how I plan to use n8n in DevOps automation:

🔔 Monitor Infrastructure: Auto-alerts when AWS EC2 status changes or resource limits are crossed.

🐙 GitHub Integration: Auto-create or comment on issues when a build fails.

🧪 CI/CD Hooks: Trigger Slack or Telegram messages when a deployment finishes.

📈 Observability: Collect and forward logs or metrics to tools like Grafana or ELK.

📤 Backups & Reports: Automate daily/weekly cloud storage backups or generate reports.

🧰 Step-by-Step: Install n8n via npm


✅ 1. Install Node.js and npm
Go to the official Node.js website and download the LTS version (recommended for most users).

This will install both node and npm (Node.js package manager).

After installation, verify using:

node -v
npm -v

✅ 2. Install n8n Globally
Run the following command to install n8n globally:

npm install -g n8n

✅ 3. Run n8n
After installation, simply run:
n8n
Default URL: http://localhost:5678

📝 Notes:
Your workflows will be stored locally in your system.

When you restart your machine or stop n8n, you’ll need to rerun n8n to use it again.

If needed, you can run it in the background using:

nohup n8n &



