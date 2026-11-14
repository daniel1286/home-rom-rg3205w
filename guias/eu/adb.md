# ADB arazketa

ADBri esker, pantaila ordenagailu batetik kudea dezakezu aginduen bidez: aplikazioak instalatu, erregistroa ikusi, fitxategiak kopiatu. Desaktibatuta dator, eta behar duenarentzat bakarrik da.

> [!WARNING]
> ADB aktibatuta, zure sarera sarbidea duen edonor saia daiteke pantaila kontrolatzen. Aktibatu erabiltzen duzun bitartean bakarrik, eta itzali amaitzean.

## Nola aktibatu

### Laguntzailean

**Aukera aurreratuak → Arazketa (ADB)** atalean. USB bidez eta Wi-Fi bidez aktibatuta geratzen da, eta zure sarea hari gabeko arazketarako onartuta geratzen da.

### Gero, Ezarpenetatik

1. **Ezarpenak → Gailuari buruz** atalean, sakatu zazpi aldiz **Konpilazio-zenbakia**. **Garatzaileentzako aukerak** agertzen dira.
2. Sartu **Ezarpenak → Sistema → Garatzaileentzako aukerak** atalean.
3. Aktibatu **USB bidezko arazketa** edo **Hari gabeko arazketa**.

Ordenagailu bat lehen aldiz konektatzen denean, pantailak baimena ematen diozun galdetzen du.

## Wi-Fi bidez

1. **Garatzaileentzako aukerak** atalean, sartu **Hari gabeko arazketa** aukeran.
2. Sakatu **Parekatu gailua parekatze-kodearekin**.
3. Ordenagailuan, idatzi pantailan agertzen diren helbidea, ataka eta kodea:

| Urratsa | Agindua |
| --- | --- |
| Parekatu, lehen aldian bakarrik | `adb pair <IP>:<parekatze-ataka> <kodea>` |
| Konektatu | `adb connect <IP>:<ataka>` |

Konektatzeko ataka aktibatzen den bakoitzean aldatzen da: begiratu **Hari gabeko arazketa** atalean.

## Kable bidez

Home instalatzeko erabilitako kable bera behar da: Rev5 ereduan, barneko konektorerako egokigailuarekin. [Instalazio-gidan](../INSTALAR.md#2-saber-si-es-rev4-o-rev5-y-conectarlo-al-pc) duzu.

> [!IMPORTANT]
> Ordenagailuaren USB kablea konektatuta badago, pantaila ez da guztiz abiarazten. Kendu kablea berrabiarazi aurretik.

## Nola itzali

**Garatzaileentzako aukerak** atalean, desaktibatu **USB bidezko arazketa** eta **Hari gabeko arazketa**.
