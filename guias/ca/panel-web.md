# Panell web

Amb el panell web veus com està la pantalla i en canvies els ajustos des del navegador del mòbil o de l'ordinador, sense tocar-la. Només funciona dins de casa i ve apagat: només el té qui el tria.

## Encendre'l

- **A l'assistent**, marca **Panell web** a **Què vols instal·lar**. Queda instal·lat i encès.
- **Si has actualitzat des de la 2.0**, s'ofereix a les novetats de la 2.1: **Instal·lar i encendre el panell web**.
- **Si no el vas marcar**, posa'l des d'**Actualitzacions → Apps de Home → Opcionals**, amb **Posa-la**. Es posa apagat.
- **Si ja el tens**, obre l'app **Panell web** i activa **Encès**, a dalt a la dreta.

Mentre està encès hi ha un avís fix, «Panell web encès», amb el botó **Apagar**.

## Emparellar el mòbil o l'ordinador

1. A la pantalla, obre l'app **Panell web**. A **Obrir el panell** surten l'adreça i un codi QR.
2. Escaneja el codi amb el mòbil, o escriu l'adreça tal com surt, amb el `:8443` del final. Si l'escrius sense `https://`, la pantalla et porta sola a la versió segura.
3. La primera vegada, el navegador avisa que el certificat no és d'una autoritat coneguda. És normal: és d'aquesta pantalla. Comprova que la seva empremta (SHA-256) és la de l'app, que surt a **Obrir el panell** sota l'adreça. Al navegador la veus si toques l'avís o el cadenat que hi ha al costat de l'adreça i obres els detalls del certificat. Si coincideix, continua.
4. A **Emparella aquest navegador**, toca **Demanar el codi**. A la pantalla surt el codi de 6 xifres; val 2 minuts.
5. Escriu-lo a **Codi de la pantalla**. Si vols, posa un nom a l'aparell, per reconèixer-lo després a la llista.
6. Toca **Emparellar**.

Ja ets al panell. Les vegades següents aquest navegador hi entra directament, sense codi.

> [!TIP]
> Si a la pantalla surt un codi que no has demanat, toca **Tancar** i aquest codi deixa de valer. Algú de la teva xarxa, també el mòbil d'un convidat connectat a la teva Wi-Fi, està intentant emparellar un navegador.

## Què s'hi pot fer

| Part | Què hi ha |
| --- | --- |
| Estat | Versió, temperatura, processador, memòria, Wi-Fi i temps encesa |
| Pantalla i so | Brillantor, apagar o encendre la pantalla, mida del text i volum de la música i de les alarmes |
| Estalvi de pantalla | Si surt, al cap de quant de temps i la ciutat del temps |
| Projectar | Encendre'l o apagar-lo, qui pot enviar i tallar el que s'està rebent |
| Actualitzacions | Si està al dia, cercar ara i cada quan cerca sola. La instal·lació sempre es confirma a la pantalla |
| Aparells | Els navegadors emparellats, quan es van fer servir per última vegada, i treure'ls |
| Últims canvis | Què s'ha canviat des del panell i des de quin aparell |
| Reiniciar | Amb dues confirmacions al navegador i un compte enrere de 15 segons a la pantalla, amb **Cancel·lar** |

El que no es pot fer mai des del panell: canviar la Wi-Fi o la seva contrasenya, la depuració ADB, el root o els certificats; instal·lar o treure apps; veure el registre del sistema; fer servir la càmera o el micròfon.

## Segur dins de casa

- Només escolta a la Wi-Fi de casa i rebutja el que no en vingui. No obre res al router ni passa per cap núvol.
- Tot va xifrat (HTTPS), amb un certificat propi d'aquesta pantalla. La seva clau es desa al magatzem de claus d'Android i no en surt mai.
- Cada canvi surt un moment a la pantalla i queda apuntat a **Últims canvis**, amb l'aparell que l'ha fet.
- Un navegador que no es fa servir en 90 dies s'ha de tornar a emparellar.

## Si no et deixa emparellar

| El que passa | Què has de fer |
| --- | --- |
| No surt el codi a la pantalla | Obre l'app **Panell web** a la pantalla i toca **Emparellar**: surt el codi que està en ús o un de nou |
| «Aquest no és el codi. Queden … intents.» | Mira bé el codi de la pantalla i torna'l a escriure |
| «El codi ha caducat. Demana'n un altre.» | Han passat els 2 minuts: torna a tocar **Demanar el codi** |
| «Massa intents amb aquest codi. Demana'n un altre.» | Demana un codi nou |
| «Espera … segons abans de demanar un altre codi.» | Espera el que diu i torna'l a demanar |
| «Ja hi ha 12 aparells emparellats. Treu-ne algun des de la pantalla.» | A l'app, a **Aparells emparellats**, treu-ne algun que ja no facis servir |

## Treure un aparell o apagar el panell

- **A la pantalla**, a l'app **Panell web**: a **Aparells emparellats**, toca **Treure** en un o, si n'hi ha més d'un, **Treure'ls tots**.
- **Al navegador**: a **Aparells emparellats** de la pàgina, toca **Treure** al que vulguis, o a baix **Desemparellar aquest navegador**. Aquest navegador torna a demanar el codi.
- **Apagar-lo**: toca **Apagar** a l'avís o desactiva **Encès** a l'app. Apagat, no hi ha res escoltant.
- Si creus que algú té una còpia del certificat, toca **Fer un certificat nou** a l'app. L'empremta canvia i cada navegador avisarà un cop més.

## Treure'l o tornar-lo a posar

El panell web es desinstal·la com qualsevol app, i es torna a posar des d'**Actualitzacions → Apps de Home → Opcionals**. Ho tens a [Treure o tornar a posar apps](quitar-o-poner-apps.md).

- En tornar-lo a posar s'instal·la apagat: obre l'app i activa **Encès**.
- La pantalla fa un altre certificat: cada navegador avisarà un cop més i caldrà tornar-los a emparellar.
- En canvi, en actualitzar el panell el certificat no canvia i els navegadors continuen entrant sense codi.
