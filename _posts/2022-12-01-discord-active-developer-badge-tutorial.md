---
layout: post
title:  "Discord Active Developer Badge Tutorial"
author: DovydasTEDS
date:   2022-12-01 20:15:41 +0000
---

In this tutorial, I will be going over how to get the discord active developer badge.

## Making the bot account

Head over to the [discord developer portal](https://discord.com/developers/applications) and sign in to your discord account. Then, make an application and name it whatever.  
![Image1](/assets/img/posts/discord-active-developer-badge/image1.png)

Once you have done that, open the newly created application and click on bot. You will then need to click add bot. Once made, click on reset token and copy your token.  
![Image2](/assets/img/posts/discord-active-developer-badge/image2.png)

## Setting up the replit

After doing this, you will need to go to [Replit](https://replit.com). You will need to sign up or login and then press create. Upon doing that, you will need to click 'Import from GitHub'   
![Image3](/assets/img/posts/discord-active-developer-badge/image3.png)  
Copy this url: 

```https://github.com/hackermondev/discord-active-developer-badge```  
Then click 'Import from GitHub'
When loaded, at the top click the run button and wait for it to load. When it asks for the application token in the big black box, paste in your bot token and hit enter. (**Note**: ``CTRL + V`` won't work so you either have to right click and hit paste or type ``CTRL + SHIFT + V``)  
![Image4](/assets/img/posts/discord-active-developer-badge/image4.png)

Once complete, go back to the application page, go to the 'General Information' tab, scroll down and copy the application id. It will look like numbers, however, I changed it to APPLICATION-ID.  
![Image5](/assets/img/posts/discord-active-developer-badge/image5.png)  

## Using the bot

Use this invite link to add the application to the server: (replace ``{applicationid}`` with what you copied) ``https://discord.com/oauth2/authorize?client_id={applicationid}&scope=bot%20applications.commands&permissions=105227086912``  
Then, go to your discord server, you can delete it later if you want, and in the settings for it, enable community.  
In the server, go to a channel and use the ``/ping`` command on the bot.  

## Claiming the badge

Finally, go to the [Discord Active Developers](https://discord.com/developers/active-developer) page and register everything. (**if it says you're not eligible, it's because you're not registered in their system yet. you might have to wait up to 24 hours**)

**NOTE:** Make sure you have the “Use data to improve Discord” setting enabled under User Settings > Privacy & Safety otherwise you won't be able to be marked as eligible.

Credits to [hackermondev](https://github.com/hackermondev) for making the repository for this to work.
