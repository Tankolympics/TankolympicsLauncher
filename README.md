# TankolympicsLauncher
The launcher software of Tankolympics.
Now also featuring a responsive UI!

## For anyone intrested in the inner workings of this software:
1. Launcher checks if our local version of the game differs from the one at the cloud server, using a handy version file.
2. Launcher downloads the latest ZIP package of the game "Tankolympics" from OneDrive utilizing my
"base64 encoder" (https://github.com/TheJapsu1/base64-onedrive-link-encoder) .
3. The package gets unzipped and moved to the game's destination folder, without removing any of the user progress/data. The now useless ZIP gets deleted.
4. And voilá, we got a working launcher!

## Known issues:
-There's no checksum validation, so every time you
update the game, the launcher has to download the full
zip package again.
-Also there could be some UI bugs, haven't checked in a while.

##TODO
-Moved todo list to Trello
