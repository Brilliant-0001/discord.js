# Thanks for Visiting!

Hi, my name is Nicholas, but you can call me Nick. Welcome to my [Discord.JS](https://discord.js.org) bot example! This is a simple example bot to get you started. Hope you enjoy using it! 

This walk-through is aimed at people who want to code a bot just for their server. 

Before trying to do this, make sure you understand the concept of **JavaScript**. Also, this bot can only be ran via a Windows (or Linux, I haven't tested yet) Computer or Laptop.


# Setup

**There are a few things you need to do before you can actually run a Discord Bot:**
1. Make sure you have the **LTS** version of [Node.JS](https://nodejs.org/en/download) along with the [PATH](#installing-the-node-path) downloaded.
2. [Create Yourself A Bot](#creating-your-discord-bot) at the Developer Portal.
3. Download the ZIP file and save it somewhere accessible.

If you have already done all this, then scroll down [here](#configuring-your-discord-bot).

## Installing the Node PATH

Basically, what I mean by this is that, when in the Node.JS Installer, you must select everything to be downloaded (It is like this by default). Therefore, it is no need to touch anything when installing Node. Just click Next, then Install.

## Creating your Discord Bot

To create a Discord Bot, you need to do the following:

 1. Login with your discord account into the [Discord Developer Portal](https://discordapp.com/developers/applications/).
 2. Create a new Application by clicking the button situated in the top-right corner.
 3. In the left-hand menu, scroll down to bot and 'Build a Bot'.
 4. Invite it to your server by scrolling to the OAuth2 and giving it some permissions.
 5. Copy the token of your Discord Bot.

## Configuring your Bot

Before you can run your Discord Bot, you must set some things up first. Assuming you already done the previous steps, unzip the downloaded file and open it. You are looking for a file named **config.json**. Once opened, it should look like this:
```json
{
    "token": "your-token",
    "prefix": "!"
}
```
Replace `your-token` with your own bot's token you've just copied. You can even change the prefix to something else if you want to!😃

Now you are ready to start **play-testing** it!


## Play-testing your Bot

It is a good idea that, when busy developing a Discord Bot, you should run it in a separate channel or server. This allows you to experiment with your creation and do something wild!
The downloaded folder comes with a batch file called **run.bat**. 
This is completely safe, as all it does is it just runs your bot via executing **node index.js**.

 If you don't trust me, you can just hold **Alt - F** in your File-Explorer and click 'Open Power-Shell Window Here'. Or, just hold shift and right-click and click 'Open Power-Shell Window Here'. In both cases, Power-Shell opens. Then type **`node index.js`** to start the bot.
 You should see a message that it loaded a file from a certain area in your **commands** file, as well as 'Commands Ready' being outputted.
 
 But what does that mean? Does that mean the downloaded file came with a pre-made command? You should test it! In your Discord Server, type your bot's prefix followed by 'profile'. So, if the prefix is **`//`**, you would do `//profile`. It even works when running it on other players! For example, `//profile @User`!

## Improving your bot

Before trying to code with the Discord API, I recommend that you learn JavaScript first. JS is used with **HTML** and **CSS**, two well-known Languages for Web Development. There are many ways of coding with JavaScript, but make sure you know more than just the Basics before attempting to code with a JavaScript Library or Framework. 

If you are good enough in JavaScript (or you just want a free Discord Bot😈), you can start coding some commands in the sub-folders of the commands folder. Make sure that nothing other than JavaScript files are there, otherwise the Bot crashes! 
Always make sure that you have access to the [Discord.JS Documentation](https://discord.js.org/#/docs) if you get stuck, or if you are interested in something.

## Debugging your Bot

Debugging is a term programmers use to convey that an error has been found and that it needs to be fixed. You know you have found an error if your Command Prompt resets itself, or if your Power-Shell suddenly sends some long lines of text. If you do get an error, make sure that you know how to deal with it. 

The reason why I like play-testing is because you get to save your progress and move on, provided there are no errors. The more rarely you play-test, the higher the chance of getting errors. Therefore, I normally play-test for the following:
- whenever I finished a huge part of a command, or the command itself
- whenever I copied example code from the Discord.JS Documentation
- whenever I encountered an error and try to fix it to see if it's gone

Please note that this has been how I coded my Discord Bots ever since I started with Discord.JS. If you tend to differ, go for it! I would love to see my example helping people grow in general in terms of Discord.JS.


## Finalizing your Bot

Congratulations! You have yourself a Discord Bot! Do you have a feeling it's complete? If so, how do you keep it running 24/7? I recommend some websites like Heroku or Glitch, but this is purely personal preference. I also recommend watching YouTube videos about this topic, as it makes no sense to keep your computer 24/7 just to run your Discord Bot.

## Troubleshooting
In the rare case of major, unfixable problems, there are some options for getting help. You can join the official Discord.JS server, or you can join mine [here](https://discord.gg/ccpUQ5p). I do have some social history if you would like to get in touch with me elsewhere. I recommend that you search for a problem on Google, or even a Q&A site, such as [Stack Overflow](https://stackoverflow.com/).


# Social


If you ever need to get in contact with me, there are some ways to do so:

- **My Discord Server**: https://discord.gg/ccpUQ5p
- **My Discord tag**: `Brilliant#0001` (DM me!)
- **Official Disocrd Server**: https://discord.gg/bRCvFy9

I mostly use Discord for any social media, as it is my main form of coding. I also commented every file that came upon installation. Most of the content is ES6-based, which improves the overall speed of the Discord Bot.

Well,  I guess that's all from my side; Enjoy your coding with my Discord Bot Example!
