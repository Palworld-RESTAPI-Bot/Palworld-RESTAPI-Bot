# Palworld-RESTAPI-Bot
A Discord bot manage palworld servers via the official Palworld REST API. It lets server admins manage their Palworld servers entirely from Discord.
**The easiest and most beautiful way to control your Palworld servers right from Discord.**

[![Python](https://img.shields.io/badge/Python-3.14+-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/downloads/)
[![discord.py](https://img.shields.io/badge/discord.py-2.7.1-blue.svg?style=for-the-badge&logo=discord&logoColor=white)](https://github.com/Rapptz/discord.py)

[Features](#-features) • [Setup Guide](#%EF%B8%8F-how-to-install) • [Commands](#%E2%8C%A8%EF%B8%8F-commands) • [Languages](#-languages)

---
## ✨ Features

We've built everything you need to manage your community effortlessly.

| 💻 **Add Multiple Servers** | 📊 **Live Dashboard** |
| :--- | :--- |
| Connect as many Palworld servers as you want to a single Discord server. | Get a beautiful message in your chat that updates live with server status and players. |

| 🎤 **Player Counters** | 🛡️ **Kick & Ban from Discord** |
| :--- | :--- |
| See how many people are playing right in your voice channel names. | Keep bad players out forever. Bans are saved in the bot, so they stay banned even if the game restarts. |

| 📢 **Send Messages** | 💾 **Player History** |
| :--- | :--- |
| Send global announcements directly into the game chat from Discord. | Keep a detailed log of who joins, who leaves, and when. |

<br>

## ⌨️ Commands

We use Discord Slash Commands (`/`) so you never have to remember how to type them! Click below to see all the commands.

<details>
<summary><b>🛠️ Connect & Manage Servers (Admins)</b></summary>

| Command | What it does |
|---|---|
| `/server add` | Add a new Palworld server to your Discord. |
| `/server edit` | Change the details of a connected server. |
| `/server remove` | Disconnect a server. |

<br>
</details>

<details>
<summary><b>👀 Check Status (For Everyone)</b></summary>

| Command | What it does |
|---|---|
| `/serverinfo <server>` | See if the server is online and its version. |
| `/servermetrics <server>`| Check server performance (FPS, memory). |
| `/players <server>` | See exactly who is playing right now. |

<br>
</details>

<details>
<summary><b>🎮 Control the Game (Admins)</b></summary>

| Command | What it does |
|---|---|
| `/announce <server> <msg>`| Send a message to everyone in the game. |
| `/kick <server> <user>` | Kick a player out. |
| `/ban <server> <user>` | Ban a player forever. |
| `/unban <server> <user>` | Remove a ban. |
| `/save <server>` | Save the game world right now. |
| `/shutdown <server>` | Turn off the server safely. |
| `/stop <server>` | Force the server to stop immediately. |

<br>
</details>

<details>
<summary><b>📺 Live Tracking (Admins)</b></summary>

| Command | What it does |
|---|---|
| `/dashboard set` | Create a live message that updates with server info. |
| `/dashboard remove` | Delete the live message. |
| `/voicecounter set` | Create voice channels that count players. |
| `/voicecounter remove` | Delete the counting voice channels. |
| `/playerlogs set` | Choose a channel to log every join and leave. |
| `/playerlogs history` | View the full history of a player. |

<br>
</details>

<details>
<summary><b>🤖 General Help</b></summary>

| Command | What it does |
|---|---|
| `/ping` | Check if the bot is fast and responsive. |
| `/info` | Read basic information about the bot. |
| `/about` | Learn about everything the bot can do. |
| `/setup` | Get a quick guide on how to configure everything. |

<br>
</details>

<br>

---
<i>Made with ❤️ by AyanoKouji</i>
