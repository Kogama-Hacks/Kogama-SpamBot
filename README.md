# Kogama-SpamBot
Kogama SpamBot is a program which spams comments on Kogama.

Preview (version 1.0):
![Preview 1.0](https://i.imgur.com/sDgwrMD.png)

## Download
To download, click "releases" on the right side of your screen, then scroll to the version you want to download.
On the versions, you will see 5 files:
 - spambot.onedir.zip - everything (Python, modules, etc.) is bundled in the single directory.
 - spambot.onefile.exe - everything (Python, modules, etc.) is bundled in the single exe.
 - spambot.src.py - source Python script.
 - sourcecode.zip and .tar.gz - contain everything in this repo (the readme file).

## How to use

Launch the variant you prefer (source .py, single exe or directory). All of them work basically the same.

Then, it will prompt you to enter the Kogama server. Enter either 'www', 'friends' or 'br'.
www: https://www.kogama.com
friends: https://friends.kogama.com
br: https://kogama.com.br

Now, it will ask you which object it should spam on.
Enter the ID of the object. Add prefix 'a-' if you mean an avatar, add prefix 'i-' if you mean a model. Adding no prefix treats the ID as game ID.
Examples:
136436 - game ID
a-453235 - avatar ID
i-557743 - model ID

*Note: commenting on avatars and models works only if that avatar/model is sold.*

After that, it will ask you which text it should write in the comments. Type in the text you want to spam in the comments.

Then, enter your kogama username and password (they are required because the script will login with that account data to be able to write comments).

Now it will spam comments.

To exit, press CTRL+C in the program window or just close the program.
