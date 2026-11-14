# ADB debugging

ADB lets you control the screen from a computer with commands: install apps, read the log, copy files. It comes turned off and is only for those who need it.

> [!WARNING]
> With ADB on, anyone with access to your network can try to control the screen. Only turn it on while you're using it and turn it off when you're done.

## Turning it on

### In the setup wizard

Under **Advanced options → Debugging (ADB)**. It's turned on over USB and Wi-Fi, and your network is accepted for wireless debugging.

### Later, from Settings

1. In **Settings → About device**, tap **Build number** seven times. **Developer options** appear.
2. Go to **Settings → System → Developer options**.
3. Turn on **USB debugging** or **Wireless debugging**.

The first time a computer connects, the screen asks whether you allow it.

## Over Wi-Fi

1. In **Developer options**, go to **Wireless debugging**.
2. Tap **Pair device with pairing code**.
3. On the computer, type the address, port and code shown on the screen:

| Step | Command |
| --- | --- |
| Pair, only the first time | `adb pair <IP>:<pairing port> <code>` |
| Connect | `adb connect <IP>:<port>` |

The port for connecting changes every time it's turned on: check it in **Wireless debugging**.

## Over a cable

You need the same cable you used to install Home: on the Rev5, with the adapter to the internal connector. It's in the [installation guide](../INSTALL.md#2-rev4-or-rev5-and-connecting-it-to-the-pc).

> [!IMPORTANT]
> With the computer's USB cable connected, the screen doesn't finish starting up. Unplug it before restarting.

## Turning it off

In **Developer options**, turn off **USB debugging** and **Wireless debugging**.
