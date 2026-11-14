# Primeiros pasos

A primeira vez que se acende, Home abre un asistente que deixa a pantalla lista nuns minutos. Aquí tes que pide cada paso, que convén escoller e onde se cambia despois.

## Antes de comezar

- A pantalla ten que estar enchufada. Non ten batería: se se desenchufa, apágase.
- Ten a man o contrasinal da túa wifi.
- Se a vas usar como panel de Home Assistant ou como altofalante da casa, deixa acendido o teu servidor: o asistente búscao na rede.

En todos os pasos tes **Atrás** abaixo á esquerda e **Seguinte** abaixo á dereita. Case nada se aplica ata o final, así que podes ir e volver sen medo.

## Idioma, rexión e texto

**Ola.** Escolle o idioma: o asistente cambia ao momento e a pantalla queda nese idioma. Despois toca **Comezar**.

**Rexión e hora.** O fuso horario (Península e Baleares, Canarias, Ceuta e Melilla ou Portugal), se a hora se colle de Internet e se a queres en formato de 24 horas.

**Tamaño do texto.** Normal, Grande ou Moi grande. Ao tocar un, todo o asistente cambia para que vexas como queda. Vale para todas as apps de Home, o protector de pantalla incluído.

## Wifi e nome

**Wifi.** Escolle a túa rede, escribe o contrasinal e toca **Conectar**. Se non aparece, toca **Buscar de novo**. Podes saltar este paso, pero sen conexión non se pode instalar o panel de Home Assistant nin poñer a hora automática.

**Nome.** Como se chamará a pantalla na túa rede, por Bluetooth e ao proxectar. Se tes máis dunha na casa, ponlle o nome da habitación: Salón, Cociña, Entrada…

## Que queres instalar

Marca o que vas usar. O que non marques non se instala e non ocupa sitio.

| Opción | Para que |
| --- | --- |
| Panel de Home Assistant | O teu panel a pantalla completa, que se abre só ao acender. Amósao Fully Kiosk |
| Altofalante da casa | Que a pantalla soe á vez que o resto de altofalantes, co teu servidor de música |
| Manexar a pantalla desde o PC | Ver e tocar a pantalla desde outro ordenador |
| F-Droid | Tenda de apps libres e de balde |
| Aurora Store | Apps de Google Play sen conta de Google |
| Axuda | Esta guía e, se algo falla, contalo e ver a resposta |
| Monitor | Ver a pantalla por dentro: procesador, memoria, temperaturas e rede |

Axuda, F-Droid e Aurora Store veñen marcadas; Monitor, non. Axuda e Monitor pódense desinstalar despois coma calquera app.

Se marcas o panel ou o altofalante, aparecen dous pasos máis:

- **Home Assistant.** O asistente búscao na túa rede. Se non o atopa, escribe o enderezo, por exemplo `homeassistant.local:8123`. Se o teu Home Assistant usa un certificado propio, engádeo en **Opcións avanzadas**.
- **Altofalante da casa.** Escolle o teu servidor de música da lista ou escribe o seu enderezo.

## Proxectar e pantalla en repouso

**Proxectar.** Permite que esta pantalla reciba a imaxe e o son do iPhone, do Mac, do ordenador con Windows ou do móbil Android. Escolle quen pode enviar:

- **Con código a primeira vez** (vén así): a primeira vez, os aparellos de Apple escriben un código de catro cifras que sae na pantalla, e os demais piden permiso nela.
- **Calquera da casa**: calquera aparello conectado á túa rede envía sen preguntar.
- **Con contrasinal**: os aparellos de Apple usan un contrasinal que escolles ti; os demais piden permiso a primeira vez.

Vén activado. Se non o vas usar, desactiva **Recibir nesta pantalla** e Proxectar quítase; podes poñelo cando queiras desde **Actualizacións → Apps de Home**, en **Opcionais**.

**Pantalla en repouso.** Que pasa cando ninguén a toca:

- **Sae o protector de pantalla**: a hora, o tempo e os teus fondos. Escolle despois de canto tempo aparece e a túa cidade, que é de onde saen o tempo, a choiva e os avións.
- **Queda o que haxa** (vén así): queda diante o panel ou a app que teñas aberta.

O espertador soa nos dous casos.

**Pantalla.** O brillo e, se non usas o protector de pantalla, despois de canto tempo se apaga. Se a usas como panel ou como reloxo, escolle **Nunca**.

**Navegación.** Como te moves pola pantalla: con **Xestos** (vén así) ou con **Botóns**, sempre á vista abaixo. Está explicado en [Moverte por Home](moverte-por-home.md).

## Privacidade e opcións avanzadas

**Privacidade.** Se se poden usar o micrófono e a cámara. A cámara vén desactivada.

**Axuda a mellorar Home.** Se queres, a pantalla conta unha vez ao día como está configurada e se as actualizacións saen ben. Vén apagado: só se envía se o activas. O paso di que se envía e que non se envía nunca.

**Opcións avanzadas.** IP fixa, enderezo MAC, certificados propios, depuración ADB e root. Se non os precisas, toca **Continuar**. Tes a explicación na sección [Avanzado](README.md#avanzado).

## Resumo

Repasa todo. Toca unha liña para cambiala e, cando estea ben, toca **Aplicar**.

A pantalla vai dicindo o que fai. Non a apagues nin a desenchufes mentres tanto. Se algo non sae ben, amósao arriba e permíteche volver ao resumo; o resto xa queda feito. Ao rematar, toca **Comezar a usala**. Non fai falta reiniciar.

## Onde se cambia despois

| Que | Onde |
| --- | --- |
| Idioma | Configuración → Sistema → Idiomas |
| Tamaño do texto | Configuración → Pantalla → Tamaño do tipo de letra |
| Wifi | Configuración → Rede e Internet |
| Nome | Configuración → Acerca do dispositivo → Nome do dispositivo |
| Proxectar | App Proxectar |
| Protector de pantalla | App Protector de pantalla → Ao deixar de usala |
| Brillo e apagado | Configuración → Pantalla |
| Xestos ou botóns | Configuración → Sistema → Xestos → Navegación do sistema |
| Axuda a mellorar Home | App Actualizacións → Axustes |
| Depuración ADB | Configuración → Sistema → Opcións de programador |
