# 🤖 Chakravyuh Bot

This is an advanced, multi-functional Discord bot built with Python (discord.py). The main objective of this project is to implement secure server management, interactive user interfaces using modern Discord UI components (buttons and views), event-driven automation, and real-time state management.

---

 ## About the Bot:

Chakravyuh Bot is a feature-rich community management and moderation tool running via the Discord API. It automates server welcoming workflows, handles raw message reactions to assign roles, manages structured client project tickets through ephemeral channel routing, and drives interactive server giveaways via integrated UI button views.

---

## Features

- Advanced Role-Gated Moderation: Features strict role-hierarchy checks (The Fool / The Lord) for destructive commands like !ban, !kick, !mute, and !unmute.
- UI-Driven Ticket System: Creates dedicated support/project channels inside a private category (❍──────LOGS───➤) using persistent interactive buttons and automatic channel teardowns (!close).
- Dynamic Giveaway Engine: Implements real-time asynchronous tasks using asyncio to manage background durations, accept entrant sets via UI buttons, and randomly compute winners.
- Robust Reaction Menu Builder: Includes an interactive step-by-step wizard to create custom emoji-to-role assignment menus in target text channels.
- Mention-Based Automation: Uses event listeners to filter message content and automatically intercept mentions with custom contextual triggers and utility help cards.

---

## Tech Stack

- Language: Python 3.x
- Core Library: Discord.py (v2.0+ framework with UI/View components)
- Async Runtime: Asyncio (for background sleep cycles and non-blocking scheduling)

---

## How to Run

# Install the required Discord API wrapper
pip install discord.py

# Run the bot script
python main.py

---  

⚠️ Security Warning: Do not share or publicly expose your bot's token. It is highly recommended to store the token in an environment variable (os.getenv("TOKEN")) rather than hardcoding it directly inside the initialization block.
