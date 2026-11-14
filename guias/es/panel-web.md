# Panel web

Con el panel web ves cómo está la pantalla y cambias sus ajustes desde el navegador del móvil o del ordenador, sin tocarla. Funciona solo dentro de casa y viene apagado: solo lo tiene quien lo elige.

## Encenderlo

- **En el asistente**, marca **Panel web** en **Qué quieres instalar**. Queda instalado y encendido.
- **Si actualizaste desde la 2.0**, se ofrece en las novedades de la 2.1: **Instalar y encender el panel web**.
- **Si no lo marcaste**, ponlo desde **Actualizaciones → Apps de Home → Opcionales**, con **Poner**. Se pone apagado.
- **Si ya lo tienes**, abre la app **Panel web** y activa **Encendido**, arriba a la derecha.

Mientras está encendido hay un aviso fijo, «Panel web encendido», con el botón **Apagar**.

## Emparejar el móvil o el ordenador

1. En la pantalla, abre la app **Panel web**. En **Abrir el panel** sale la dirección y un código QR.
2. Escanea el código con el móvil, o escribe la dirección tal cual sale, con el `:8443` del final. Si la escribes sin `https://`, la pantalla te lleva sola a la versión segura.
3. La primera vez, el navegador avisa de que el certificado no es de una autoridad conocida. Es normal: es de esta pantalla. Comprueba que su huella (SHA-256) es la de la app, que sale en **Abrir el panel** debajo de la dirección. En el navegador se ve tocando el aviso o el candado junto a la dirección y abriendo los detalles del certificado. Si coincide, continúa.
4. En **Empareja este navegador**, toca **Pedir el código**. En la pantalla sale el código de 6 cifras; vale 2 minutos.
5. Escríbelo en **Código de la pantalla**. Si quieres, ponle un nombre al aparato, para reconocerlo luego en la lista.
6. Toca **Emparejar**.

Ya estás en el panel. Las siguientes veces ese navegador entra directamente, sin código.

> [!TIP]
> Si en la pantalla sale un código que no has pedido, toca **Cerrar** y ese código deja de valer. Alguien de tu red, también el móvil de un invitado conectado a tu Wi-Fi, está intentando emparejar un navegador.

## Qué se puede hacer

| Parte | Qué hay |
| --- | --- |
| Estado | Versión, temperatura, procesador, memoria, Wi-Fi y tiempo encendida |
| Pantalla y sonido | Brillo, apagar o encender la pantalla, tamaño del texto y volumen de la música y de las alarmas |
| Salvapantallas | Si sale, tras cuánto rato y la ciudad del tiempo |
| Proyectar | Encenderlo o apagarlo, quién puede enviar y cortar lo que se está recibiendo |
| Actualizaciones | Si está al día, buscar ahora y cada cuánto busca sola. Instalar siempre se confirma en la pantalla |
| Aparatos | Los navegadores emparejados, cuándo se usaron por última vez, y quitarlos |
| Últimos cambios | Qué se ha cambiado desde el panel y desde qué aparato |
| Reiniciar | Con dos confirmaciones en el navegador y una cuenta atrás de 15 segundos en la pantalla, con **Cancelar** |

Lo que nunca se puede hacer desde el panel: cambiar el Wi-Fi o su contraseña, la depuración ADB, el root o los certificados; instalar o quitar apps; ver el registro del sistema; usar la cámara o el micrófono.

## Seguro dentro de casa

- Escucha solo en el Wi-Fi de casa y rechaza lo que no venga de ella. No abre nada en el router ni pasa por ninguna nube.
- Todo va cifrado (HTTPS), con un certificado propio de esta pantalla. Su clave se guarda en el almacén de claves de Android y no sale nunca de ella.
- Cada cambio sale un momento en la pantalla y queda apuntado en **Últimos cambios**, con el aparato que lo hizo.
- Un navegador que no se usa en 90 días tiene que volver a emparejarse.

## Si no deja emparejar

| Lo que pasa | Qué hacer |
| --- | --- |
| No sale el código en la pantalla | Abre la app **Panel web** en la pantalla y toca **Emparejar**: sale el código que está en uso o uno nuevo |
| «Ese no es el código. Quedan … intentos.» | Mira bien el código de la pantalla y escríbelo otra vez |
| «El código ha caducado. Pide otro.» | Pasaron los 2 minutos: toca **Pedir el código** otra vez |
| «Demasiados intentos con ese código. Pide otro.» | Pide un código nuevo |
| «Espera … segundos antes de pedir otro código.» | Espera lo que dice y vuelve a pedirlo |
| «Ya hay 12 aparatos emparejados. Quita alguno desde la pantalla.» | En la app, en **Aparatos emparejados**, quita alguno que ya no uses |

## Quitar un aparato o apagar el panel

- **En la pantalla**, en la app **Panel web**: en **Aparatos emparejados**, toca **Quitar** en uno o, si hay más de uno, **Quitar todos**.
- **En el navegador**: en **Aparatos emparejados** de la página, toca **Quitar** en el que quieras, o abajo **Desemparejar este navegador**. Ese navegador vuelve a pedir el código.
- **Apagarlo**: toca **Apagar** en el aviso o desactiva **Encendido** en la app. Apagado, no hay nada escuchando.
- Si crees que alguien tiene una copia del certificado, toca **Hacer un certificado nuevo** en la app. La huella cambia y cada navegador avisará una vez más.

## Quitarlo o volver a ponerlo

El panel web se desinstala como cualquier app, y se vuelve a poner desde **Actualizaciones → Apps de Home → Opcionales**. Lo tienes en [Quitar o volver a poner apps](quitar-o-poner-apps.md).

- Al volver a ponerlo se instala apagado: abre la app y activa **Encendido**.
- La pantalla hace otro certificado: cada navegador avisará una vez más y habrá que emparejarlos de nuevo.
- Al actualizar el panel, en cambio, el certificado no cambia y los navegadores siguen entrando sin código.
