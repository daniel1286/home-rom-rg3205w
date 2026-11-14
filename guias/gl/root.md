# Root con Magisk

Con root, as apps ás que deas permiso poden cambiar todo o sistema. Home leva Magisk preparado, pero o root vén apagado: só se acende se o pides.

> [!CAUTION]
> Unha app con root pode estragar o sistema ou ler todo o que hai na pantalla. Actívao só se sabes para que o precisas, e dálle permiso só a apps de confianza.

## Activalo no asistente

En **Opcións avanzadas → Root (Magisk)**, activa **Permitir root con Magisk**. Ao aplicar, instálase a app de Magisk.

A partir de aí, cada vez que unha app pide root, Magisk pregúntache antes de darllo. A única que o recibe sen preguntar é Fully Kiosk, se usas o panel de Home Assistant.

## Activalo ou apagalo despois

O root decídese ao acender a pantalla, segundo un axuste. Se non o activaches no asistente, cámbiase con [ADB](adb.md):

| Para | Orde |
| --- | --- |
| Activalo | `adb shell settings put global home_root 1` |
| Apagalo | `adb shell settings put global home_root 0` |

Despois, reinicia a pantalla. Co root activado, a app de Magisk instálase soa ao arrincar. Co root apagado, ningunha app o recibe; a app de Magisk pódese desinstalar coma calquera outra.

## As actualizacións

As actualizacións de Home conservan o root como o teñas: o axuste non cambia. Magisk vai sempre dentro de Home e ponse ao día con cada versión.
