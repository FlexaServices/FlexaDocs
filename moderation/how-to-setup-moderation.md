# How to setup moderation

### Setting up the moderation-config

In your server, make sure you have a channel dedicated to moderation-logs and in that channel, execute the command /moderatesystem configure and it gives you the prompts called logging\_channel mute\_role and multi\_guilded. Always set multi\_guilded to <mark style="color:red;">false</mark>. logging\_channel is your created moderation-logs channel and your mute\_role is the dedicated role for muting users.

When you press enter on the command it will return an embed saying "✅ successfully configured the moderation system" now you know the moderation system is setup. Any command you execute regarding banning, muting, kicking, striking etc will be sent to that channel.
