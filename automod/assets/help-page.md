Automod allows you to set up some automated moderation on your server, like banning websites, banning foul language and so on.

The different rules you can set up at the moment:

 - **Slowmode**: Users are allowed to send max `x` messages in `y` seconds
 - **Mass mention**: Messages that contain more than `x` unique mentions (everyone and here mentions don't count)
 - **Server invites**: Messages that contain invites to other servers (invites to the same server are allowed, so are expired ones. *will not block links to something like pastebin that contain invite links*)
 - **Links**: Restrict sending of all links
 - **Ban websites**: Restrict specific websites
 - **Ban words**: Restrict specific words


All rules have a set of common options:

 - **Enabled**: If this is checked, the rule is enabled, otherwise it's disabled (This also applies to the general automod page)
 - **Violations expire after**: This is the amount of time (minutes) before a users violations have expired, if a user has 1 minute left before it expires and then breaks the rule again, then his violations expire time will be reset to this again. So the user has to go this many minutes without any violations for them to expire.
     + 1440 minutes = 1 day
     + max 1 week
 -  **Mute/Kick/Ban after**: this is the amount of violations that are required for a mute/kick/ban, if this is set to 0 then it will never apply this punishment. *Even if all the punishments are disabled, the messages that break the rules will still be removed and the user will still be warned.* Caution with the ban option!
 -  **Ignore role**: This rule does not apply to people with this role (Good for staff or admins)
 -  **Ignore channels**: This rule is ignored in the selected channels (if it doesnt work in some channels, check that the bot can read and manage messages there)

There are plans to extend automod in the future but time is a valuable resource.
