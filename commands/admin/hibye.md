# Hibye Command

The Hibye command is a great command that can be used together with [Embed](/commands/utility/embed.md) to create great welcome _\(hi!\)_ and goodbye _\(bye!\)_ messages. There are quite a few aliases for the hibye command but lets keep it simple for now.

#### Use: `[prefix]hibye <hi/bye> <enable/disable/set/get>`

Lets break down the command line:  
`[prefix]hibye` Letting the bot know you want to use this command \(aliases below\)  
`<hi/bye>`  View or edit  `hi`or `bye` part of the command.  
`<enable/disable/.../...>` Enable/disable the command in the current channel.  
`<.../.../set/get>` To insert a new message choose `<set>`. Or view the current message with `<get>`

**Aliases for hibye:**

* `[prefix]hi`
* `[prefix]bye`
* `[prefix]welcome`
* `[prefix]goodbye`

### Examples:

**View** the current welcome/hi message: `[prefix]hi hi get`

**Disable** the bye message in the current channel: `[prefix]hibye bye disable`

**Set** a new welcome message: `[prefix]hi hi set {embededmessage}`

**Preview:**

`[prefix]hi hi enable`

![](/assets/hibye-welcomeenable.png)

`[prefix]hi bye disable`

![](/assets/hibyegoodbyedisbale.png)

