# WhatsApp Spam Bot

## Overview

This is a **WhatsApp Spam Bot** tool built using the [Baileys](https://github.com/adiwajshing/Baileys) library. The bot allows you to request pairing codes for a specified phone number and sends these codes at an interval of 3000 ms per code. This bot is created for **educational purposes** and should be used responsibly.

⚠️ **Disclaimer:** This tool is for educational purposes only. Misuse of this tool to spam, attack, or harm any WhatsApp users is illegal and violates WhatsApp's terms of service. Use responsibly.

---

## Features

- Request WhatsApp pairing codes for a specific phone number.
- Send multiple pairing codes at an interval of 3000 ms (3 seconds).
- Console-based user interface for easy interaction.
- Color-coded console output for enhanced readability.
- Defaults to generating 20 pairing codes (can be customized).

---

## Prerequisites

Before using this tool, ensure you have the following:

- **Node.js** installed (v14 or higher is recommended)
- Basic understanding of Node.js and JavaScript
- Familiarity with using the command line/terminal

---

## Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/whatsapp-spam-bot.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd whatsapp-spam-bot
    ```

3. **Install required dependencies**:

    ```bash
    npm install
    ```

4. **Create a session folder for authentication**:

    ```bash
    mkdir -p ./69/session
    ```

5. **Run the bot**:

    ```bash
    node index.js
    ```

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
