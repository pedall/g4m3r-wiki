# Embed

## Usage

```text
<prefix>embed [user] [embed] [whatever]
```

## Extended Help

&gt;&gt; _Two options_ to create an embed:

* _embed @user &lt;embedObject from Nadeko embed builder&gt;_
* _embed &lt;embedObject from Nadeko embed builder&gt;_

using @user is only relevant if you use one of the USER variables

&gt;&gt; Possible _variables_ that will replaced by the bot:

* _%author%, %authorimage%, %authormention%_
* _%user%,%userimage%, %usermention%_
* _%guild%, %guildimage%_

&gt;&gt; user variables **only work** when mentioning a user together with the command

&gt;&gt; guild variables **only work ** when command is used in a guild channel

**Create your embed object on this website: **[embedbuilder.nadekobot.me](https://embedbuilder.nadekobot.me/)  
Soon there will be a custom Embed Builder in your dashboard ;\)

## Example

```text
.embed {"plaintext":"Test","title":"Test","description":"Test","footer":{"text":"Test"},"thumbnail":"%authorimage%","image":"https://www.almanac.com/sites/default/files/birth_month_flowers-primary-1920x1280px_pixabay.jpg","fields":[{"name":"Test","value":"%authorimage%","inline":false}],"color":7458112}
```

![](https://cdn.discordapp.com/attachments/282295514727448587/358940001846689794/image.png)

