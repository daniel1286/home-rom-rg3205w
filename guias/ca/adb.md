# Depuració ADB

ADB permet controlar la pantalla des d'un ordinador amb ordres: instal·lar apps, veure el registre, copiar fitxers. Ve desactivat i és només per a qui ho necessiti.

> [!WARNING]
> Amb ADB activat, qui tingui accés a la teva xarxa pot intentar controlar la pantalla. Activa'l només mentre el facis servir i apaga'l en acabar.

## Activar-lo

### A l'assistent

A **Opcions avançades → Depuració (ADB)**. Queda activat per USB i per Wi-Fi, i la teva xarxa queda acceptada per a la depuració sense fil.

### Després, des de Configuració

1. A **Configuració → Informació del dispositiu**, toca set vegades **Número de compilació**. Apareixen les **Opcions per a desenvolupadors**.
2. Entra a **Configuració → Sistema → Opcions per a desenvolupadors**.
3. Activa **Depuració per USB** o **Depuració sense fil**.

La primera vegada que s'hi connecti un ordinador, la pantalla pregunta si l'autoritzes.

## Per Wi-Fi

1. A **Opcions per a desenvolupadors**, entra a **Depuració sense fil**.
2. Toca **Vincula el dispositiu amb un codi de vinculació**.
3. A l'ordinador, escriu l'adreça, el port i el codi que surten a la pantalla:

| Pas | Ordre |
| --- | --- |
| Vincular, només la primera vegada | `adb pair <IP>:<port de vinculació> <codi>` |
| Connectar | `adb connect <IP>:<port>` |

El port per connectar canvia cada vegada que s'activa: mira'l a **Depuració sense fil**.

## Per cable

Cal el mateix cable que per instal·lar Home: al Rev5, amb l'adaptador al connector intern. Ho tens a la [guia d'instal·lació](../INSTALAR.md#2-saber-si-es-rev4-o-rev5-y-conectarlo-al-pc).

> [!IMPORTANT]
> Amb el cable USB de l'ordinador connectat, la pantalla no acaba d'arrencar. Treu-lo abans de reiniciar-la.

## Apagar-lo

A **Opcions per a desenvolupadors**, desactiva **Depuració per USB** i **Depuració sense fil**.
