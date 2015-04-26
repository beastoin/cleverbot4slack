# Basic Tutorial!

## Require
nodejs, Slack Bot

## For installing
Create Slack Bot -> Add Bot's Token -> Run node

1. Create Slack Bot  
You can use this tutorial to create your bot by the simple way.
ref: https://api.slack.com/bot-users

2. Add Bot's Token  
Go to your bot configured page and get the token(Api Token).  
Open `package.json` file and fill your bot's token to `"bot_token"` value:  
`
"config":
  {
    "slack":
    {      
      "bot_token":"xxx"      
    }
  }
`

3. Run node  
Run `node server.js` and enjoy it.  
You can also deploy your source to any server that support nodejs.  
example :https://openshift.redhat.com

## For using
Direct message: just like another member in your team.  
Channel: tag your bot to each message that you want to replied by cleverbot. 
