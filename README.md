<h1 align= "center">
 Inspirational Saleh G Twitter Bot
</h1>


<p align="center">
<img src="./public/saleh_tweet.png"  width="600"/>
</p>

<p align="center">
<img src="./public/twitter.png" height="20"/>
Tweet <a href="https://twitter.com/unimaxsystems" target="_blank">@unimaxsystems</a>
for an inspirational quote!
</p>

<p>
This bot was developed out of love and as a method to resume Python programming. Since I've always been interested in automation, I thought this would be a perfect opportunity to learn more about Python automation.
 </p>
 
 <p>The bot is an AWS-hosted Flask application. The bot now tweets a random Saleh G picture from the Shibe API along with an uplifting statement from the Zen Quotes API (a href="https://zenquotes.io/api" target=" blank">Zen Quotes API/a>). The image is then uploaded and posted via the Twitter API.. 
</p>

<p>
<img src="./public/saleh_icon.png" width="20"/>The bot also checks for mentions every 5 minutes and will respond to them with some wisdom!
</p>

<h2 align= "center">
 Creating Your Own Bot <img src="./public/doge.png" width="20">
</h2>


If you wish to use this project as a template for creating your own bot, do the following.

## Prerequisites

* Create a developer account with Twitter
* Request elevated access to be able to use the API v2 (necessary to upload images)
* Save your keys in a .env or somewhere safe.
* Create an account with AWS or your hosting service of choice

## Installation

```bash
# Clone the repo
$ git clone https://github.com/sarahdepalo/twitter-bot.git

# Change into the directory
$ cd twitterbot

# Install dependencies
$ pip install -r requirements.txt

# Swap out your credentials in constants.py
# Publish a post
$ python3 daily_post.py
```

🌸 Happy coding! 🌸

<p align="left">
<img src="./public/mention_tweet.png"  width="500"/>
</p>
