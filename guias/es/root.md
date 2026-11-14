# Root con Magisk

Con root, las apps a las que des permiso pueden cambiar todo el sistema. Home lleva Magisk preparado, pero el root viene apagado: solo se enciende si lo pides.

> [!CAUTION]
> Una app con root puede romper el sistema o leer todo lo que hay en la pantalla. Actívalo solo si sabes para qué lo necesitas, y da permiso solo a apps de confianza.

## Activarlo en el asistente

En **Opciones avanzadas → Root (Magisk)**, activa **Permitir root con Magisk**. Al aplicar, se instala la app de Magisk.

A partir de ahí, cada vez que una app pide root, Magisk te pregunta antes de dárselo. La única que lo recibe sin preguntar es Fully Kiosk, si usas el panel de Home Assistant.

## Activarlo o apagarlo después

El root se decide al encender la pantalla, según un ajuste. Si no lo activaste en el asistente, se cambia con [ADB](adb.md):

| Para | Orden |
| --- | --- |
| Activarlo | `adb shell settings put global home_root 1` |
| Apagarlo | `adb shell settings put global home_root 0` |

Después, reinicia la pantalla. Con el root activado, la app de Magisk se instala sola al arrancar. Con el root apagado, ninguna app lo recibe; la app de Magisk se puede desinstalar como cualquier otra.

## Las actualizaciones

Las actualizaciones de Home conservan el root como lo tengas: el ajuste no cambia. Magisk va siempre dentro de Home y se pone al día con cada versión.
