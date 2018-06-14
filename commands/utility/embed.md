# Embed

You can use[ Nadeko embed builder](https://embedbuilder.nadekobot.me/) to create neat looking embeds.

## `Use: <prefix>embed [optional: @user] [embed from Nadeko builder]`

 Using @user is only relevant if you use one of the USER variables.

## User Variables

Here are the possible variables that will replaced by the bot:

* _%author%, %authorimage%, %authormention%_
* _%user%,%userimage%, %usermention%_
* _%guild%, %guildimage%_

User variables only work when mentioning a user together with the command and guild variables only work **** when command is used in a guild channel

  
Soon there will be a custom Embed Builder in your dashboard

## Example

```text
.embed {"plaintext":"Test","title":"Test","description":"Test","footer":{"text":"Test"},"thumbnail":"%authorimage%","image":"https://www.almanac.com/sites/default/files/birth_month_flowers-primary-1920x1280px_pixabay.jpg","fields":[{"name":"Test","value":"%authorimage%","inline":false}],"color":7458112}
```

![](https://cdn.discordapp.com/attachments/282295514727448587/358940001846689794/image.png)

