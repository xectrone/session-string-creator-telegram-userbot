# Session String Creator Userbot

![Python](https://img.shields.io/badge/python-3.7%2B-blue)
![Pyrogram](https://img.shields.io/badge/pyrogram-2.0.25-blue)

**Session String Creator Userbot** is a Python-based tool designed to securely generate and export session strings for Telegram user accounts. This tool simplifies the process of creating session strings, essential for running bots or automating tasks using the Telegram API.

## Key Features

- **Secure Session Generation**: Seamlessly generate session strings for user accounts without requiring persistent storage.
- **Easy Configuration**: Utilizes environment variables for quick setup and secure configuration.
- **Interactive Input**: Prompts users for necessary inputs like API credentials and phone number during execution.
- **Error Handling**: Provides robust error management to handle authentication and connection issues gracefully.

## Table of Contents

- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Clone the Repository](#1-clone-the-repository)
  - [Install Dependencies](#2-install-dependencies)
  - [Configuration](#3-configuration)
  - [Running the Userbot](#4-running-the-userbot)
- [Usage](#usage)
  - [Generating a Session String](#generating-a-session-string)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- **Python 3.7+**: Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/).
- **Telegram API Credentials**: Obtain API credentials (API ID, API HASH, and phone number) from [Telegram's website](https://my.telegram.org/auth).

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/xectrone/session-string-creator-telegram-userbot.git
cd session-string-creator-telegram-userbot
```

### 2. Install Dependencies

Install the required Python dependencies using pip:

```bash
pip install -r requirements.txt
```

### 3. Configuration

Create a `.env` file in the root directory and add the following environment variables:

```plaintext
API_ID=your_api_id
API_HASH=your_api_hash
PHONE_NUMBER=your_phone_number
```

### 4. Running the Userbot

Start the userbot by running:

```bash
python main.py
```

## Usage

### Generating a Session String

1. **Run the Script**: Execute the script using the command `python main.py`.
2. **Input Credentials**: If not already set in the `.env` file, you will be prompted to enter your API ID, API Hash, and phone number.
3. **Verification**: A code will be sent to your Telegram account. Enter this code when prompted.
4. **Receive Session String**: Once authenticated, the script will generate and display the session string. Copy this string for use in your bot or application.

## Contributing

Contributions are welcome! If you have suggestions or want to contribute improvements, please fork the repository and submit a pull request. Feel free to open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.