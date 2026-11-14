# Home Assistant dashboard

The screen can show your Home Assistant dashboard full screen and open it by itself every time it's switched on. Fully Kiosk does this, and the setup wizard installs it if you tick **Home Assistant dashboard**.

## How it's set up

In the setup wizard:

1. Tick **Home Assistant dashboard** in **What to install**.
2. In the **Home Assistant** step, choose yours from the list or type its address, for example `homeassistant.local:8123`.

When you apply, the wizard downloads Fully Kiosk from its website, checks that it's the genuine one, gives it your Home Assistant's address and sets it as the home screen. Once it's done, your dashboard shows up.

## If your Home Assistant uses https with its own certificate

Add the certificate in the setup wizard, under **Advanced options → Own certificates** (a .crt or .pem file), so the dashboard accepts it. See [Static IP, MAC and certificates](red-y-certificados.md).

## Changing the address

You change the address in Fully Kiosk's settings: swipe in from the left edge to open its menu, go to its settings and change the start page (**Start URL**).

Some of Fully's options are paid; you don't need them to show the dashboard.

## With the screensaver

If you want Home's screensaver to come on with the dashboard:

- In Fully, turn off its option that keeps the screen on (**Keep Screen On**). Otherwise the screensaver never comes on.
- Don't use Fully's own screensaver at the same time.

More in [The screensaver](salvapantallas.md).

## Going back to the usual home screen

If you stop using the dashboard, change the home screen: swipe down from the top, open **Settings** with the gear and go to **Apps → Default apps → Home app**. Choose **Trebuchet**, the Android home screen.
