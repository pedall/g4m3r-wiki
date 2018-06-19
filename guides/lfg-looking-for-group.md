---
description: Want to create your very own custom LFG module for your server?
---

# LFG - Looking For Group

## What is an LFG Module?

An LFG, Looking For Group, module is a way for players to find other players on your server. We designed this module to be extremely customizable for each server because we knew that every server would want something unique. This guide will cover the **KISS** LFG module but you can customize them to however you like.

## Understanding The Basics Of LFG Module

The LFG Module has two core pieces, guild settings and events.

### Guild Settings

The most basic part here is to create and set up default settings for your LFG Module for your server. To do this we first go into the **Settings** command:

![](../.gitbook/assets/image%20%2823%29.png)

Next, we go into Events:

![](../.gitbook/assets/image%20%289%29.png)

Let us first look at Event Permissions:

![](../.gitbook/assets/image%20%2811%29.png)

1. Creation permissions are what define which type of users can create **events** that other players can find. Currently, this can be made to be:
   1. All Users
   2. Mods + Admins
   3. Admins Only
2. Add Member Permissions is what defined what level of permission you need to forcibly add a member to an **event**. I recommend leaving this at Admins Only to prevent any form of childish abuse from members forcing other members to an event.

Now lets take a look at the default guild settings:

![](../.gitbook/assets/image%20%2820%29.png)

1. The first thing we want to do is to _enable_ **Use Default** settings. This will make sure that anyone who tries to create an event on your server will automatically have these settings on their event.
2. Since this is a LFG module, we want to make sure that our **Type**, is set as Gaming.
3. Depending on the game, you can set your **Duration** how you like but for this guide we will set it to **2 h** duration.
4. We will set the **Attendees** Maximum to be 5 since Arena of Valor is a 5v5 Game.
5. Arena of Valor is a **Mobile** game so we will set the platform accordingly.
6. Since we are creating a LFG Module for Arena of Valor at the moment, we can set the **Game** to be for Arena of Valor.
7. **Advertisement channel** is really important as this is where the LFG events will be posted. I recommend creating a channel where you _disable_ Send Messages and Add Reactions for everyone except the bot. This will make sure that it is kept clean and professional on your server.
8. In this case, we will enable **Advertise All Events** but note that this will make it so any event created by anyone will be posted in the LFG channel declared above.
9. We will set the **Default Reminder Time** to be set at 30 minutes so that the users are reminded 30 minutes before the event starts that they had signed up.

The hard part is now done! You have now successfully, created and understood the settings for the LFG Module _hopefully!_

We know this is a complicated module so please don't be afraid to ask for help after you have read this guide thoroughly.

{% hint style="info" %}
**NOTE:** In order to make sure that users could still have their own custom default settings, the **usersettings** command enables any user to save their own defaults which will override all guild settings that you create on the server.
{% endhint %}

### Event Creation

Now that we have understood 50% of the LFG Module, let us understand and master the other 50%.

![](../.gitbook/assets/image%20%2838%29.png)

1. Add in a proper **Title** so that others will know what it is for immediately.
2. The **Start** time is when the event is set to start. This time will be used to send reminders, re-create recurring events as well as set the **Ends** time based on the duration.
3. The **Duration** will update the Ends time automatically.
4. A small **Text** description is very useful to help players understand exactly what it is.
5. **Max Members** sets the max amount of players that can join. Don't worry more players can join the waiting list.
6. **Tags** is what is used when players are using the search command to find events.
7. **Platform** is what device the game is played on. Sometimes, games separate players based on device so this is very useful.
8. **Game** is meant for players to determine what game the event is for.
9. **Activity** can be something to tell others what you wish to do in the game during the event.
10. **Private** allows you to make these events private or public.
    1. Private events will require players to enter a Password to join.
11. **Reminders** are at what times before the Start time, a message is sent by the bot in a private message reminding you all the attendees of the event.
12. **Recurring** allows events to be re-created after it ends.
13. **Interval** is only visible if Recurring is set to true and this allows you to determine how often to re-create the events.
14. **Timezone** helps set the timezone of the Time for the event.

{% hint style="success" %}
When showing an event, the time of the event will be shown to players based on **their** timezone and not the set timezone.
{% endhint %}

Wow that was complicated! No worries, you can always refer back to this guide when you need it. You don't need to memorize anything and it will all become very easy to do once you make a few events yourself. It is like riding a bike, once you learn it you can do it with your eyes closed.

{% hint style="danger" %}
**Note:** I do not recommend doing this with your eyes closed. 😝
{% endhint %}

## KISS: Keep It Simple Stupid!

This KISS LFG Module setup is mostly designed if you believe your users will have trouble following directions and you want to keep it as simple as possible for your users.

### Step 1: Setup The Category And Channels

On my server, I have players from all over the world and to make sure LFG events are easy to find for them I created separate events channels on the server.

![](../.gitbook/assets/image%20%287%29.png)

Each region was given it's own channel for LFG because players from one region are not able to play with others from another server.

{% hint style="info" %}
**Advanced Tip:** To take it a step further, you can create roles for each region and only allow each role to see their own specific channel so that users are not able to view or get spammed by channels they can not participate in.
{% endhint %}

### Step 2: Creating The First LFG Event

Now you can go ahead and create an base LFG event. This event should be made so that players can find each other.

Once the event is created, you can go into the channel of that server and type **.e ad id** but replace _id_ with the ID number of the event. In this case the event ID was 3 so I would type **.e ad 3**.

![](../.gitbook/assets/image%20%2847%29.png)

It will create an advertisement in that channel as well as post it in the default LFG channel you created. Please make sure that the bot has **Add Reactions** permissions enabled in these channels so that it can add those reactions.

I also made this event **recurring every 24 hours.** This makes it so that every day at 6PM EDT players can sign up to play together on my discord server. In order to join, the only thing that players have to do is tap the ✅in order to join and ❌ to leave.

![When a person joins the event.](../.gitbook/assets/image%20%2851%29.png)

![When a person leaves the event](../.gitbook/assets/image%20%2855%29.png)

{% hint style="warning" %}
**Note:** Please make sure the bot also has **Manage Messages** permission in these channels so that it can delete these extra messages that are sent when a person leaves or joins.
{% endhint %}

Now you can simply create other events at times your other users request to play and make them recurring every 24 hours. Once the events, are made players can join with a simple tap of a reaction. There is no complicated stuff for users and it really is Keep It Simple Stupid!

{% hint style="info" %}
**Advanced Users:** You can also create a \#custom-lfg channel where you allow other users to create their own events. For example, some users on a server can handle a higher amount of responsibility and they can be given permission to create and manage events on a separate channel for advanced levels.
{% endhint %}

