# MD_TradeBot

MD_TradeBot is a Telegram bot for trading on the Quotex platform. It provides features for both demo and live trading, as well as options for automated trading.

## Features

- Start a trading session
- Check account status
- Toggle auto trading mode
- Set demo trading mode and amount
- Provide trading signals

## Configuration

To configure your account details, use the `/set_config` command followed by your email, password, email account password, and browser profile path. To reset the configuration and start over, use the `/start` command. This will prompt you to set your account details again.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/MD_TradeBot.git
    cd MD_TradeBot
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Configure the settings:
    Create a `settings/config.ini` file with the following content:
    ```ini
    [settings]
    email=your_email
    password=your_password
    email_pass=your_email_password
    user_data_dir=your_browser_profile_path
    ```

4. Run the bot:
    ```bash
    python main.py
    ```

## Usage

Start the bot and use the following commands in Telegram:

- `/start` - Start the bot and reset configuration
- `/set_config <email> <password> <email_pass> <user_data_dir>` - Set or update account configuration
- `/help` - Get help
- `/trade` - Start a trading session
- `/status` - Check account status
- `/toggle_auto_trade` - Toggle auto trading mode
- `/set_demo_trade <amount>` - Set demo trading mode and amount

## License

This project is licensed under the MIT License.