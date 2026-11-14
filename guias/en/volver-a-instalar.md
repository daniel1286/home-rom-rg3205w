# Reinstall Home

If you want to leave the screen as good as new, or if something has gone so wrong that it won't start, you can reinstall Home from a computer. You don't need to do this to get up to date: just [update](actualizar.md).

> [!WARNING]
> Installing Home from the computer wipes everything on the screen: apps, settings and data.

## What you need

- A computer with 64-bit Windows 10 or 11.
- The USB cable you used to install Home. On the Rev5, with the adapter to the internal connector.
- The installer, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), which downloads Home and installs it with a window.

## How to do it

The [installation guide](../INSTALL.md) explains it step by step. With Home already installed, getting into fastboot is easier than the first time:

- From the [recovery](recovery.md): **Reiniciar → Bootloader**.
- Or with [ADB](adb.md): `adb reboot bootloader`.

## If it won't start or get into fastboot

There's still the EDL rescue, the processor's emergency mode. It's for people with some experience: it's in the [installation guide](../INSTALL.md#11-backup-and-rescue-over-edl).
