# twitterbot

These codes are meant to be copy-pasted then adapted for your likening. Create a Twitter bot account, then enable it to become a developing account. You will need to fill out a short application in order to recieve APIs for read and write permissions.

The TwitterGoogleScriptrequires a Google API, which may be found on their developer portal. You must download the JSON for the API that will have the API name/tokens in its title. You must also create a Google Sheet, with three columns (and preferably no unnecessary rows). The first column is the tweet text, the second is the reply tweet ID, and the third is the image link.

The TwitterDiscordScript requires a Discord app to be made, from which you create a bot account and receive its subsequent APIs. The log of who tweets what currently is created to be sent via the shell. 

Install the modules listed at the top of each scipt using the terminal (you'll see the names of these modules following "import").

Due to Tweepy (the required Twitter python module) forbidding duplicate tweets, all tweet texts are automatically stored in a file entitled "tweeters.txt". Reply texts are in "reply_text.txt" and image links are in "image_links.txt". For each row of the spreadsheet, or for each command, the script will inspect these files to determine if there are duplicate statuses. If so, the row will be skipped. 
