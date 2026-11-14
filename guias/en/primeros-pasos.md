# First steps

The first time it's switched on, Home opens a setup wizard that gets the screen ready in a few minutes. Here's what each step asks, what's best to choose and where to change it later.

## Before you start

- The screen has to be plugged in. It has no battery: if you unplug it, it turns off.
- Have your Wi-Fi password at hand.
- If you're going to use it as a Home Assistant dashboard or as a house speaker, leave your server on: the wizard looks for it on the network.

Every step has **Back** at the bottom left and **Next** at the bottom right. Almost nothing is applied until the end, so you can go back and forth without worrying.

## Language, region and text

**Hello.** Choose the language: the wizard switches right away and the screen stays in that language. Then tap **Start**.

**Region and time.** The time zone (Mainland Spain and Balearic Islands, Canary Islands, Ceuta and Melilla, or Portugal), whether the time comes from the Internet and whether you want the 24-hour format.

**Text size.** Normal, Large or Very large. Tap one and the whole wizard changes so you can see how it looks. It applies to every Home app, the screensaver included.

## Wi-Fi and name

**Wi-Fi.** Choose your network, type the password and tap **Connect**. If it doesn't show up, tap **Search again**. You can skip this step, but without a connection the Home Assistant dashboard can't be installed and the time can't be set automatically.

**Name.** What the screen will be called on your network, over Bluetooth and when casting. If you have more than one at home, name it after the room: Living room, Kitchen, Hallway…

## What to install

Tick what you'll use. Whatever you don't tick isn't installed and takes up no space.

| Option | What it's for |
| --- | --- |
| Home Assistant dashboard | Your dashboard full screen, opening by itself at startup. Fully Kiosk shows it |
| House speaker | The screen plays in sync with the rest of your speakers, from your music server |
| Control the screen from your PC | See and touch the screen from another computer |
| F-Droid | Store of free and open-source apps |
| Aurora Store | Google Play apps without a Google account |
| Help | This guide and, if something goes wrong, reporting it and seeing the answer |
| Monitor | See how the screen is doing inside: processor, memory, temperatures and network |

Help, F-Droid and Aurora Store come ticked; Monitor doesn't. Help and Monitor can be uninstalled later like any other app.

If you tick the dashboard or the speaker, two more steps show up:

- **Home Assistant.** The wizard looks for it on your network. If it can't find it, type the address, for example `homeassistant.local:8123`. If your Home Assistant uses its own certificate, add it in **Advanced options**.
- **House speaker.** Choose your music server from the list or type its address.

## Cast and screen at rest

**Cast.** Lets this screen receive the picture and sound from an iPhone, a Mac, a Windows computer or an Android phone. Choose who can send:

- **With a code the first time** (the default): the first time, Apple devices enter a four-digit code shown on the screen, and other devices ask for permission on it.
- **Anyone at home**: any device on your network can send without asking.
- **With a password**: Apple devices use a password you choose; other devices ask for permission the first time.

It comes turned on. If you're not going to use it, turn off **Receive on this screen** and Cast is removed; you can add it whenever you like from **Updates → Home apps**, under **Optional**.

**Screen at rest.** What happens when nobody is touching it:

- **Show the screensaver**: the time, the weather and your backgrounds. Choose how long until it comes on, and your city, which is where the weather, rain and aircraft come from.
- **Keep what is on screen** (the default): the dashboard or whatever app you have open stays in front.

The alarm clock rings either way.

**Display.** The brightness and, if you don't use the screensaver, how long until it turns off. If you use it as a dashboard or a clock, choose **Never**.

**Navigation.** How you move around the screen: with **Gestures** (the default) or with **Buttons**, always visible at the bottom. It's explained in [Getting around Home](moverte-por-home.md).

## Privacy and advanced options

**Privacy.** Whether the microphone and camera can be used. The camera comes turned off.

**Help improve Home.** If you like, the screen reports once a day how it's set up and whether updates go well. It's off by default: nothing is sent unless you turn it on. The step tells you what is sent and what is never sent.

**Advanced options.** Static IP, MAC address, your own certificates, ADB debugging and root. If you don't need them, tap **Continue**. They're explained in the [Advanced](README.md#advanced) section.

## Summary

Go over everything. Tap a line to change it and, when it's all right, tap **Apply**.

The screen tells you what it's doing as it goes. Don't turn it off or unplug it in the meantime. If something doesn't work, it shows it at the top and lets you go back to the summary; everything else is already in place. When it's done, tap **Start using it**. There's no need to restart.

## Where to change it later

| What | Where |
| --- | --- |
| Language | Settings → System → Languages |
| Text size | Settings → Display → Font size |
| Wi-Fi | Settings → Network & internet |
| Name | Settings → About device → Device name |
| Cast | Cast app |
| Screensaver | Screensaver app → When not in use |
| Brightness and screen timeout | Settings → Display |
| Gestures or buttons | Settings → System → Gestures → System navigation |
| Help improve Home | Updates app → Settings |
| ADB debugging | Settings → System → Developer options |
