# Primers passos

La primera vegada que s'engega, Home obre un assistent que deixa la pantalla a punt en uns minuts. Aquí tens què demana cada pas, què et convé triar i on es canvia després.

## Abans de començar

- La pantalla ha d'estar endollada. No té bateria: si la desendolles, s'apaga.
- Tingues a mà la contrasenya de la teva Wi-Fi.
- Si la faràs servir de tauler de Home Assistant o d'altaveu de casa, deixa engegat el teu servidor: l'assistent el busca a la xarxa.

A tots els passos tens **Enrere** a baix a l'esquerra i **Següent** a baix a la dreta. Gairebé res no s'aplica fins al final, així que pots anar endavant i enrere sense por.

## Idioma, regió i text

**Hola.** Tria l'idioma: l'assistent canvia a l'instant i la pantalla es queda en aquest idioma. Després toca **Comença**.

**Regió i hora.** El fus horari (Península i Balears, Canàries, Ceuta i Melilla o Portugal), si l'hora es pren d'Internet i si la vols en format de 24 hores.

**Mida del text.** Normal, Gran o Molt gran. Quan en toques una, tot l'assistent canvia perquè vegis com queda. Val per a totes les apps de Home, l'estalvi de pantalla inclòs.

## Wi-Fi i nom

**Wi-Fi.** Tria la teva xarxa, escriu la contrasenya i toca **Connecta**. Si no surt, toca **Torna a cercar**. Pots saltar-te aquest pas, però sense connexió no es pot instal·lar el tauler de Home Assistant ni posar l'hora automàtica.

**Nom.** Com es dirà la pantalla a la teva xarxa, per Bluetooth i quan hi projectis. Si en tens més d'una a casa, posa-li el nom de l'habitació: Menjador, Cuina, Entrada…

## Què vols instal·lar

Marca el que faràs servir. El que no marquis no s'instal·la i no ocupa lloc.

| Opció | Per a què |
| --- | --- |
| Tauler de Home Assistant | El teu tauler a pantalla completa, que s'obre sol en engegar. El mostra Fully Kiosk |
| Altaveu de casa | Que la pantalla soni alhora que la resta d'altaveus, amb el teu servidor de música |
| Controlar la pantalla des del PC | Veure i tocar la pantalla des d'un altre ordinador |
| F-Droid | Botiga d'apps lliures i gratuïtes |
| Aurora Store | Apps de Google Play sense compte de Google |
| Ajuda | Aquesta guia i, si alguna cosa falla, explicar-ho i veure la resposta |
| Monitor | Veure la pantalla per dins: processador, memòria, temperatures i xarxa |

Ajuda, F-Droid i Aurora Store ja surten marcades; Monitor, no. Ajuda i Monitor es desinstal·len després com qualsevol app.

Si marques el tauler o l'altaveu, surten dos passos més:

- **Home Assistant.** L'assistent el busca a la teva xarxa. Si no el troba, escriu-ne l'adreça, per exemple `homeassistant.local:8123`. Si el teu Home Assistant fa servir un certificat propi, afegeix-lo a **Opcions avançades**.
- **Altaveu de casa.** Tria el teu servidor de música de la llista o escriu-ne l'adreça.

## Projectar i pantalla en repòs

**Projectar.** Deixa que aquesta pantalla rebi la imatge i el so de l'iPhone, el Mac, l'ordinador amb Windows o el mòbil Android. Tria qui hi pot enviar:

- **Amb codi la primera vegada** (ve així): la primera vegada, els aparells d'Apple escriuen un codi de quatre xifres que surt a la pantalla, i els altres hi demanen permís.
- **Qualsevol de casa**: qualsevol aparell connectat a la teva xarxa hi envia sense preguntar.
- **Amb contrasenya**: els aparells d'Apple fan servir una contrasenya que tries tu; els altres demanen permís la primera vegada.

Ve activat. Si no el faràs servir, desactiva **Rebre en aquesta pantalla** i Projectar es treu; el pots posar quan vulguis des d'**Actualitzacions → Apps de Home**, a **Opcionals**.

**Pantalla en repòs.** Què passa quan ningú no la toca:

- **Surt l'estalvi de pantalla**: l'hora, el temps i els teus fons. Tria al cap de quanta estona surt i la teva ciutat, que és d'on surten el temps, la pluja i els avions.
- **Es queda el que hi hagi** (ve així): es queda al davant el tauler o l'app que tinguis oberta.

El despertador sona en tots dos casos.

**Pantalla.** La brillantor i, si no fas servir l'estalvi de pantalla, al cap de quant s'apaga. Si la fas servir de tauler o de rellotge, tria **Mai**.

**Navegació.** Com et mous per la pantalla: amb **Gestos** (ve així) o amb **Botons**, sempre a la vista a baix. Ho tens explicat a [Moure't per Home](moverte-por-home.md).

## Privadesa i opcions avançades

**Privadesa.** Si es poden fer servir el micròfon i la càmera. La càmera ve desactivada.

**Ajuda a millorar Home.** Si vols, la pantalla explica un cop al dia com està configurada i si les actualitzacions surten bé. Ve apagat: només s'envia si l'actives. El pas diu què s'envia i què no s'envia mai.

**Opcions avançades.** IP fixa, adreça MAC, certificats propis, depuració ADB i root. Si no et calen, toca **Continua**. Els tens explicats a la secció [Avançat](README.md#avançat).

## Resum

Repassa-ho tot. Toca una línia per canviar-la i, quan estigui bé, toca **Aplica**.

La pantalla va dient el que fa. No l'apaguis ni la desendollis mentrestant. Si alguna cosa no surt bé, ho mostra a dalt i et deixa tornar al resum; la resta ja queda feta. En acabar, toca **Comença a fer-la servir**. No cal reiniciar.

## On es canvia després

| Què | On |
| --- | --- |
| Idioma | Configuració → Sistema → Idiomes |
| Mida del text | Configuració → Pantalla → Mida de la lletra |
| Wi-Fi | Configuració → Xarxa i Internet |
| Nom | Configuració → Informació del dispositiu → Nom del dispositiu |
| Projectar | App Projectar |
| Estalvi de pantalla | App Estalvi de pantalla → En deixar d'usar-la |
| Brillantor i apagada | Configuració → Pantalla |
| Gestos o botons | Configuració → Sistema → Gestos → Navegació del sistema |
| Ajuda a millorar Home | App Actualitzacions → Configuració |
| Depuració ADB | Configuració → Sistema → Opcions per a desenvolupadors |
