<style>
  .votebutton.btn.btn-orange {
  	background-color: #46d46d !important;
  }

  #upvotebutton {
  	background-color: #FFFFFF !important;
  }

  #bot-details-page > article > div.container.is-widescreen > div:nth-child(5) > div {
    color: black !important;
  }

  body:not(.columns) {
    background-image: url('data:image/png;base64,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') !important;
  }

  .columns {
  	background-color: rgba(237, 247, 239, .85) !important;
    border: .5px solid 3c3c3c;
    border-radius: 5px;
    color: black !important;
  }

  .content {
  	background-color: rgba(237, 247, 239, .85) !important;
    border: .5px solid 3c3c3c;
    border-radius: 5px;
    color: black !important;
    padding: 20px !important;
  }

  .shapes-background {
  	display: none !important;
  }

  #createdby {
  	color: #46d46d !important;
  }

  .container {
  	border-top: none !important;
  }

  h1 {
  	text-align: center !important;
    color: black !important;
  }

  #upvotebutton {
  	background-color: rgba(237, 247, 239, .75) !important;
  }

  .bot-description {
  	font-weight: bold !important;
  }

  #bot-details-page .bot-img {
    border-radius: 50%;
    box-shadow: 0 7px 11px 0 rgba(0, 0, 0, 0.65), 0 10px 15px 0 rgba(0, 0, 0, 0.35), 0 12px 20px 0 rgba(0, 0, 0, 0.23);
  }

  .comment {
  	color: black !important;
  }

  .comment-username {
  	color: black !important;
  }

  .bot-description {
  	color: black !important;
  }

  code {
  	color: #7289DA !important;
    background-color: white !important;
  }

  .content h2:not(.override) {
    color: black !important;
  }

  .content h3:not(:first-child) {
  	color: black !important;
  }

  #bot-details-page .bot-name {
  	color: black !important;
  }

  .btn-like span {
  	color: black !important;
  }

  .text-secondary {
  	color: black !important;
  }

  .bot-tags-title {
  	color: black !important;
  }
</style>

# **Villager Bot**
# [![Bot Status](https://top.gg/api/widget/status/639498607632056321.svg?noavatar=true)](https://top.gg/bot/639498607632056321) [![Server Count](https://top.gg/api/widget/servers/639498607632056321.svg?noavatar=true)](https://top.gg/bot/639498607632056321) [![Support Server](https://img.shields.io/discord/641117791272960031?color=51B780&label=Discord%20Server)](https://discord.gg/39DwwUV)

## Notable Features
* Ability to generate Minecraft pixel art from images sent in the chat
* Ability to ping / check the status of any Minecraft server
* Expansive economy system (based upon emeralds obviously!)
* Multi-language support and other customization options
* Made by Iapetus11, so it must be good right?!

## Support / Contact Information
* [Discord Support Server](https://discord.gg/39DwwUV)
* Discord Username: `Iapetus11#6821`


## Commands
### Economy
* `/profile [optional: user]` *shows the profile of you or the specified user*
* `/balance [optional: user]` *shows the balance of you or the specified user*
* `/inventory [optional: user]` *shows the inventory of you or the specified user*
* `/deposit <emerald blocks>` *deposit emeralds into the vault*
* `/withdraw <emerald blocks>` *withdraw emeralds from the vault*
* `/give <user> <amount> <item>` *give another user an item or emeralds*
* `/mine` *mine for emeralds*
* `/search` *beg for emeralds*
* `/honey` *harvest honey from the bees you own*
* `/gamble <emeralds>` *gamble with the bot for a chance of winning emeralds*
* `/pillage <user>` *pillage emeralds from another user*
* `/chug <potion>` *use the specified potion*
* `/shop` *shows the Villager Shop*
* `/buy [optional: amount of item] <item>` *buy an item from the Villager Shop*
* `/sell <amount> <item>` *sell items back to Villager Bot*
* `/leaderboards` *shows the leaderboards*

### Minecraft
* `/mcstatus [optional: server]` *checks the status of any type of Minecraft server*
* `/randommc` *shows a random Minecraft server if you want a new place to explore*
* `/mcimage` *turns whatever image you upload into Minecraft blocks / pixel art*
* `/stealskin <username>` *fetches the skin of a Minecraft Java Edition player*
* `/achievement <text>` *generates a Minecraft achievement from the given text*
* `/buildidea` *sends a random build idea for if you're bored and need inspiration*
* `/mccolors` *shows the Minecraft colors and how to use them in the ingame chat*
* `/nametouuid <username>` *turns a MC Java Edition username into a uuid*
* `/uuidtoname <uuid>` *turns a MC Java Edition uuid into a username*
* `/nametoxuid <username>` *turns an MC Bedrock Edition gamertag into an xuid*

### Utility
* `/help` *view helpful information about Villager Bot*
* `/config` *configure / setup the bot to your liking*
* `/ping` *shows the latency between Discord and Villager Bot*
* `/server` *view information about the current server*
* `/links` *view useful links relating to Villager Bot*
* `/vote` *earn emeralds from voting for Villager Bot on certain websites*
* `/info` *view information about Villager Bot*
* `/stats` *shows statistics about Villager Bot*
* `/uptime` *view how long the bot has been online*
* `/google <search>` *searches on google for your query*
* `/youtube <search>` *searches on youtube for your query*
* `/image <search>` *searches google images for your query*
* `/aliases <command>` *shows the aliases of that command*

### Fun
* `/cursed` *sends a random cursed Minecraft image*
* `/meme` *sends a random meme from reddit*
* `/4chan` *shows a funny screenshot from 4chan*
* `/comic` *sends a random comic from r/comics on reddit*
* `/say <text>` *makes the bot say the text you put in*
* `/enchant <text>` *turns text into the Minecraft enchantment table language*
* `/unenchant <text>` *turns the enchantment table language back into text*
* `/villagerspeak <text>` *turns text into villager sounds*
* `/clap <text>` *:clap: puts :clap: the :clap: emoji :clap: between :clap: text*
* `/emojify <text>` *turns text into emojis*
* `/sarcastic <text>` *turn text into the spongebob sarcastic text*
* `/owo <text>` *owofies the given text uwu*
* `/vaporwave <text>` *makes text into the vaporwave style*
* `/kill <user>` *brutally murder another user*
* `/bubblewrap` *sends virtual bubblewrap for you to pop*
* `/coinflip` *flips a coin and says the result in the chat*
* `/pat <thing>` *pats the mentioned user or thing*

### Moderation
* `/warn <user> <reason>` *warn a user for a specified reason*
* `/warns <user>` *view the warns a user has, leave blank to see your warnings*
* `/purge [optional: user] <amount>` *purge messages from the current channel*
* `/delwarns <user>` *clears the warns that user has in this server*
* `/kick <user>` *kicks the user from the current Discord server*
* `/ban <user>` *bans the user from the current Discord server*
* `/pardon <user>` *unban the user from the current Discord server*
