# Disclaimer
Everything in this repository should **ONLY** be used for educational and training purposes. The scripts **ARE NOT** intended to be used "in the field". As a reminder, all offenses against the confidentiality, integrity and availability of computer data and systems, including illegal access, is a crime.
# Hotplug Attacks
>As technology continues to advance, one persistant problem remains: the vulnerability of humans to cyber-attacks.

While most envision hackers as masterminds using intricate techniques and methods, the reality is that most successful attacks are a result of exploiting human error (layer 8 vulnerability). Hotplugs are devices hidden in the packaging of common peripherals:
- Most commonly, an abandoned USB, such as the [Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky)
- A lent phone charger

# Script Usage
These scripts have only been tested on Windows machines. Reading the [Ducky Syntax](https://docs.hak5.org/hak5-usb-rubber-ducky) documentation will grant you some understanding of the scripts and how to convert them to other systems. Do note, that depending on the hardware, the `DELAY`s may have to be tweaked for slower hosts.

# Script Functionalities
Finally, the fun part!

| SCRIPT                                                                                                                          | DESCRIPTION                                                          |
| :------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------- |
| [disable_defender](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/disable_defender.txt)                         | Disables Defender' real-time protection                              |
| [disable_user_account_control](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/disable_user_account_control.txt) | Disable user notifications for modifications applied to the computer |
| [i_ate_your_cookies](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/enable_bluetooth.txt)                       | A simple example that opens notepad and writes some text             |
| [enable_bluetooth](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/i_ate_your_cookies.txt)                       | As the name suggests, it enable Bluetooth                            |
| [rickroll](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/rickroll.txt)                                         | Opens a browser to a specific link                                   |
| [wifi_exfiltration](https://github.com/DarkKooky/Bad-USB-Scripts/blob/main/Scripts/wifi_exfiltration.txt)                       | Retrieves all stored network profiles                                |
