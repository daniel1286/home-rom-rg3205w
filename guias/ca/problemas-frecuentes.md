# Problemes freqüents

El que passa més sovint i com s'arregla. Si el teu cas no és aquí o no s'arregla, [explica-ho](contar-un-problema.md) i veuràs la resposta a la mateixa pantalla.

## Pantalla

### No surt l'estalvi de pantalla

Passa per una d'aquestes dues coses:

1. A l'app **Estalvi de pantalla**, **En deixar d'usar-la** està en **Es queda el que hi hagi**. Tria **Surt l'estalvi de pantalla**.
2. Una app manté la pantalla encesa. A Fully Kiosk, apaga l'opció **Keep Screen On**.

Més informació a [L'estalvi de pantalla](salvapantallas.md).

### Es queda en negre en reiniciar

Amb el cable USB de l'ordinador connectat, la pantalla no acaba d'arrencar. Treu el cable, desendolla-la del corrent i torna-la a endollar.

### No surten els botons Enrere, Inici i Recents

No és cap error: Home ve amb la navegació amb gestos. Si prefereixes els botons, ves a **Configuració → Sistema → Gestos → Navegació del sistema** i tria **Navegació amb 3 botons**. Els gestos estan explicats a [Moure't per Home](moverte-por-home.md).

### El botó d'engegada no fa res

Si el prems un moment, s'apaga la pantalla; si el mantens premut, s'obre el menú per apagar o reiniciar. Si fas servir Fully Kiosk, mira que no hi tinguis activada l'opció que desactiva el botó d'engegada.

## Projectar

### L'iPhone o l'ordinador no veuen la pantalla

- Comprova que tots dos són a la mateixa xarxa Wi-Fi. Les xarxes de convidats del router no solen deixar que els aparells es vegin.
- A l'app **Projectar**, mira que estigui activat i que a **Des d'on** hi hagi encès el que fas servir.
- Amb **Només so** activat, Windows i Android no veuen la pantalla: només serveixen per duplicar-la.

### Es veu en negre

Les pel·lícules i sèries de pagament no es poden enviar a una altra pantalla per la seva protecció contra còpia. La resta es veu amb normalitat.

### Es talla o va a salts

La imatge va per la Wi-Fi. Acosta la pantalla o l'aparell al router i, si pots, fes servir la xarxa de 5 GHz. A **Projectar → Qualitat**, **Com la pantalla** demana menys a la xarxa que **Alta (1080p)**.

## So i Bluetooth

### L'altaveu Bluetooth es desconnecta

A **Configuració → Dispositius connectats**, toca l'altaveu, tria **Oblida** i torna'l a vincular. Tingues-lo a prop de la pantalla mentre ho fas. Les trucades no van per Bluetooth: un auricular amb micròfon només sona.

### No sona alhora que la resta de la casa

Obre l'app **Snapcast** i comprova que està connectada al teu servidor de música. Si el servidor no veu la pantalla, posa-li nom des del mateix servidor. Ho tens a [Altaveu de casa](altavoz-de-casa.md).

## Wi-Fi i hora

### No surt cap xarxa Wi-Fi

Toca **Torna a cercar**. Si continua sense sortir-ne cap, reinicia la pantalla mantenint premut el botó d'engegada.

### L'hora no és la bona

La pantalla no té pila per al rellotge: pren l'hora d'Internet. A **Configuració → Sistema → Data i hora**, comprova que l'hora automàtica està activada i que la zona horària és la teva.

## Actualitzacions

### L'actualització no s'instal·la

L'app **Actualitzacions** diu per què. El més habitual:

- **Treu el cable USB**: amb el cable de l'ordinador connectat no acaba d'arrencar.
- **No hi ha espai**: cal el doble del que ocupa la versió. Allibera espai i torna-ho a provar.
- **S'ha tallat la connexió**: el que s'ha baixat s'aprofita; quan ho tornis a provar, continua on s'havia quedat.

Cada avís està explicat a [Si una actualització no s'instal·la](si-no-se-instala.md). Les teves apps, ajustos i dades no es toquen.

### No avisa de les versions noves

A **Actualitzacions → Configuració**, mira **Cerca automàtica**: si està en **Mai, només a mà**, no avisa. Pots cercar quan vulguis amb **Cerca ara**.

## Tauler i apps

### El tauler no s'obre en engegar

Fully Kiosk ha de ser l'app d'inici. Ves a **Configuració → Aplicacions → Aplicacions predeterminades → Aplicació d'inici** i tria **Fully Kiosk Browser**. Si s'obre però surt en blanc, revisa a Fully l'adreça del teu Home Assistant.
