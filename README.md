# Instagram Follower Bot

This is an Instagram bot that automatically follows followers of a specified account. The bot uses Selenium to automate the process of logging into Instagram, navigating to a target account's followers, and following them.

## Features

- Automatically logs into Instagram
- Navigates to the followers of a specified account
- Follows the followers of that account

## Prerequisites

- [Python 3.7+](https://www.python.org/downloads/)
- [Chrome WebDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
- [Selenium](https://pypi.org/project/selenium/)

## Setup

1. Clone this repository:

    ```sh
    git clone https://github.com/Prathamesh326/instagram-follower-bot.git
    cd instagram-follower-bot
    ```

2. Install the required packages:

    ```sh
    pip install selenium
    ```

3. Download Chrome WebDriver and add it to your system's PATH. You can download it from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).

4. Update the `SIMILAR_ACCOUNT`, `USERNAME`, and `PASSWORD` variables in the `bot.py` file with your Instagram username, password, and the target account whose followers you want to follow.

## Usage

1. Run the bot:

    ```sh
    python main.py
    ```

2. The bot will open a Chrome browser window, log into your Instagram account, navigate to the followers of the specified account, and start following them.

## Important Notes

- Use this bot responsibly. Excessive use may lead to your Instagram account being temporarily or permanently banned.
- The XPaths and CSS Selectors used in this bot may change over time as Instagram updates its website. You may need to update these selectors in the code to keep the bot working.
