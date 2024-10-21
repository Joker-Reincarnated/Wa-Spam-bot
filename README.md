# WhatsApp Spam Bot - Spambot.js

A simple WhatsApp spam bot built with [Baileys](https://github.com/adiwajshing/Baileys), designed to generate multiple OTP/Pairing Codes (currently set to pairing code but can be adapted for OTP) for a target phone number.

## Features

- Generate multiple pairing codes for a target phone number.
- Random color-coded console outputs.
- Customizable number of pairing codes.
- Delayed execution (3 seconds interval per code).
- Works in **Termux**.

## Prerequisites

- **Node.js** (v16 or higher)
- **npm**
- **Termux** (for running on Android)

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Joker-Reincarnated/Wa-Spam-bot.git
2. **Open cloned repo**:
   ```bash
   cd Wa-Spam-bot
3. **Install dependencies**: Run the following command to install the required packages:
   ```bash
   npm install
4. **Baileys Setup**: If this is your first time running the bot, make sure you authenticate using Baileys:
   ```bash
   node Spambot.js
Your session data will be saved automatically in the **69/session** folder.

## Disclaimer
This tool is intended for educational purposes only. Misuse of this software to send unsolicited spam or for malicious purposes is strictly prohibited and illegal.

## License 
This `README.md` ensures compatibility with **Termux** and provides clear instructions on how to set up and run the bot.
