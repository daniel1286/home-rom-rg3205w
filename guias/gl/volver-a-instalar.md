# Volver instalar Home

Se queres deixar a pantalla coma nova, ou se algo foi tan mal que non arrinca, pódese volver instalar Home desde un ordenador. Para poñerte ao día non fai falta: abonda con [actualizar](actualizar.md).

> [!WARNING]
> Instalar Home desde o ordenador borra todo o que hai na pantalla: apps, axustes e datos.

## O que fai falta

- Un ordenador con Windows 10 ou 11 de 64 bits.
- O cable USB co que instalaches Home. No Rev5, co adaptador ao conector interno.
- O instalador, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), que descarga Home e o instala desde unha xanela.

## Como se fai

A [guía de instalación](../INSTALAR.md) explícao paso a paso. Con Home xa instalado, entrar en fastboot é máis doado que a primeira vez:

- Desde o [recovery](recovery.md): **Reiniciar → Bootloader**.
- Ou con [ADB](adb.md): `adb reboot bootloader`.

## Se non arrinca nin entra en fastboot

Queda o rescate por EDL, o modo de emerxencia do procesador. É para quen ten algo de experiencia: tes isto na [guía de instalación](../INSTALAR.md#11-copia-de-seguridad-y-rescate-por-edl).
