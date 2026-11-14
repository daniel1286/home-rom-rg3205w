# Common problems

What happens most often and how to fix it. If your problem isn't here or doesn't get fixed, [report it](contar-un-problema.md) and you'll see the answer on the screen itself.

## Screen

### The screensaver doesn't come on

It's down to one of these two things:

1. In the **Screensaver** app, **When not in use** is set to **Keep what is on screen**. Choose **Show the screensaver**.
2. An app is keeping the screen on. In Fully Kiosk, turn off its **Keep Screen On** option.

More in [The screensaver](salvapantallas.md).

### It stays black when restarting

With the computer's USB cable connected, the screen doesn't finish starting up. Remove the cable, unplug the screen from the mains and plug it back in.

### The Back, Home and Recents buttons don't show

It's not a fault: Home comes with gesture navigation. If you prefer the buttons, go to **Settings → System → Gestures → System navigation** and choose **3-button navigation**. The gestures are explained in [Getting around Home](moverte-por-home.md).

### The power button does nothing

A short press turns off the display and a long press opens the menu to turn off or restart. If you use Fully Kiosk, check that its option to disable the power button isn't turned on.

## Cast

### The iPhone or the computer can't see the screen

- Check that both are on the same Wi-Fi network. Guest networks on routers usually don't let devices see each other.
- In the **Cast** app, check that it's turned on and that what you're using is on under **Sources**.
- With **Sound only** on, Windows and Android can't see the screen: they're only for mirroring it.

### The picture is black

Paid movies and series can't be sent to another screen because of their copy protection. Everything else shows normally.

### It drops out or stutters

The picture travels over Wi-Fi. Move the screen or the device closer to the router and, if you can, use the 5 GHz network. In **Cast → Quality**, **Like the screen** is lighter on the network than **High (1080p)**.

## Sound and Bluetooth

### The Bluetooth speaker disconnects

In **Settings → Connected devices**, tap the speaker, choose **Forget** and pair it again. Keep it close to the screen while you do it. Calls don't go over Bluetooth: a headset with a microphone only plays sound.

### It doesn't play in sync with the rest of the house

Open the **Snapcast** app and check that it's connected to your music server. If the server can't see the screen, give it a name from the server itself. See [House speaker](altavoz-de-casa.md).

## Wi-Fi and time

### No Wi-Fi networks show up

Tap **Search again**. If still none show up, restart the screen with a long press of the power button.

### The time is wrong

The screen has no clock battery: it gets the time from the Internet. In **Settings → System → Date & time**, check that automatic time is on and that the time zone is yours.

## Updates

### The update won't install

The **Updates** app tells you why. The most common causes:

- **Remove the USB cable**: with the computer's cable connected, it doesn't finish starting up.
- **No space**: it needs twice the size of the version. Free up some space and try again.
- **The connection was lost**: what was downloaded is kept; when you try again, it picks up where it left off.

Each message is explained in [If an update won't install](si-no-se-instala.md). Your apps, settings and data aren't touched.

### It doesn't tell you about new versions

In **Updates → Settings**, look at **Automatic check**: if it's set to **Never, manual only**, it won't let you know. You can check whenever you like with **Check now**.

## Dashboard and apps

### The dashboard doesn't open at startup

Fully Kiosk has to be the home app. Go to **Settings → Apps → Default apps → Home app** and choose **Fully Kiosk Browser**. If it opens but stays blank, check your Home Assistant's address in Fully.
