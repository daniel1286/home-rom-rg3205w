# Problemas frecuentes

Lo que más pasa y cómo se arregla. Si lo tuyo no está aquí o no se arregla, [cuéntalo](contar-un-problema.md) y verás la respuesta en la propia pantalla.

## Pantalla

### No sale el salvapantallas

Pasa por una de estas dos cosas:

1. En la app **Salvapantallas**, **Al dejar de usarla** está en **Se queda lo que haya**. Elige **Sale el salvapantallas**.
2. Una app mantiene la pantalla encendida. En Fully Kiosk, apaga su opción **Keep Screen On**.

Más en [El salvapantallas](salvapantallas.md).

### Se queda en negro al reiniciar

Con el cable USB del ordenador puesto, la pantalla no termina de arrancar. Quita el cable, desenchúfala de la corriente y vuelve a enchufarla.

### No salen los botones Atrás, Inicio y Recientes

No es un fallo: Home viene con la navegación por gestos. Si prefieres los botones, ve a **Ajustes → Sistema → Gestos → Navegación del sistema** y elige **Navegación con 3 botones**. Los gestos están explicados en [Moverte por Home](moverte-por-home.md).

### El botón de encendido no hace nada

Una pulsación corta apaga la pantalla y una larga abre el menú para apagar o reiniciar. Si usas Fully Kiosk, mira que no tenga activada su opción para desactivar el botón de encendido.

## Proyectar

### El iPhone o el ordenador no ven la pantalla

- Comprueba que los dos están en la misma red Wi-Fi. Las redes de invitados del router no suelen dejar que los aparatos se vean.
- En la app **Proyectar**, mira que esté activado y que en **Desde dónde** esté encendido lo que usas.
- Con **Solo sonido** activado, Windows y Android no ven la pantalla: solo sirven para duplicarla.

### Se ve en negro

Las películas y series de pago no dejan enviarse a otra pantalla por su protección de copia. Lo demás se ve con normalidad.

### Se corta o va a saltos

La imagen va por la Wi-Fi. Acerca la pantalla o el aparato al router y, si puedes, usa la red de 5 GHz. En **Proyectar → Calidad**, **Como la pantalla** pide menos a la red que **Alta (1080p)**.

## Sonido y Bluetooth

### El altavoz Bluetooth se desconecta

En **Ajustes → Dispositivos conectados**, toca el altavoz, elige **Olvidar** y vuelve a emparejarlo. Tenlo cerca de la pantalla mientras lo haces. Las llamadas no van por Bluetooth: un auricular con micrófono solo suena.

### No suena a la vez que el resto de la casa

Abre la app **Snapcast** y comprueba que está conectada a tu servidor de música. Si el servidor no ve la pantalla, ponle nombre desde el propio servidor. Lo tienes en [Altavoz de casa](altavoz-de-casa.md).

## Wi-Fi y hora

### No sale ninguna red Wi-Fi

Pulsa **Buscar de nuevo**. Si sigue sin salir ninguna, reinicia la pantalla con una pulsación larga del botón de encendido.

### La hora no es la buena

La pantalla no tiene pila para el reloj: toma la hora de Internet. En **Ajustes → Sistema → Fecha y hora**, comprueba que la hora automática está activada y que la zona horaria es la tuya.

## Actualizaciones

### La actualización no se instala

La app **Actualizaciones** dice por qué. Lo más habitual:

- **Quita el cable USB**: con el cable del ordenador puesto no termina de arrancar.
- **No hay sitio**: hace falta el doble de lo que ocupa la versión. Libera espacio y vuelve a intentarlo.
- **Se ha cortado la conexión**: lo descargado se aprovecha; al volver a intentarlo sigue por donde iba.

Cada aviso está explicado en [Si una actualización no se instala](si-no-se-instala.md). Tus apps, ajustes y datos no se tocan.

### No avisa de las versiones nuevas

En **Actualizaciones → Ajustes**, mira **Búsqueda automática**: si está en **Nunca, solo a mano**, no avisa. Puedes buscar cuando quieras con **Buscar ahora**.

## Panel y apps

### El panel no se abre al encender

Fully Kiosk tiene que ser la app de inicio. Ve a **Ajustes → Aplicaciones → Aplicaciones predeterminadas → Aplicación de inicio** y elige **Fully Kiosk Browser**. Si se abre pero sale en blanco, revisa en Fully la dirección de tu Home Assistant.
