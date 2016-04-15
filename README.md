# Flask-HelloWorldBot
A Basic Template for A FB Messenger Bot created in Flask

Steps to get up and running:

1) Create a new FB App https://developers.facebook.com/quickstarts/?platform=web

2) Create a new FB Page https://www.facebook.com/pages/create

3) Go to your app and to the messengers tab on the sidebar

4) Generate a token for your page

5) In HelloWorldBot.py replace '\<ACCESS_TOKEN_HERE>' with that token

6) In HelloWorldBot.py replace '\<VERIFY_TOKEN_HERE>' with any string you like

7) Deploy your app, you need a https url, so deploying to Heroku is easiest, should work out of the box

8) Click 'Setup Webhooks' back in the Facebook Developers page (still in the Messenger tab), and the Callback URL should be YOUR_URL + '/webhook'

REMEMBER: It needs to be https

Your Verify Token is the string you chose in step 6

At least check 'messages' in Subscription Fields, others are optional

9) Verify and Save

10) If you did it correctly, your page should respond to every message from YOU to the page with "Hello World" 
Note that this will not work for anyone else until you submit your app for review

Using this as a reference can help: https://developers.facebook.com/docs/messenger-platform/quickstart

No experience with Heroku? Its super easy: https://devcenter.heroku.com/articles/getting-started-with-python#introduction

This seems like another tutorial that goes more in-depth (although in Node.js but should be fairly easy to translate, maybe?) - https://github.com/jw84/messenger-bot-tutorial

I don't have much more experience with bots than this, but I would be happy to try and answer any questions you have! You can contact me at reparadocs (at) gmail (dot) com
