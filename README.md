# Disclaimer
Everything in this repository should **ONLY** be used for educational and training purposes. The scripts **are not** intended to be used "in the field". As a reminder, all offenses against the confidentiality, integrity and availability of computer data and systems, including illegal access, is a crime.
# Hotplug Attacks
>As technology continues to advance, one persistant problem remains: the vulnerability of humans to cyber-attacks.

While most envision hackers as masterminds using intricate techniques and methods, the reality is that most successful attacks are a result of exploiting human error (layer 8 vulnerability). Hotplugs are devices hidden in the packaging of common peripherals:
- Most commonly, an abandoned USB, such as the [Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky)
- Or a lent phone charger
# Script Usage
Should you want to use the scripts, you will either have to compile them to a `.bin` before insertion into a bad USB or, through [qFlipper](https://flipperzero.one/update), place them into a [Flipper Zero](https://flipperzero.one). Depending on the machines being tested, the `DELAY` may have to be tweaked for those on the slower end.

Before proceeding any further, I would recommend learning about the [Ducky Syntax](https://docs.hak5.org/hak5-usb-rubber-ducky).
# Script Functionalities
Finally, the fun parts:
- [disable_defender](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/disable_defender.txt) : disables Defender' real-time protection
- [disable_user_account_control](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/disable_user_account_control.txt) : disable user notifications for modifications applied to the computer
- [i_ate_your_cookies](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/enable_bluetooth.txt) : a simple example that opens notepad and writes some text
- [enable_bluetooth](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/i_ate_your_cookies.txt) : as the name suggests, it enable Bluetooth
- [rickroll](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/rickroll.txt) : opens a browser to a specific link