# OnProver Referral Bot

A Python automation bot that creates referral accounts on [OnProver]([https://onprover.orochi.network/](https://onprover.orochi.network/?referralCode=7R0g_forestarmy)) using a referral link. This tool is useful for growing your referral network automatically.

⚠️ script is not owned by me it was shared to me from my members
## Features

- Automated account registration  
- Optional headless (no browser window) mode  
- Configurable delays between actions  
- Temporary email support  
- Custom referral code integration  
- Error handling and pause on failure  

## Requirements

- Python 3.6+  
- Google Chrome browser  
- Compatible ChromeDriver (matching your Chrome version)  

## Installation

1. **Clone the Repository**

```bash
git clone https://github.com/itsmesatyavir/onprover.git
cd onprover
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Configure the Bot**

Edit the `config.json` file to match your preferences:

```json
{
    "headless": false,
    "account_count": 3,
    "min_delay": 10,
    "max_delay": 20,
    "password": "YourSecurePassword123!",
    "referral_code": "7R0g_forestarmy",
    "use_temp_email": true,
    "email_prefix": "userTest",
    "email_domain": "gmail.com",
    "pause_on_failure": true
}
```

> **Note**: Make sure your ChromeDriver version matches your installed Chrome browser version.

## Usage

Run the bot using:

```bash
python main.py
```

The bot will start creating accounts based on the configuration in `config.json`.

## Referral Link

Want to help grow the network manually too? Share your referral link:  
[https://onprover.orochi.network/?referralCode=7R0g_forestarmy](https://onprover.orochi.network/?referralCode=7R0g_forestarmy)

## Disclaimer

This project is intended for educational and research purposes only. Use responsibly and in accordance with the OnProver platform’s terms of service.

## License

MIT License
