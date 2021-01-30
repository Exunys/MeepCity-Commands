# MeepCity Commands

### About

This script is a MeepCity admin commands script. The scripts inside get executed by running a specific command in the chat
Default prefix is (/). You can change the prefix by using the command "/prefix *symbol*". Make sure the prefix is 1 character long though.
Make sure to use the commands with all lowercase. You can set the values with all capitals but not the command.
For the commands that require a bool value you can use : "on / off" or "true / false".

### Commands

- /cmds
- /prefix *string*
- /plus *bool*
- /boombox *bool*
- /candypack *bool*
- /rpname *string*
- /walkspeed *int*
- /jumppower *int*
- /teleport *player name*
- /tp *player name*
- /ws *int*
- /jp *int*
- /fov *int*
- /effects *bool*
- /sprint *bool*
- /clicktp *bool*
- /timechanging *bool*
- /fly *bool*
- /infinitejump *bool*
- /infjump *bool*
- /btools
- /rejoin

#### Commands explained

- (/cmds) Prints a list of commands, check the developer console for results (F9).
- (/prefix) The prefix that activates every single command. This changes the prefix to the value after the command. Example : /prefix ! (Changes the prefix from "/" to "!").
- (/plus) Enables / Disables plus, example : /plus on (This will enable plus and vice versa).
- (/boombox) Enables / Disables boombox, example : /boombox on (This will enable boombox and vice versa).
- (/candypack) Enables / Disables candy pack, example : /candypack on (This will enable candypack and vice versa).
- (/rpname) Sets your roleplay name to the message after the command. Example : /rpname Hello, Test! (This will set your roleplay name to "Hello, Test!").
- (/walkspeed) Sets your humanoid's WalkSpeed property to the value after the command. Example : /walkspeed 60 (Your WalkSpeed will be set to 60).
- (/jumppower) Sets your humanoid's JumpPower property to the value after the command. Example : /jumppower 115 (Your JumpPower will be set to 115).
- (/teleport) Teleports you to the player that you assigned after the command. This command also accepts shortened names. Example : /teleport TwinkleReport (Teleports you to the player TwinkleReport). Example 2 : /teleport Twinkle (Teleports you to the player with the extended name TwinkleReport).
- (/tp) Same as /teleport but shortened.
- (/ws) Same as /walkspeed but shortened.
- (/jp) Same as /jumppower but shortened.
- (/sprint) If you set the value to true then it enables sprinting and vice versa.
- (/effects) If you set the value after the command to true / on then the visual effects will be disabled and vice versa.
- (/clicktp) Enables click teleport script. Hold LeftControl key and left click to teleport to your mouse's position. 
- (/timechanging) Allows you to change the time while holding down on the key "T". The more you hold, the time changes. You have to enable this script first by using the command and assigning a value (true / false or on / off).
- (/btools) Gives you Building Tools (BTools).
- (/fly) If the value you assigned is true then you will fly and vice versa.
- (/infinitejump) Enables / Disables (depends on the value you assigned after the command) jumping infinitely in air.
- (/infjump) Same as /infinitejump but shortened.
- (/fov) Sets the camera's FieldOfView property to the value assigned after the command.
- (/rejoin) Leaves and re-joins the game. A good way to refresh this script.

Currently, there are 18 commands total in this script. Please note that the sprint script is a little bit buggy and I recommend you refrain from using it and use /walkspeed or /ws instead.

### Possible issues that you can face :

- Notification popup saying "Code has errored".
- Commands not working.
- Couldn't find any player's named *name*. That is because you are either in a different place but same server. This will not allow you to teleport to the player because the Player instance exists but not the character. In this case we're teleporting to the character so it would return nil.
- Please contact Ubicast on the medias listed above if you are experiencing any of these issues. (Check developer console "F9" and contact Ubicast with error information)

Load the script by using the code below or by copying it from [here](https://github.com/UbicastDev/MeepCity-Commands/blob/main/MeepCity%20Commands).
```lua
loadstring(game:HttpGet("https://pastebin.com/raw/guvdfbPu"))()
```

## Contact information

- Discord : [Aleksandar](https://discord.com/users/611111398818316309)
- ROBLOX : [Ubicast](https://www.roblox.com/users/330279990/profile)
