# wpflood
Simple Python script to post automatic comments on Wordpress powered websites

# To use it run:
1. pkg update && pkg upgrade
2. pkg install python
3. git clone https://github.com/AwesomeB0ts/wpflood/
4. cd wpflood
5. pip install requests argparse
6. python bot.py "YOUR TEXT"

# You can edit following:
post_ids = list(range(1, 2)) to post comments under following list of posts (from to)

author_name': 'Bot' to post comments from custom name

'author_email': 'bot@bot.com', to post comments from custom email

time.sleep(9) to post comments with custom delay
