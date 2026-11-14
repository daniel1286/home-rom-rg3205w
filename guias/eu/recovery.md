# Recovery modua

Recovery modua sistema txiki bat da, Home-ren ordez abiarazten dena eguneratzeak instalatzeko. Home-k TWRP darama, bere diseinuarekin eta gaztelaniaz. Normalean ez da bertan sartu behar: Eguneratzeak aplikazioak berak erabiltzen du.

## Noiz agertzen den

- **Eguneratzean**: **Instalatu eta berrabiarazi** sakatu ondoren, pantaila recovery moduan abiarazten da, bertsioa instalatzen du nola doan erakutsiz, eta bere kasa itzultzen da Home-ra.
- **Zu sartzen bazara**, [ADB](adb.md) bidez: `adb reboot recovery`.

## Zer egin daitekeen

| Zertarako | Ukitu |
| --- | --- |
| Home-ra itzuli | **Reiniciar → Sistema** |
| Fastboot-era joan, Home berriro instalatzeko | **Reiniciar → Bootloader** |
| Itzali | **Reiniciar → Apagar** |

> [!CAUTION]
> Recovery moduan dena ezaba daiteke. Aukera batek zer egiten duen ez badakizu, ez ukitu, eta itzuli Home-ra **Reiniciar → Sistema** aukerarekin.

## Recovery moduan geratzen bada

Recovery moduak instalatzean errore bat egon dela abisatzen badu, ukitu **Reiniciar → Sistema**. Abiaraztean, Eguneratzeak aplikazioak zer gertatu den esaten du: [Eguneratze bat instalatzen ez bada](si-no-se-instala.md) gidan duzu. Pantaila jada abiarazten ez bada, [instalatu berriro Home](volver-a-instalar.md).
