# batnotify
A simple but nice battery notifier.

![demo](https://user-images.githubusercontent.com/88589756/163951992-9a9a0b6b-242e-46ac-a7d6-a85a3b350d97.png)

## What is it?
Like it the title says. It shows a notification when the battery is low. Plus it plays a nice beep bios sounds when showing the notifications.

## How can I install it?
1: Make sure you have a notification daemon (dunst for example) and beep installed. Otherwhise it won't work. And check if the beep bios sounds is enabled from bios and is unmuted from alsamixer.

![aslamixer](https://user-images.githubusercontent.com/88589756/164026277-bebeae52-a97a-4ffd-bb9f-796fc05d1f13.png)

2: You need to download the installer by using `git clone https://github.com/GabubuAvailable/batnotify.git && cd batnotify` command;

3: Run the installed as root on your terminal. Running as user you'll receive this error:

![error](https://user-images.githubusercontent.com/88589756/163953503-4cfe081e-63a6-4dbf-ba03-bdf60e7f9430.png)

4: Choose the language (not your language here? you can contribute by translating. check at bottom for more)

![language](https://user-images.githubusercontent.com/88589756/163954072-b77928f7-ce8c-46ef-b1ac-c684caa7e825.png)

5: Choose "Install"

![menu](https://user-images.githubusercontent.com/88589756/163954226-3d173179-9519-406c-b362-1b8fb4ab32f6.png)

6: After installing will come a small guide how it sounds when the battery is low.

7: What you need to do is use your .xinitrc or autostartup settings to run batnotify automatically

8: Congrats! Now you have batnotify.

## How can I uninstall it?
1: Download the source code (see on installing part)

2: Run the installer as root.

3: Choose language

4: Choose "Uninstall"

5: That's it. You uninstalled batnotify. Now make sure to delete the batnotify from your .xinitrc or autostartup settings.

## Do you want to translate?
To contribute you need to download the file by [clicking here](https://raw.githubusercontent.com/GabubuAvailable/batnotify/main/translate%20submit) and completing.

After that, create a new issue with this file and wait :)

## Thanks to:
- Me for creating this lol
- Damaj301damaj for French translation
- sctech-tr for Turkish translation
