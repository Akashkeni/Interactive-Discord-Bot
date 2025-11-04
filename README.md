# 🤖 Interactive Discord Bot

An interactive and customizable Discord bot built using **Python** and **discord.py**.  
It includes features like fun commands, moderation tools, and real-time responses for an engaging Discord experience.

---

## 🚀 Features

- 🗣️ Responds to user messages with smart and fun replies  
- 🎮 Interactive commands (games, quotes, jokes, etc.)  
- 🛠️ Basic moderation tools (kick, ban, mute)  
- 📊 Logging system for tracking bot activity  
- ⚙️ Easy to extend and customize new commands  

---

## 🧠 Tech Stack

- **Language:** Python 3.x  
- **Libraries:** `discord.py`, `asyncio`, `dotenv`  
- **Environment Management:** [uv](https://docs.astral.sh/uv/)  

---

## ⚙️ Setup Instructions (Local Development)

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/Akashkeni/Interactive-Discord-Bot.git
cd Interactive-Discord-Bot
```
### 2. Create & Activate Virtual Environment (with uv)
```bash
uv init
uv venv
uv sync
```
### 3. Add Environment Variables
```
DISCORD_TOKEN=your_discord_bot_token_here
```
### 4. Run the Bot
```
uv run python main.py
```

