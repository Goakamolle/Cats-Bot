Requirements
Python 3.11 (you can install it here)
Telegram API_ID and API_HASH (you can get them here)
Install the required dependencies:

pip install -r requirements.txt
Get your API_ID and API_HASH:

Go to my.telegram.org
Sign in with your Telegram account
Create a new application to get your API_ID and API_HASH
Configure the application:

Open config.py and add your API_ID and API_HASH:

API_ID = your_api_id
API_HASH = 'your_api_hash'
If you want to use a proxy, set USE_PROXY in config.py to True, otherwise set it to False:

USE_PROXY = True  # or False
if you want a task with pictures to be performed, then you need to create a "photos" folder and upload photos to it

DO_PHOTOS = True
If USE_PROXY is True, open proxy.txt and fill it out using the example provided. Ensure there are no extra lines in the file. Proxy format : ip:port:login:password session_name, session name is which use this proxy (WITHOUT .session, only session name)

192.168.1.1:1234:username:password session1
192.168.1.2:2934:username:password session2
192.168.1.3:3834:username:password session3
192.168.5.1:2884:username:password session4
And don't forget set proxy type in config.py

PROXY_TYPE = "socks5" # or http
IMPORTANT Create a sessions folder

Usage
Run the bot:

python main.py
The software will work with all accounts using the single API_ID and API_HASH. No need to change them for each account.

Important Notes
Python Version: The software runs on Python 3.11. Using a different version may cause errors.
DONT USE MAIN ACCOUNT BECAUSE THERE IS ALWAYS A CHANCE TO GET BANNED IN TELEGRAM
