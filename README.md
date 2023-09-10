<!-- Add your project title and description -->
# Google Search Telegram Bot

A Telegram bot built with Python and the aiogram library to perform Google searches and display the results.

<!-- Add badges, if applicable -->
[![License](https://img.shields.io/github/license/iSabbir/Google-Search-Telegram-Bot)](https://github.com/iSabbir/Google-Search-Telegram-Bot/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.9-blue)](https://www.python.org/downloads/release/python-390/)

<!-- Add a demo GIF or image, if applicable -->
![Demo](demo.gif)

## Features

- Interactive and user-friendly command-based interface.
- Supports both text and image searches.
- Pagination of search results.
- Cooldown mechanism to prevent spamming.
- Integration with the Google Custom Search API.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/iSabbir/Google-Search-Telegram-Bot.git
2. Navigate to the project directory:
   
   ```bash
   cd Google-Search-Telegram-Bot

3. Install the required Python packages:

   ```bash
    pip install -r requirements.txt

Usage
1. Obtain a Telegram Bot token from the BotFather.

2. Set your BOT_TOKEN, GOOGLE_API_KEY, and GOOGLE_CSE_ID as environment variables. You can use a .env file to manage these variables.

3. Run the bot:

  ```bash
   python main.py


To create a stylish and colorful README.md file for your GitHub repository, you can use Markdown syntax along with some custom formatting. Here's an example of how you can structure your README.md file for the Google Search Telegram Bot:

markdown
Copy code

<!-- Add your project title and description -->
# Google Search Telegram Bot

A Telegram bot built with Python and the aiogram library to perform Google searches and display the results.

<!-- Add badges, if applicable -->
[![License](https://img.shields.io/github/license/iSabbir/Google-Search-Telegram-Bot)](https://github.com/iSabbir/Google-Search-Telegram-Bot/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.9-blue)](https://www.python.org/downloads/release/python-390/)

<!-- Add a demo GIF or image, if applicable -->
![Demo](demo.gif)

## Features

- Interactive and user-friendly command-based interface.
- Supports both text and image searches.
- Pagination of search results.
- Cooldown mechanism to prevent spamming.
- Integration with the Google Custom Search API.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/iSabbir/Google-Search-Telegram-Bot.git
Navigate to the project directory:

bash
Copy code

cd Google-Search-Telegram-Bot
Install the required Python packages:

bash
Copy code

pip install -r requirements.txt
Usage
Obtain a Telegram Bot token from the BotFather.

Set your BOT_TOKEN, GOOGLE_API_KEY, and GOOGLE_CSE_ID as environment variables. You can use a .env file to manage these variables.

Run the bot:

bash
Copy code

python your_script_name.py
Replace your_script_name.py with the name of the Python script file that contains your bot code.

Configuration
You can configure the bot by modifying the following variables in your_script_name.py:

'RESULTS_PER_PAGE': The number of search results to display per page.
'user_cooldowns': A dictionary to manage user cooldowns.
'admin_ids': A list of admin IDs who have access to certain commands.
'GOOGLE_API_KEY': Your Google API key.
'GOOGLE_CSE_ID': Your Google Custom Search Engine ID.


License
This project is licensed under the MIT License.
