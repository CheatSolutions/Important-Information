# <a href="https://www.paypal.com/ncp/payment/EVXKXBD6M5XPC">Get Java & Bedrock Edition in one jar</a>

## Command Arguments
``<>`` Required command argument<br>
``[]`` Optional command argument<br>
You can hover above commands in-game to get additional descriptions about their functionality.


## Command List

``/vacan menu`` opens the main gui menu.<br>
Permissionss: vacan.info, vacan.manage

``/vacan panic`` enables silent mode and disables punishments for all checks.<br>
Permissions: vacan.manage

``/vacan reload`` reloads Vacan's configuration.<br>
Permission: vacan.reload

``/vacan notifications [ticks-frequency]`` toggles the notification system.<br>
Permission: vacan.notifications

``/vacan verbose`` toggles all notifications instead of just ones with high hacking probability.<br>
Permission: vacan.notifications

``/vacan info [player]`` opens a GUI menu with a player's violations info.<br>
Permission: vacan.info

``/vacan kick <player> <reason>`` kicks a player and broadcasts a message.<br>
Permission: vacan.kick

``/vacan toggle <check>`` toggles a certain check.<br>
Permission: vacan.manage

``/vacan toggle-prevention <check>`` toggles a certain check's preventions by making it silent.<br>
Permission: vacan.manage

``/vacan toggle-punishment <check>`` toggles a certain check's punishments.<br>
Permission: vacan.manage

``/vacan bypass <player> <check> <seconds>`` allows a player to bypass a check for a certain amount of time.<br>
Permission: vacan.use_bypass

``/vacan warn <player> <reason>`` warns a player with a reason.<br>
Permission: vacan.warn

``/vacan wave <add/remove/clear/run/list> [player] [command]`` allows you to interact with the wave punishment system.<br>
Permission: vacan.wave

``/vacan proxy-command <command>`` sends a command to the proxy/network of servers. (Example: BungeeCord) [May not always work]<br>
Permissions: vacan.admin, vacan.*

```
/vacan <player> if <condition> equals <result> do <command> executes a conditional command.
/vacan <player> if <condition> contains <result> do <command> executes a conditional command.
/vacan <player> if <number> is-less-than <result> do <command> executes a conditional command.
/vacan <player> if <number> is-greater-than <result> do <command> executes a conditional command.
```
Permission: vacan.condition


## Additional Permissions
vacan.bypass allows you to bypass all checks. (USE THE settings.yml op_bypass OPTION WHEN OP)
vacan.bypass.(check) allows you to bypass a certain check.
vacan.admin, vacan.* gives you all permissions except the bypass ones. (BE CAREFUL WHEN OP)
vacan.bedrock considers a player as a Bedrock client instead of Java client. (BE CAREFUL WHEN OP)
vacan.punishment allows you to bypass the configured punishments of all checks.


## Hovering Above Commands
Vacan supports interactive commands. When you hover above a command, Vacan will create a small hovering box that explains in text what the command does and examples of how you can use it.


## Pressing TAB
Vacan supports command auto-complete. To trigger it, type /vacan and press the button TAB on your keyboard. This functionality takes part as a list of recommendations to save you time.


## Permissions that judge Staff Rank / Ranks
```
vacan.admin
vacan.*
vacan.info
vacan.manage
vacan.reload
vacan.notifications
vacan.kick
vacan.use_bypass
vacan.warn
vacan.wave
vacan.condition
```

## Command Proxy-Transfer Plugins (BungeeCord, Velocity, WaterFall)
https://www.spigotmc.org/resources/27580/<br>
https://www.spigotmc.org/resources/52093/

