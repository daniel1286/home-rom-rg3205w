# Web panel

With the web panel you can see how the screen is doing and change its settings from your phone or computer browser, without touching it. It only works at home and comes turned off: you only have it if you choose it.

## Turn it on

- **In the setup wizard**, tick **Web panel** in **What to install**. It's installed and turned on.
- **If you updated from 2.0**, it's offered in “What's new” for version 2.1: **Install and turn on the web panel**.
- **If you didn't tick it**, add it from **Updates → Home apps → Optional**, with **Add**. It's added turned off.
- **If you already have it**, open the **Web panel** app and turn on the **On** switch, at the top right.

While it's on, there's a permanent notification, “Web panel on”, with a **Turn off** button.

## Pair your phone or computer

1. On the screen, open the **Web panel** app. Under **Open the panel** you see the address and a QR code.
2. Scan the code with your phone, or type the address exactly as it appears, with the `:8443` at the end. If you type it without `https://`, the screen takes you to the secure version by itself.
3. The first time, the browser warns that the certificate isn't from a known authority. That's normal: it belongs to this screen. Check that its fingerprint (SHA-256) is the one in the app, shown under **Open the panel** below the address. In the browser, you see it by tapping the warning or the padlock next to the address and opening the certificate details. If it matches, carry on.
4. Under **Pair this browser**, tap **Ask for the code**. The 6-digit code appears on the screen; it's valid for 2 minutes.
5. Type it in **Code from the screen**. If you like, give the device a name so you can recognise it later in the list.
6. Tap **Pair**.

You're in the panel. From then on, that browser goes straight in, without a code.

> [!TIP]
> If a code you didn't ask for appears on the screen, tap **Close** and that code stops working. Someone on your network, even a guest's phone connected to your Wi-Fi, is trying to pair a browser.

## What you can do

| Section | What's there |
| --- | --- |
| Status | Version, temperature, processor, memory, Wi-Fi and how long it's been on |
| Screen and sound | Brightness, turning the screen off or on, text size, and music and alarm volume |
| Screensaver | Whether it appears, after how long, and the weather city |
| Cast | Turning it on or off, who can cast, and stopping what's being received |
| Updates | Whether it's up to date, checking now, and how often it checks by itself. Installing is always confirmed on the screen |
| Devices | The paired browsers, when they were last used, and removing them |
| Latest changes | What was changed from the panel and from which device |
| Restart | With two confirmations in the browser and a 15-second countdown on the screen, with **Cancel** |

What can never be done from the panel: change the Wi-Fi or its password, ADB debugging, root or certificates; install or remove apps; read the system log; use the camera or microphone.

## Safe at home

- It only listens on the home Wi-Fi and rejects anything that doesn't come from home. It doesn't open anything on your router or go through any cloud.
- Everything is encrypted (HTTPS), with this screen's own certificate. Its key is kept in the Android keystore and never leaves the screen.
- Every change shows up briefly on the screen and is logged in **Latest changes**, with the device that made it.
- A browser that isn't used for 90 days has to be paired again.

## If pairing doesn't work

| What happens | What to do |
| --- | --- |
| The code doesn't appear on the screen | Open the **Web panel** app on the screen and tap **Pair**: it shows the code in use or a new one |
| “That's not the code. … tries left.” | Look carefully at the code on the screen and type it again |
| “The code has expired. Ask for another one.” | The 2 minutes are up: tap **Ask for the code** again |
| “Too many tries with that code. Ask for another one.” | Ask for a new code |
| “Wait … seconds before asking for another code.” | Wait as long as it says and ask again |
| “There are already 12 paired devices. Remove one from the screen.” | In the app, under **Paired devices**, remove one you no longer use |

## Remove a device or turn off the panel

- **On the screen**, in the **Web panel** app: under **Paired devices**, tap **Remove** on one or, if there's more than one, **Remove all**.
- **In the browser**: under **Paired devices** on the page, tap **Remove** on the one you want, or **Unpair this browser** at the bottom. That browser will ask for the code again.
- **To turn it off**: tap **Turn off** in the notification or turn off the **On** switch in the app. When it's off, nothing is listening.
- If you think someone has a copy of the certificate, tap **Make a new certificate** in the app. The fingerprint changes and every browser will warn you once more.

## Remove it or add it back

The web panel uninstalls like any app, and you add it back from **Updates → Home apps → Optional**. It's explained in [Remove or reinstall apps](quitar-o-poner-apps.md).

- When you add it back, it's installed turned off: open the app and turn on the **On** switch.
- The screen makes a new certificate: every browser will warn you once more and you'll have to pair them again.
- Updating the panel, on the other hand, doesn't change the certificate, and browsers keep getting in without a code.
