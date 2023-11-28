# Amazon Price Alert

## Description
This Amazon Price Alert script monitors the price of a specific product on Amazon and sends an email notification when the price drops below a set threshold. The script is written in Python and uses libraries like BeautifulSoup for web scraping and smtplib for sending emails. It's an ideal tool for those who want to grab deals as soon as they become available.

## Features
- Web scraping Amazon product pages to get the latest prices.
- Automated email notifications when prices drop.
- Customizable product URL and price threshold.

## Requirements
- Python 3.x
- BeautifulSoup4
- requests
- smtplib

## Setup and Installation
1. Clone the repository to your local machine.
2. Install the required Python libraries:
   ```bash
   pip install beautifulsoup4 requests
Update the script with your email credentials and the Amazon product URL.

## Usage
1. Run the script using Python:
  ```bash
python amazon_price_alert.py
2. The script will periodically check the specified Amazon product page.
3. If the product price falls below your set threshold, you will receive an email alert.

## Customization
- Set your desired Amazon product URL in the URL variable.
- Modify the check_price function to suit your specific needs.
- Update the send_mail function with your email details for notifications.

## Contributing
Feel free to fork this project and contribute by submitting a pull request.

## Disclaimer
This script is intended for educational purposes. Please be aware of Amazon's terms of service regarding web scraping.

## Authors and Acknowledgments
- Franz Rott
- Guided by AlexTheAnalyst
