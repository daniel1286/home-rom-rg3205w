# Volver a instalar Home

Si quieres dejar la pantalla como nueva, o si algo ha ido tan mal que no arranca, se puede volver a instalar Home desde un ordenador. Para ponerte al día no hace falta: basta con [actualizar](actualizar.md).

> [!WARNING]
> Instalar Home desde el ordenador borra todo lo que hay en la pantalla: apps, ajustes y datos.

## Lo que hace falta

- Un ordenador con Windows 10 u 11 de 64 bits.
- El cable USB con el que instalaste Home. En el Rev5, con el adaptador al conector interno.
- El instalador, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), que baja Home y lo instala con ventana.

## Cómo se hace

La [guía de instalación](../INSTALAR.md) lo explica paso a paso. Con Home ya instalado, entrar en fastboot es más fácil que la primera vez:

- Desde el [recovery](recovery.md): **Reiniciar → Bootloader**.
- O con [ADB](adb.md): `adb reboot bootloader`.

## Si no arranca ni entra en fastboot

Queda el rescate por EDL, el modo de emergencia del procesador. Es para quien tiene algo de experiencia: lo tienes en la [guía de instalación](../INSTALAR.md#11-copia-de-seguridad-y-rescate-por-edl).
