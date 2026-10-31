<p align="center">
  <img src="img/portada/arranque.gif" width="720" alt="Animación de arranque de Home">
</p>

<p align="center">
  <b>Android 15 para el Askey RG3205W</b><br>
  Una segunda vida para tu pantalla de casa: limpia, cifrada y lista en unos minutos.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-15-E0A85A?style=flat-square&labelColor=1B1A18&logo=android&logoColor=E0A85A" alt="Android 15">
  <img src="https://img.shields.io/badge/LineageOS-22.2-E0A85A?style=flat-square&labelColor=1B1A18&logo=lineageos&logoColor=E0A85A" alt="LineageOS 22.2">
  <img src="https://img.shields.io/badge/kernel-4.9-E0A85A?style=flat-square&labelColor=1B1A18&logo=linux&logoColor=E0A85A" alt="Kernel 4.9">
  <img src="https://img.shields.io/badge/licencia-Apache--2.0-E0A85A?style=flat-square&labelColor=1B1A18" alt="Licencia Apache-2.0">
  <a href="https://github.com/daniel1286/home-rom-rg3205w/releases/latest"><img src="https://img.shields.io/github/v/release/daniel1286/home-rom-rg3205w?label=versi%C3%B3n&cacheSeconds=3600&style=flat-square&labelColor=1B1A18&color=E0A85A" alt="Versión"></a>
</p>

<p align="center">
  <a href="https://github.com/daniel1286/home-rom-rg3205w/releases/latest"><b>Descargar</b></a>
  &nbsp;·&nbsp;
  <a href="https://daniel1286.github.io/home-rom-rg3205w/"><b>Probar la demo</b></a>
  &nbsp;·&nbsp;
  <a href="#qué-trae"><b>Qué trae</b></a>
  &nbsp;·&nbsp;
  <a href="guias/INSTALAR.md"><b>Guía de instalación</b></a>
  &nbsp;·&nbsp;
  <a href="#detalles-técnicos"><b>Detalles técnicos</b></a>
  &nbsp;·&nbsp;
  <a href="README.en.md"><b>English</b></a>
</p>

<br>

> [!NOTE]
> **Ya está la 2.0.** Descárgala en **[Releases](https://github.com/daniel1286/home-rom-rg3205w/releases/latest)** y sigue la [guía de instalación](guias/INSTALAR.md). Para enterarte de las próximas versiones, dale a **Watch → Custom → Releases** arriba a la derecha.

## Qué es Home

El Askey RG3205W tiene más hardware del que su software deja ver: un Snapdragon 625 de ocho núcleos, pantalla de 8 pulgadas, dos altavoces y cuatro micrófonos. El software de fábrica se quedó en Android 8.1, con un kernel de 32 bits, el parche de seguridad de octubre de 2021 y las apps del operador.

Home es Android 15 compilado desde el código de LineageOS solo para este aparato. No es la ROM de otro móvil adaptada: el kernel, los controladores y el árbol de dispositivo están hechos o ajustados para el RG3205W, y no lleva nada que no hayas elegido tú.

La primera vez que la enciendes, un asistente te pregunta para qué la quieres y la deja lista en unos minutos:

- **Panel de Home Assistant**, en la pared o en la encimera, siempre encendido y a pantalla completa.
- **Altavoz de casa**, sonando a la vez que el resto de altavoces con Snapcast.
- **Tablet de 8 pulgadas**, con las apps que instales desde Aurora Store o F-Droid.

| | Software de fábrica | Home 2.0 |
|---|---|---|
| Android | 8.1 | 15 (LineageOS 22.2) |
| Kernel | 3.18, 32 bits | 4.9, 64 bits |
| Parche de seguridad | Octubre de 2021 | Octubre de 2026 |
| Apps preinstaladas | Las del operador | Solo las que eliges |

## Qué trae

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Android 15 de verdad</h3>
      Hecho para este aparato y en horizontal, como una tablet de 8 pulgadas. Wi-Fi, Bluetooth, altavoces, micrófonos y cámara funcionando.
    </td>
    <td width="50%" valign="top">
      <h3>Listo en unos minutos</h3>
      Un asistente al encenderla por primera vez que pregunta lo justo. En español, inglés, catalán, gallego, euskera y portugués.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>Panel de Home Assistant</h3>
      Si lo eliges, instala Fully Kiosk desde su web oficial y abre tu panel a pantalla completa cada vez que se enciende.
    </td>
    <td valign="top">
      <h3>Altavoz de casa</h3>
      Con Snapcast suena a la vez que el resto de altavoces de la casa. Y con droidVNC-NG la manejas desde el PC. Las dos cosas son opcionales.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>Tus apps, sin cuenta de Google</h3>
      Aurora Store para las apps de Google Play y F-Droid para las libres. Las que vienen instaladas se actualizan desde ahí como cualquier otra.
    </td>
    <td valign="top">
      <h3>Se actualiza sola</h3>
      Cuando publico una versión nueva aquí, la app Actualizaciones te avisa y tú eliges cuándo instalarla. Conserva tus datos y apps, sigue por donde iba si se corta el Wi-Fi y solo acepta actualizaciones firmadas por mí.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>Tus datos, cifrados</h3>
      Si alguien se lleva el aparato, no puede leer lo que tienes guardado. SELinux va en modo estricto y lleva el parche de seguridad de octubre de 2026.
    </td>
    <td valign="top">
      <h3>Sin nada que te espíe</h3>
      Sin apps del operador ni telemetría. Lo único que consulta por su cuenta es GitHub, para ver si hay actualizaciones. Y root con Magisk para quien lo quiera.
    </td>
  </tr>
</table>

## Así se ve

### Encendido

Primero sale el splash y, mientras Android carga, la animación de arranque que tienes arriba.

<p align="center">
  <img src="img/arranque/splash.png" width="640" alt="Splash de Home">
</p>

### Asistente de configuración

Idioma, zona horaria, Wi-Fi, nombre del aparato, qué apps quieres, pantalla y privacidad. Los pasos de Home Assistant y del altavoz solo salen si los eliges.

<p align="center">
  <a href="https://daniel1286.github.io/home-rom-rg3205w/">
    <img src="img/portada/asistente.gif" width="720" alt="Recorrido por el asistente de configuración">
  </a>
  <br><br>
  <a href="https://daniel1286.github.io/home-rom-rg3205w/"><img src="https://img.shields.io/badge/%E2%96%B6%20%20Probar%20la%20demo%20en%20el%20navegador-E0A85A?style=for-the-badge&labelColor=1B1A18" alt="Probar la demo en el navegador"></a>
  <br>
  <sub>Se abren el encendido y el asistente completos: toca la pantalla como si fuera el aparato.</sub>
</p>

<table>
  <tr>
    <td width="33%"><img src="img/asistente/01_bienvenida.png" alt="Bienvenida"></td>
    <td width="33%"><img src="img/asistente/02_region.png" alt="Región y hora"></td>
    <td width="33%"><img src="img/asistente/05_apps.png" alt="Aplicaciones"></td>
  </tr>
  <tr>
    <td align="center"><sub>Bienvenida e idioma</sub></td>
    <td align="center"><sub>Región y hora</sub></td>
    <td align="center"><sub>Qué apps quieres</sub></td>
  </tr>
  <tr>
    <td><img src="img/asistente/06_home_assistant.png" alt="Home Assistant"></td>
    <td><img src="img/asistente/07_altavoz.png" alt="Altavoz"></td>
    <td><img src="img/asistente/11_resumen.png" alt="Resumen"></td>
  </tr>
  <tr>
    <td align="center"><sub>Panel de Home Assistant</sub></td>
    <td align="center"><sub>Altavoz de casa</sub></td>
    <td align="center"><sub>Resumen antes de aplicar</sub></td>
  </tr>
</table>

### Actualizaciones

La app Actualizaciones mira en las releases de este repositorio si hay una versión nueva, te enseña qué trae y la baja cuando tú quieras. Antes de bajarla entera comprueba la firma, que sea más nueva y el tamaño, y rechaza la que no cuadre. Al instalarla, el aparato reinicia en el TWRP, que enseña el progreso, y vuelve solo a Home.

<table>
  <tr>
    <td width="50%"><img src="img/actualizaciones/01_al_dia.png" alt="Al día"></td>
    <td width="50%"><img src="img/actualizaciones/02_novedades.png" alt="Aviso de una versión nueva, con sus novedades"></td>
  </tr>
  <tr>
    <td align="center"><sub>Al día</sub></td>
    <td align="center"><sub>Aviso de una versión nueva, con sus novedades</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="img/actualizaciones/03_descargando.png" alt="Descarga, con lo que falta"></td>
    <td width="50%"><img src="img/actualizaciones/04_twrp.png" alt="El TWRP instalándola"></td>
  </tr>
  <tr>
    <td align="center"><sub>Descarga, con lo que falta</sub></td>
    <td align="center"><sub>El TWRP instalándola</sub></td>
  </tr>
</table>

### Fondos de pantalla

<table>
  <tr>
    <td width="25%"><img src="img/fondos/plataforma.png" alt="Plataforma"></td>
    <td width="25%"><img src="img/fondos/rejilla.png" alt="Rejilla"></td>
    <td width="25%"><img src="img/fondos/polvo.png" alt="Polvo de luz"></td>
    <td width="25%"><img src="img/fondos/claro.png" alt="Claro"></td>
  </tr>
  <tr>
    <td align="center"><sub>Plataforma (de serie)</sub></td>
    <td align="center"><sub>Rejilla</sub></td>
    <td align="center"><sub>Polvo de luz</sub></td>
    <td align="center"><sub>Claro</sub></td>
  </tr>
</table>

## Detalles técnicos

Para quien quiera saber qué hay por dentro.

<details>
<summary><b>Hardware y cómo lo usa Home</b></summary>
<br>

| Componente | Hardware | En Home |
|---|---|---|
| Sistema | — | LineageOS 22.2 (Android 15) compilado desde el código, con su propio árbol de dispositivo. Todo en 64 bits; solo la cámara conserva librerías de 32 bits |
| Procesador | Snapdragon 625 (APQ8053), 8 × Cortex-A53 | Kernel 4.9 a partir del código de Qualcomm (CodeLinaro), al día con Linux 4.9 estable |
| Gráficos | Adreno 506 | Controladores de Qualcomm y HAL de gráficos de CAF compilado desde el código. OpenGL ES 3.2 y Vulkan 1.1 |
| Pantalla | 8", 1280 × 800, panel HX8394-D | Tiempos del panel del fabricante en el árbol de dispositivo |
| Táctil | Goodix GT9xx | Controlador del kernel adaptado a los pines del RG3205W |
| Audio | Códec WCD9335, 2 altavoces y 4 micrófonos | HAL de audio de Qualcomm compilado desde el código, con la calibración del fabricante |
| Wi-Fi | QCA9379, 2,4 y 5 GHz | qcacld-2.0 compilado desde el código |
| Bluetooth | QCA9379 por UART | Controlador de Linux (hci_qca) en el kernel y HAL de Bluetooth de AOSP |
| Cámara | OV2735 | HAL de cámara compilado desde el código; el servicio de imagen del fabricante es lo único de 32 bits |
| Brillo | Retroiluminación del panel | HAL de luces propio |
| Alimentación | Siempre enchufado, sin batería | HAL propio: Android sabe que no hay batería y no avisa de batería baja |
| Temperatura | Sensores del procesador | HAL térmico propio |
| Reloj | Sin pila | Servicio propio que guarda la hora entre reinicios |
| Contenido protegido | — | Widevine L3 |

</details>

<details>
<summary><b>Seguridad y actualizaciones</b></summary>
<br>

| | En Home |
|---|---|
| Compilación | `user`, la de producción. Firmada con claves propias que no se publican |
| SELinux | Modo estricto, con reglas escritas para este hardware |
| Parche de seguridad | Octubre de 2026 |
| Datos | Cifrado por ficheros (FBE) |
| Actualizaciones | App propia, Actualizaciones, que busca en las releases de este repositorio. Solo instala paquetes con mi firma y de una versión más nueva; los instala el TWRP sin borrar datos. También se abre desde Ajustes |
| Root | Magisk va en el boot, pero el root está apagado de serie. Se activa en el asistente, en «Opciones avanzadas» ([cómo](guias/INSTALAR.md#9-actualizaciones-adb-y-root)) |
| Recovery | TWRP con el diseño de Home, con su propia pantalla para instalar actualizaciones |
| Depuración | ADB desactivado de serie. Se activa en el asistente o en las opciones para desarrolladores, por USB o por Wi-Fi ([cómo](guias/INSTALAR.md#9-actualizaciones-adb-y-root)) |

</details>

## Qué vas a necesitar

- Un Askey RG3205W, Rev4 o Rev5.
- Un PC con Windows 10 u 11 de 64 bits.
- Un cable USB para conectarlo al PC. El Rev5 necesita además un adaptador al conector interno J4902 ([cómo saber cuál tienes](guias/INSTALAR.md#2-saber-si-es-rev4-o-rev5-y-conectarlo-al-pc)).

## Instalación

La **[guía de instalación](guias/INSTALAR.md)** lo explica todo paso a paso y con dibujos, pensada para quien no ha instalado nunca una ROM. En resumen:

1. Abrir el aparato para saber si es Rev4 o Rev5 y conectarlo al PC.
2. Instalar los drivers USB de Google en Windows.
3. Entrar en modo fastboot con los botones y desbloquear el bootloader si hace falta.
4. Ejecutar el instalador que viene en el zip.
5. Reiniciar y seguir el asistente.

> [!WARNING]
> Instalarla borra todos los datos del aparato. Cambiar el software puede anular la garantía, así que hazlo bajo tu responsabilidad.

## Preguntas frecuentes

**¿Necesito una cuenta de Google?**
No. Aurora Store descarga las apps de Google Play sin cuenta y F-Droid trae las apps libres.

**¿Se borran mis datos al actualizar?**
No. Solo borra la instalación desde el PC. Las actualizaciones de la app Actualizaciones conservan tus apps, ajustes y datos.

**¿Cómo activo ADB o root?**
En el asistente, en «Opciones avanzadas». Si ya lo has configurado, la [guía](guias/INSTALAR.md#9-actualizaciones-adb-y-root) explica cómo activar ADB después.

**¿Puedo volver al software de fábrica?**
Antes de instalar, haz la copia completa por EDL que explica la [guía](guias/INSTALAR.md#11-copia-de-seguridad-y-rescate-por-edl). Es la única forma de guardar el software de fábrica y los datos propios de tu aparato.

**¿Funciona en el mío?**
Home es para el Askey RG3205W, Rev4 y Rev5. Si algo no te va, cuéntamelo en un informe de prueba.

## ¿Ya lo has instalado?

Cuéntame cómo te ha ido en un **[informe de prueba](https://github.com/daniel1286/home-rom-rg3205w/issues/new?template=informe_prueba.yml)**. Son dos minutos: tu revisión (Rev4 o Rev5), la versión de Home que has instalado y qué funciona y qué no. Con cada informe sé en qué aparatos va bien Home y qué tengo que mejorar.

Para dudas, fallos o ideas, abre una incidencia en **[Issues](https://github.com/daniel1286/home-rom-rg3205w/issues)**.

## Código

Cada release trae el código del kernel (`Home-<versión>-kernel-src.tar.gz`) y del recovery (`Home-<versión>-twrp-src.tar.gz`) con el que se ha compilado esa versión.

## Créditos

Home no existiría sin el trabajo de mucha gente:

- [LineageOS](https://lineageos.org), la base del sistema.
- [Qualcomm CodeLinaro](https://git.codelinaro.org/clo/la) y [Linux](https://kernel.org), de donde sale el kernel.
- [xiaomi-msm8953-devs](https://github.com/xiaomi-msm8953-devs/android_kernel_xiaomi_msm8953), que me sirvió de referencia para el kernel de msm8953.
- [zry98/movistar-home-hacks](https://github.com/zry98/movistar-home-hacks), por documentar el hardware, el desbloqueo y el modo EDL.
- [TWRP](https://twrp.me), [Magisk](https://github.com/topjohnwu/Magisk), [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore), [F-Droid](https://f-droid.org), [Snapcast](https://github.com/badaix/snapdroid) y [droidVNC-NG](https://github.com/bk138/droidVNC-NG).

## Licencia

El código propio de Home va bajo la [Apache License 2.0](LICENSE). El kernel va bajo la GPL-2.0, como Linux, y TWRP y las apps de terceros mantienen sus propias licencias.

<br>

<p align="center">
  <sub>Home es un proyecto independiente, sin relación con Askey ni con ningún operador. Todas las marcas pertenecen a sus respectivos propietarios.</sub>
</p>
