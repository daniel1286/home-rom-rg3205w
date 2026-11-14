# Root amb Magisk

Amb root, les apps a les quals donis permís poden canviar tot el sistema. Home porta Magisk preparat, però el root ve apagat: només s'encén si el demanes.

> [!CAUTION]
> Una app amb root pot espatllar el sistema o llegir tot el que hi ha a la pantalla. Activa'l només si saps per a què el necessites, i dona permís només a apps de confiança.

## Activar-lo a l'assistent

A **Opcions avançades → Root (Magisk)**, activa **Permet el root amb Magisk**. En aplicar, s'instal·la l'app de Magisk.

A partir d'aquí, cada vegada que una app demana root, Magisk et pregunta abans de donar-l'hi. L'única que el rep sense preguntar és Fully Kiosk, si fas servir el tauler de Home Assistant.

## Activar-lo o apagar-lo després

El root es decideix en engegar la pantalla, segons un ajust. Si no el vas activar a l'assistent, es canvia amb [ADB](adb.md):

| Què vols fer | Ordre |
| --- | --- |
| Activar-lo | `adb shell settings put global home_root 1` |
| Apagar-lo | `adb shell settings put global home_root 0` |

Després, reinicia la pantalla. Amb el root activat, l'app de Magisk s'instal·la sola en arrencar. Amb el root apagat, cap app no el rep; l'app de Magisk es pot desinstal·lar com qualsevol altra.

## Les actualitzacions

Les actualitzacions de Home conserven el root tal com el tinguis: l'ajust no canvia. Magisk va sempre dins de Home i s'actualitza amb cada versió.
