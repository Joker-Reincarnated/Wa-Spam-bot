# WhatsApp Spam Bot

## Overview
---
A simple WhatsApp spam bot built with [Baileys](https://github.com/adiwajshing/Baileys), designed to generate multiple OTP/Pairing Codes (currently set to pairing code but can be adapted for OTP) for a target phone number.

 **Disclaimer:**
⚠️This tool is for educational purposes only. Misuse of this tool to spam, attack, or harm any WhatsApp users is illegal and violates WhatsApp's terms of service. Use responsibly.

---


## Features

- Generate multiple pairing codes for a target phone number.
- Random color-coded console outputs.
- Customizable number of pairing codes.
- Delayed execution (3 seconds interval per code).
- Works in **Termux and pannel**.

## Prerequisites

- **Node.js** (v16 or higher)
- **npm**
- **Termux** (for running on Android)

---
## Pannel Deployment
Download the repo as .zip file and deploy on [Bot Hosting free pannel](https://control.bot-hosting.net/server/)

## Termux Setup (not working yet)

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

---

## Usage

After starting the bot, you will be prompted for input in the terminal.

1. **Step 1:** Enter the target phone number (e.g., `2340000000000`).
2. **Step 2:** Enter the number of pairing codes to generate (default is 20 if left blank).
3. The bot will generate and display pairing codes, sending them at intervals of 3000 ms (3 seconds).

### Example Console Output:

```bash
*** WELCOME TO THE SPAM BOT ***
Step 1: Please enter the target phone number eg 2340000000000:
Target Phone Number: 2340000000000

Step 2: Enter the number of pairing codes you want to generate:
Number of Pairing Codes (default 20): 10

Code 1 of 10 for 2340000000000: XXXX-XXXX-XXXX
...

## Disclaimer
This tool is intended for educational purposes only. Misuse of this software to send unsolicited spam or for malicious purposes is strictly prohibited and illegal.

## License 
This `README.md` ensures compatibility with **Termux** and provides clear instructions on how to set up and run the bot.
