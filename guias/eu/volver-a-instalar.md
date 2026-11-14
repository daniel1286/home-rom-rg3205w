# Instalatu berriro Home

Pantaila berri bezala utzi nahi baduzu, edo zerbait oso gaizki joan eta ez bada abiarazten, Home berriro instala daiteke ordenagailu batetik. Egunean jartzeko ez da behar: nahikoa da [eguneratzea](actualizar.md).

> [!WARNING]
> Home ordenagailutik instalatzeak pantailan dagoen guztia ezabatzen du: aplikazioak, ezarpenak eta datuak.

## Zer behar den

- 64 biteko Windows 10 edo 11 duen ordenagailu bat.
- Home instalatzeko erabili zenuen USB kablea. Rev5 ereduan, barneko konektorerako egokigailuarekin.
- Instalatzailea, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), Home deskargatu eta leiho batean instalatzen duena.

## Nola egiten den

[Instalazio-gidak](../INSTALAR.md) urratsez urrats azaltzen du. Home instalatuta dagoenean, fastboot-en sartzea lehen aldian baino errazagoa da:

- [Recovery modutik](recovery.md): **Reiniciar → Bootloader**.
- Edo [ADB](adb.md) bidez: `adb reboot bootloader`.

## Ez bada abiarazten ezta fastboot-en sartzen ere

EDL bidezko erreskatea geratzen da, prozesadorearen larrialdi modua. Esperientzia pixka bat duenarentzat da: [instalazio-gidan](../INSTALAR.md#11-copia-de-seguridad-y-rescate-por-edl) duzu.
