# El recovery

El recovery és un petit sistema a part que arrenca en lloc de Home per instal·lar actualitzacions. Home porta TWRP amb un disseny propi, en castellà. Normalment no cal entrar-hi: Actualitzacions ja el fa servir pel seu compte.

## Quan surt

- **En actualitzar**: després de tocar **Instal·la i reinicia**, la pantalla arrenca al recovery, instal·la la versió mostrant com va i torna sola a Home.
- **Si hi entres tu**, amb [ADB](adb.md): `adb reboot recovery`.

## Què s'hi pot fer

| Què vols fer | Toca |
| --- | --- |
| Tornar a Home | **Reiniciar → Sistema** |
| Anar a fastboot, per tornar a instal·lar Home | **Reiniciar → Bootloader** |
| Apagar | **Reiniciar → Apagar** |

> [!CAUTION]
> Al recovery es pot esborrar tot. Si no saps què fa una opció, no la toquis i torna a Home amb **Reiniciar → Sistema**.

## Si es queda al recovery

Si el recovery avisa d'un error en instal·lar, toca **Reiniciar → Sistema**. En arrencar, Actualitzacions diu què ha passat: ho tens a [Si una actualització no s'instal·la](si-no-se-instala.md). Si la pantalla ja no arrenca, [torna a instal·lar Home](volver-a-instalar.md).
