# FAQ

## **FAQ**

Here you can find answers to commonly asked questions. If you have any other questions or suggestions, please join the G4M3R server [**here**](https://github.com/pedall/g4m3r-wiki/tree/e02c9f1e99118cbc5606efe0a929aec2ad537940/%20https:/discord.gg/mtJyQjW/README.md).

## Questions & Answers

#### Q: Why wont G4M3R respond to me?

**A:** Make sure you are using the right prefix \(default is g!\). If that doesn't work, then report it in the \#support channel in the G4M3R discord server \(Use this link: [**https://discord.gg/mtJyQjW**](https://discord.gg/mtJyQjW)\)

#### Q: Something is broken on the bot and/or website, will it get fixed anytime soon?

**A:** Most likely the G4M3R development team already knows and they're doing their best to fix it. You can still let them know in the \#support channel in the G4M3R Server.

#### Q: How do I change the prefix?

**A:** `[prefix]s prefix`

**Example:**  `g!s prefix .`

![](.gitbook/assets/prefixchange.png)

#### Q: How do I use the events system?

**A:** Please view the [events](commands/community/events.md) page for a very detailed guide.

#### Q: What is the input for duration and frequency in an event?

**A:** Units

* `1 mo` = 1 month
* `1 w` = 1 week
* `1 d` = 1 day
* `1 h` = 1 hour
* `1 m` = 1 minute

**Important:** Format always has to be `<number><space><unit>`  
**Examples:** 

* 2.5 h = 2 hours and 30 minutes
* 130 m = 2 hours 10 minutes
* 30 h = 1 day and 6 hours

#### Q: Is there a cheatsheet for the bot?

#### Q: Is there a cheat sheet for the bot?

**A:** There is:

* .h details // lists all the commands in detail
* .e // lists all events in the server
* _.e add &lt;event-type&gt;_ // can be **"gaming"** or **"community"** or also without event type
* _.e join &lt;eventID&gt; &lt;pinCode&gt;_ // pincode only if event is set to private \(via edit only atm\)
* _.e leave &lt;eventID&gt;_
* _.e edit &lt;eventID&gt;_ // only if you are event author or server admin
* _.e delete &lt;eventID&gt;_ // only if you are event author or server admin
* ._e pin &lt;eventID&gt;_ // only if you are event author or server admin and event is private
* in the menu **select stuff with numbers** // when numbers are shown
* _j_ or join _&lt;pinCode&gt;_ //**pincode** if event is private
* _l_ or _leave_
* _e_ or _edit_
* _d_ or _delete_
* _a_ or _attendees_ // gives you the **attendees view**
* _k_ or _kick_ // then type _@user_ or the _userID_ to **kick a user**

A new pin is generated when setting private to false and true again.

#### **Q: How to join / leave an event?**

**A:** Steps:

1. Type in `.events`
2. Type in the `[event ID]` __\(For example: `1` to select event with ID 1\)\*
3. Type in `join` \(or `leave`\)

A quicker alternative is to just type `.events join 1` or `.e j 1`

#### Q: How to edit an event while creating it?

**A:** Steps:

* Next to each category in the create event menu is a `[number]`
* **Type in the number of the category you want to edit.**
* Follow the instructions displayed.
* Press the `enter` key to save your changes.
* Type in `C` to go back.
* Type `Q` to quit the event creation menu completely.

#### Q: How can I make G4M3R join my server?

**A:** Go to [https://g4m3r.xyz/](https://g4m3r.xyz/) and click on the **ADD** button

Or if you are in the G4M3R Discord Server, type `.join` ****in chat

![](.gitbook/assets/joinmessage.png)

### **Q:How do I customise my profile cards?**

**A: Check this!**

On the profile card you can show:

* Your social / gaming accounts _\(Marked RED\)_
* The top 3 games you play _\(Marked BLUE\)_
* Your clan / community \(feature in implementation\)

![](.gitbook/assets/profilemarked.png)

**Profile card:**

| \[prefix\]profile | View your own profile |
| :--- | :--- |
| \[prefix\]profile @username | View @mentioned user's profile |

»» example:

`.prof @pedall#2147`

**custom backgrounds:**

• open the menu with

`.background`

• directly select a background

`.bg number`

\(if you know the number\) • get all backgrounds of one category

`.bg category`

»» alias:

`.bg`

»» example:

`.bg 10`

or

`.bg game`

![](.gitbook/assets/backgroundpreview.png)

G**ames:**

* register a game with _.gamesadd &lt;gamename&gt;_
* change the priority of your registered games \(top 3 are on the profile card\) with _.g prio_

&lt;&lt;alias: _.g add &lt;gamename&gt;_

&lt;&lt;example: .g add game destiny 2

![](https://cdn.discordapp.com/attachments/282295514727448587/367002698131832834/image.png)

![](https://cdn.discordapp.com/attachments/282295514727448587/367002728301330432/image.png)

**help for each command** 

_.help &lt;commandname&gt; or alias_

&lt;&lt;alias _.h &lt;commandname&gt;/&lt;commandalias&gt;_

&lt;&lt;example _.h accounts or .h g \( g is the alias for games\)_

![](https://cdn.discordapp.com/attachments/282295514727448587/367003961007276042/image.png)

