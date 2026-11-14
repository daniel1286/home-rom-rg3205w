# Root with Magisk

With root, the apps you allow can change the whole system. Home comes with Magisk ready, but root is off by default: it's only turned on if you ask for it.

> [!CAUTION]
> An app with root can break the system or read everything on the screen. Only turn it on if you know what you need it for, and only allow apps you trust.

## Turning it on in the setup wizard

Under **Advanced options → Root (Magisk)**, turn on **Allow root with Magisk**. When you apply, the Magisk app is installed.

From then on, every time an app asks for root, Magisk asks you before granting it. The only one that gets it without asking is Fully Kiosk, if you use the Home Assistant dashboard.

## Turning it on or off later

Root is decided when the screen starts up, based on a setting. If you didn't turn it on in the setup wizard, you change it with [ADB](adb.md):

| To | Command |
| --- | --- |
| Turn it on | `adb shell settings put global home_root 1` |
| Turn it off | `adb shell settings put global home_root 0` |

Then restart the screen. With root on, the Magisk app installs itself at startup. With root off, no app gets it; the Magisk app can be uninstalled like any other.

## Updates

Home updates keep root as you have it: the setting doesn't change. Magisk always comes inside Home and is brought up to date with each version.
