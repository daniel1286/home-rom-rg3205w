# Control the screen from your PC

With droidVNC-NG you see the screen on your computer and control it with the mouse and keyboard, as if you were touching it. It gets installed if you tick **Control the screen from your PC** in the setup wizard.

## Set a password

At first, droidVNC-NG has a random password you don't know. Set your own:

1. Open **droidVNC-NG** on the screen.
2. Type a password.
3. Note the address it shows: the screen's IP and the port, usually 5900.

It starts by itself every time the screen is switched on.

## Connect from the computer

1. Install a VNC viewer on the computer. There are free ones for Windows, Mac and Linux.
2. Connect to the screen's address, for example `192.168.1.50:5900`.
3. Type the password.

> [!WARNING]
> Anyone on your network who has the password can control the screen. Use a long password and don't share it.

## If it won't connect

- Check that the computer and the screen are on the same network.
- Open droidVNC-NG on the screen and check that it's running.
- If Android asks whether droidVNC-NG can record the screen, accept.
