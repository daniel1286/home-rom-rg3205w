# Tornar a instal·lar Home

Si vols deixar la pantalla com nova, o si alguna cosa ha anat tan malament que no arrenca, pots tornar a instal·lar Home des d'un ordinador. Per posar-te al dia no cal: n'hi ha prou d'[actualitzar](actualizar.md).

> [!WARNING]
> Instal·lar Home des de l'ordinador esborra tot el que hi ha a la pantalla: apps, ajustos i dades.

## El que cal

- Un ordinador amb Windows 10 o 11 de 64 bits.
- El cable USB amb què vas instal·lar Home. Al Rev5, amb l'adaptador al connector intern.
- L'instal·lador, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), que baixa Home i l'instal·la amb una finestra, sense ordres.

## Com es fa

La [guia d'instal·lació](../INSTALAR.md) ho explica pas a pas. Amb Home ja instal·lat, entrar a fastboot és més fàcil que la primera vegada:

- Des del [recovery](recovery.md): **Reiniciar → Bootloader**.
- O amb [ADB](adb.md): `adb reboot bootloader`.

## Si no arrenca ni entra a fastboot

Queda el rescat per EDL, el mode d'emergència del processador. És per a qui té una mica d'experiència: ho tens a la [guia d'instal·lació](../INSTALAR.md#11-copia-de-seguridad-y-rescate-por-edl).
