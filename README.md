🤖 PingBot — AI-Powered Telegram Assistant

Smart replies. Zero cost. Fully automated. Built with n8n + OpenRouter
Start chat → Send a message like:

🧪 Test Your Bot
(Go to Telegram → Start chatting with your bot):👉 [@MyN8NammaBot]

🚀 What Is PingBot?
PingBot is your personal AI assistant on Telegram — powered by Llama 3.3 70B via OpenRouter and orchestrated using n8n, the visual automation platform.

It listens to Telegram messages and replies instantly with intelligent answers. No OpenAI, no credit card, no limits.

✅ Free to deploy ✅ No-code setup (via n8n) ✅ Open-source & backed up on GitHub ✅ Runs 24/7 with smart memory and reply shortening

🧠 Features
🔁 Auto-replies to Telegram messages using Llama 3.3 70B

🧠 Simple memory — remembers your last message

✂️ Smart truncation — avoids Telegram reply errors

🔐 No OpenAI dependency — uses OpenRouter (free API)

🛠️ Built entirely with n8n tools — no coding required

💾 Fully backed up — import & deploy in minutes

🧰 n8n Tools Used
This bot is powered by the following n8n nodes:

Node Type	Purpose
Telegram Trigger	Listens for incoming messages from your Telegram bot
Telegram Send Message	Sends replies back to the user
OpenRouter Chat Model	Connects to Llama 3.3 70B via OpenRouter API for smart responses
Function Node	Handles memory logic and reply shortening
Set Node	Formats messages and prepares payloads
Webhook Registration	Automatically registers Telegram webhook for cloud hosting
✅ All nodes are visually connected in n8n — no manual coding required!

🛠️ Setup Guide (Step-by-Step)


1️⃣ Create Your Telegram Bot
Open Telegram → Search @BotFather

Start chat → Type /newbot

Follow instructions → Name your bot

Copy the Bot Token (e.g., 123456789:ABCdefGhIJklMNopQRstUVwxYZ) ✅ Save this for later

2️⃣ Get Your Free OpenRouter API Key
Go to OpenRouter.ai

Sign up → No credit card needed

Go to Settings → API Keys → Create new key

Copy your API Key ✅ This unlocks Llama 3.3, Qwen, Gemma, and more

3️⃣ Import Workflow into n8n
Open your n8n instance:

Local: http://localhost:5678

Cloud: https://your-n8n-subdomain.n8n.cloud

Railway/Render: your hosted URL

Go to Workflows → Import from File

Upload telegram-bot-workflow.json ✅ Bot logic is now imported!

4️⃣ Add Credentials
Fix red warnings by adding credentials:

🔹 Telegram Credential

Click any red “Telegram” node → “Add Credential”

Name it → Paste your Bot Token → Save

🔹 OpenRouter Credential

Click red “OpenRouter Chat Model” node → “Add Credential”

Name it → Paste your API Key → Save

✅ All nodes should now be green

5️⃣ Register Webhook (Cloud Hosting Only)
If using Railway, Render, or n8n.cloud:

Click “Telegram Trigger” node

Go to “Parameters” tab

☑️ Enable “Webhook: Register Automatically”

Paste your public n8n URL in “Webhook URL”

Click “Execute Node” ✅ You’ll see: ✔️ Webhook successfully set!

6️⃣ Activate Workflow
Toggle “Active” → ON (top-right corner) ✅ Your bot is now live and listening!

🧪 Test Your Bot
Go to Telegram → Search your bot: @YourBotNameBot



Send a message like:
👉 Explain AI in Tamil
✅ Bot replies instantly:

“AI என்பது மனிதர்களைப் போல சிந்திக்கக்கூடிய கணினி…”

📦 Repo Contents
telegram-bot-workflow.json — Full n8n workflow

README.md — Setup instructions

assets/ — Optional images or banners

💡 Built With
n8n — No-code automation platform

OpenRouter — Free access to top AI models

Telegram Bot API

Llama 3.3 70B

🧑‍💻 Author
Made with ❤️ by Sudharshanmonith For privacy-first, explainable AI bots and internal tools.
