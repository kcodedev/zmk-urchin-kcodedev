# Getting started

Check [the ZMK docs](https://zmk.dev/docs/user-setup#installing-the-firmware) for instructions on how to flash it.

[See it in action on YouTube!](https://youtu.be/IZ83uU0ltaE)

Here is how you can create your own ZMK keymap for the Urchin.

1) [Fork this repository](https://github.com/duckyb/zmk-urchin/fork)
2) Enable actions on your fork. (click on the actions tab and enable actions)
3) Edit the `zmk-urchin/config/urchin.keymap` file to your liking. (See the [ZMK Codes reference](https://zmk.dev/docs/codes))
4) When you push the changes an action will start that will build your firmware. If the action is successful the file will be available in it's assets. Check the [ZMK docs](https://zmk.dev/docs/user-setup#installing-the-firmware) if you need a visual guide.

## Reminder on pairing

If you get stick in a loop of connected/unconnec rapidly. Clear the bluetooth profile. Delete the pairing. Rediscover and pair again.

Use "&bt BT_CLR" for clearing. And "&bt BT_SEL n" to select the different pairings. You might have "&bt BT_SEL 0" for laptop. "&bt BT_SEL 1" for desktop. and "&bt BT_SEL 3" for your phone.
