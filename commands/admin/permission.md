# Permission Command

The **Permission** command lets you active or deactivate the usage of a specified command in a specific channel.  
You can easily view information about the set permissions.

#### Use:

**Get information:**

`[prefix]permission` _View all commands with special permissions defined._

`[prefix]permission <command>` _View permission settings from specified command._

`[prefix]permission <@role|id>` _View the permission settings of @role or role ID._

`[prefix]permission <#channel|id>` _View permission settings of \#channel or channel ID._

##### Preview:

![](/assets/permissionscommand.png)

##### 

##### 

##### Set permissions:

`[prefix]permission enable|disable <command name>`  _Enable/Disable the use of an command for the whole server. This deletes old set permissions for that command on the server._

`[prefix]permission enable|disable <command name> <@role|#channel|id>` _Enable/Disable the use of an command for a specified @role or \#channel. This deletes old set permissions for the specified command regarding the specified @role / \#channel._

##### Preview:

![](/assets/permissioncommanddisable.png)_    
_

`[prefix]permission remove <command name>`_ Removes all current exceptions for the specified command._

`[prefix]permission remove <command name> <@role|#channel|id>` _Removes all current exceptions for the specified command regarding the specified @role, \#channel or ID._

##### Preview:

![](/assets/permissioncommandroledisable.png)
