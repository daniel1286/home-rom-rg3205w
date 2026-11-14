# Root Magisk-ekin

Root-arekin, baimena ematen diezun aplikazioek sistema osoa alda dezakete. Home-k Magisk prest dakar, baina root-a itzalita dator: zuk eskatzen baduzu bakarrik pizten da.

> [!CAUTION]
> Root-a duen aplikazio batek sistema hondatu edo pantailan dagoen guztia irakur dezake. Aktibatu zertarako behar duzun badakizu bakarrik, eta eman baimena konfiantzazko aplikazioei bakarrik.

## Laguntzailean aktibatu

**Aukera aurreratuak → Root (Magisk)** atalean, aktibatu **Baimendu root Magisk-ekin**. Aplikatzean, Magisk aplikazioa instalatzen da.

Hortik aurrera, aplikazio batek root-a eskatzen duen bakoitzean, Magisk-ek galdetu egiten dizu eman aurretik. Galdetu gabe jasotzen duen bakarra Fully Kiosk da, Home Assistant panela erabiltzen baduzu.

## Gero aktibatu edo itzali

Root-a pantaila piztean erabakitzen da, ezarpen baten arabera. Laguntzailean aktibatu ez bazenuen, [ADB](adb.md) bidez aldatzen da:

| Zertarako | Agindua |
| --- | --- |
| Aktibatzeko | `adb shell settings put global home_root 1` |
| Itzaltzeko | `adb shell settings put global home_root 0` |

Ondoren, berrabiarazi pantaila. Root-a aktibatuta badago, Magisk aplikazioa bere kasa instalatzen da abiaraztean. Root-a itzalita badago, aplikazio batek ere ez du jasotzen; Magisk aplikazioa beste edozein bezala desinstala daiteke.

## Eguneratzeak

Home-ren eguneratzeek root-a daukazun bezala uzten dute: ezarpena ez da aldatzen. Magisk beti doa Home-ren barruan, eta bertsio bakoitzarekin eguneratzen da.
