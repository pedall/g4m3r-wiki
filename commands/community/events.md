# Events Command

G4M3R has the best event system on Discord. It allows you to create private/public events. Private events require a password to join, which is sent to the event creator via direct message. Not only can you join/create events, you have some moderation over them. You can kick members you don't want in your event. The timezone of the event is related to the timezone set in the server [settings](/commands/admin/settings.md).

#### Use: `[prefix]events <action> <event type/ID>`

**Actions and Aliases:**

`e` can be used instead of events

Leave action blank to view all events in the server.

`add/a <event type>` to create an event  
_Event type can be: gaming, community or calendar. If no event type is entered, the default is community._

`show/s <event ID>` to show the details of the event with that ID

`join/j <event ID> <pin if private>` to join that event

`leave/l <event ID>` to leave that event

The following actions can only be used if you are the **event creator** or a **server admin**:

`edit/e <event ID>` to edit the event with that ID

`delete/del <event ID>` to delete that event

`advertise/ad <event ID>` to display the event details to advertise the event

`pin <event ID>` direct messages you the pin of a private event

---

#### Creating an Event

`[prefix]events add`

Enter the number corresponding to the information you would like to edit. When editing a section, just follow the instructions displayed.

![](/assets/Ems_EventCreate.png)

Press the `enter` key to save your changes.  
Enter `c` to cancel the change and return to the event creation menu.  
Enter `q` to quit event creation completely.

When editing the duration or frequency \(to change frequency, recurring must be set to true\) of the event, keep in the mind the format has to be `<number><space><unit>`

Below, the unit is shown like `this`

`mo` = month

`w` = week

`d` = day

`h` = hour

`m` = minute

Examples:

`2.5 h` = 2 hours and 30 minutes

`130 m` = 2 hours 10 minutes

#### Private Events

When an event is set to private, the creator will be sent a pin via direct message. Any member wishing to join this event must enter the pin along with the join command.

The direct message will look like this:

![](/assets/Ems_Event-NewPin.png)

So in this example, a user would type`<prefix>events join 2 9988`to join.

#### ![](/assets/Ems_EventJoined.png)

#### View All Server Events

`<prefix>events`

![](/assets/Ems_Eventlist.png)



