# El recovery

El recovery es un pequeño sistema aparte que arranca en lugar de Home para instalar actualizaciones. Home lleva TWRP con su propio diseño. Normalmente no hace falta entrar: Actualizaciones lo usa sola.

## Cuándo sale

- **Al actualizar**: tras **Instalar y reiniciar**, la pantalla arranca en el recovery, instala la versión enseñando cómo va y vuelve sola a Home.
- **Si entras tú**, con [ADB](adb.md): `adb reboot recovery`.

## Qué se puede hacer

| Para | Toca |
| --- | --- |
| Volver a Home | **Reiniciar → Sistema** |
| Ir a fastboot, para volver a instalar Home | **Reiniciar → Bootloader** |
| Apagar | **Reiniciar → Apagar** |

> [!CAUTION]
> En el recovery se puede borrar todo. Si no sabes qué hace una opción, no la toques y vuelve a Home con **Reiniciar → Sistema**.

## Si se queda en el recovery

Si el recovery avisa de un error al instalar, toca **Reiniciar → Sistema**. Al arrancar, Actualizaciones dice qué ha pasado: lo tienes en [Si una actualización no se instala](si-no-se-instala.md). Si la pantalla ya no arranca, [vuelve a instalar Home](volver-a-instalar.md).
