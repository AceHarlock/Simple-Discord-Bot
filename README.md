# How to Make a Discord Bot in the Developer Portal?

Before you can dive into any Python code to handle events and create exciting automations, you need to first create a few Discord components:

1. An account
2. An application
3. A bot
4. A guild
You’ll learn more about each piece in the following sections.

Once you’ve created all of these components, you’ll tie them together by registering your bot with your guild.

You can get started by heading to Discord’s Developer Portal.

<h2>Creating a Discord Account</h2>

The first thing you’ll see is a landing page where you’ll need to either login, if you have an existing account, or create a new account:

<img src="./readme/img1.webp"/>

If you need to create a new account, then click on the Register button below Login and enter your account information.
Once you’re finished, you’ll be redirected to the Developer Portal home page, where you’ll create your application.

<h2>Creating Application</h2>
An application allows you to interact with Discord’s APIs by providing authentication tokens, designating permissions, and so on.

To create a new application, select New Application:

<img src="./readme/img2.webp"/>

Next, you’ll be prompted to name your application. Select a name and click Create:

<img src="./readme/img3.webp"/>

Congratulations! You made a Discord application. On the resulting screen, you can see information about your application:

<img src="./readme/img4.webp"/>

Keep in mind that any program that interacts with Discord APIs requires a Discord application, not just bots. Bot-related APIs are only a subset of Discord’s total interface.

However, since this tutorial is about how to make a Discord bot, navigate to the Bot tab on the left-hand navigation list.

<h2>Creating a Bot</h2>

As you learned in the previous sections, a bot user is one that listens to and automatically reacts to certain events and commands on Discord.

For your code to actually be manifested on Discord, you’ll need to create a bot user. To do so, select Add Bot:

<img src="./readme/img5.webp"/>

Once you confirm that you want to add the bot to your application, you’ll see the new bot user in the portal:

<img src="./readme/img6.webp"/>

Notice that, by default, your bot user will inherit the name of your application. Instead, update the username to something more bot-like, such as RealPythonTutorialBot, and Save Changes:

<img src="./readme/img7.webp"/>

Now, the bot’s all set and ready to go, but to where?

A bot user is not useful if it’s not interacting with other users. Next, you’ll create a guild so that your bot can interact with other users.
