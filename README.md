# WhatsApp Bulk Message Sender

Send WhatsApp text messages from the terminal with Python.

## Features

- Send repeated WhatsApp text messages from the terminal
- Choose the message and number of repetitions
- Set a delay between messages
- Automatically adds a counter to each message, such as `(1)`, `(2)`, and `(3)`
- Uses PyAutoGUI to type messages into the currently focused WhatsApp chat

## Requirements

- Python 3.x
- WhatsApp Web or WhatsApp Desktop, logged in
- PyAutoGUI

## Installation

Clone the repository:

```bash
git clone https://github.com/FalconLynx/WhatsApp-Bulk-Message-Sender.git
cd WhatsApp-Bulk-Message-Sender
```

Install the required package:

```bash
python -m pip install pyautogui
```

## Usage

Run the script:

```bash
python whatsapp.py
```

Then enter the requested details in the terminal:

1. Recipient's phone number
2. Message text
3. Number of messages to send
4. Delay between messages in seconds

## Important: Before Running

The current script does **not** use the phone number to open a WhatsApp chat automatically. Before the 5-second countdown ends:

1. Open WhatsApp Web or WhatsApp Desktop and sign in.
2. Open the intended recipient's chat.
3. Click inside the message input box.
4. Keep the WhatsApp window focused while the script runs.

The script types into whichever window is focused and presses Enter to send each message. If another window is focused, text could go to the wrong place.

## Disclaimer

Use this tool responsibly. Send messages only to intended recipients who have agreed to receive them. Avoid spam and follow WhatsApp's terms of service. Check
