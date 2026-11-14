# Tauler de Home Assistant

La pantalla pot mostrar el teu tauler de Home Assistant a pantalla completa i obrir-lo sola cada vegada que s'engega. Ho fa Fully Kiosk, que l'assistent instal·la si marques **Tauler de Home Assistant**.

## Com queda configurat

A l'assistent:

1. Marca **Tauler de Home Assistant** a **Què vols instal·lar**.
2. Al pas **Home Assistant**, tria el teu de la llista o escriu-ne l'adreça, per exemple `homeassistant.local:8123`.

En aplicar, l'assistent baixa Fully Kiosk del seu web, comprova que és l'autèntic, hi posa l'adreça del teu Home Assistant i el deixa com a pantalla d'inici. En acabar, ja surt el teu tauler.

## Si el teu Home Assistant fa servir https amb un certificat propi

Afegeix el certificat a l'assistent, a **Opcions avançades → Certificats propis** (un fitxer .crt o .pem), perquè el tauler l'accepti. Ho tens a [IP fixa, MAC i certificats](red-y-certificados.md).

## Canviar l'adreça

L'adreça es canvia a la configuració de Fully Kiosk: llisca des de la vora esquerra per obrir-ne el menú, entra a la configuració i canvia la pàgina d'inici (**Start URL**).

Algunes opcions de Fully són de pagament; per mostrar el tauler no calen.

## Amb l'estalvi de pantalla

Si vols que surti l'estalvi de pantalla de Home amb el tauler:

- A Fully, apaga l'opció per mantenir la pantalla encesa (**Keep Screen On**). Si no, l'estalvi de pantalla no sortirà mai.
- No facis servir alhora l'estalvi de pantalla de Fully.

Més informació a [L'estalvi de pantalla](salvapantallas.md).

## Tornar a l'inici de sempre

Si deixes de fer servir el tauler, canvia la pantalla d'inici: llisca des de dalt, obre **Configuració** amb la roda dentada i ves a **Aplicacions → Aplicacions predeterminades → Aplicació d'inici**. Tria **Trebuchet**, l'inici d'Android.
