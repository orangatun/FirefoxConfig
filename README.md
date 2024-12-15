# Firefox Config

This is meant to be a simple keyboard centric theme based on https://github.com/mimipile/firefoxCSS which in turn uses https://github.com/JarnotMaciej/Essence.

## Preview

![Using Ctrl+L or Command+L key](https://github.com/user-attachments/assets/5569f8bb-8bde-4838-96cc-c3da25f006da)

![The hover space is all the way to the top edge, and doesn't get in the way](https://github.com/user-attachments/assets/c1efc4fd-c1ba-4bca-aa5a-dc4331c7a2d1)


## Setup instructions

1. Open Firefox, and enter `about:config` in the URL, to go to the Firefox configuration page.
2. If this is your first time, you'll see a warning. Click on "Accept the Risk and Continue" to proceed. 
3. Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in the config.
4. Enter `about:profiles` in the URL, to go to the profiles in Firefox. You should see the path, and a button "Show in Explorer" or "Show in Finder" depending on your Operating System.
5. Create a `chrome` directory in the profile directory.
6. Copy the `userChrome.css`file to the `chrome` directory.
7. Restart Firefox to see the changes.

