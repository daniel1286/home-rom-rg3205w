# The recovery

The recovery is a small separate system that starts instead of Home to install updates. Home comes with TWRP in its own design, in Spanish. You don't normally need to go into it: Updates uses it by itself.

## When it shows up

- **When updating**: after **Install and restart**, the screen starts in the recovery, installs the version while showing its progress and goes back to Home by itself.
- **If you go into it yourself**, with [ADB](adb.md): `adb reboot recovery`.

## What you can do

| To | Tap |
| --- | --- |
| Go back to Home | **Reiniciar → Sistema** |
| Go to fastboot, to reinstall Home | **Reiniciar → Bootloader** |
| Power off | **Reiniciar → Apagar** |

> [!CAUTION]
> In the recovery you can wipe everything. If you don't know what an option does, don't touch it and go back to Home with **Reiniciar → Sistema**.

## If it stays in the recovery

If the recovery reports an error while installing, tap **Reiniciar → Sistema**. At startup, Updates tells you what happened: see [If an update won't install](si-no-se-instala.md). If the screen no longer starts, [reinstall Home](volver-a-instalar.md).
