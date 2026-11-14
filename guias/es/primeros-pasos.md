# Primeros pasos

La primera vez que se enciende, Home abre un asistente que deja la pantalla lista en unos minutos. Aquí tienes qué pide cada paso, qué conviene elegir y dónde se cambia después.

## Antes de empezar

- La pantalla tiene que estar enchufada. No tiene batería: si se desenchufa, se apaga.
- Ten a mano la contraseña de tu Wi-Fi.
- Si la vas a usar de panel de Home Assistant o de altavoz de casa, deja encendido tu servidor: el asistente lo busca en la red.

En todos los pasos tienes **Atrás** abajo a la izquierda y **Siguiente** abajo a la derecha. Casi nada se aplica hasta el final, así que puedes ir y volver sin miedo.

## Idioma, región y texto

**Hola.** Elige el idioma: el asistente cambia al momento y la pantalla se queda en ese idioma. Luego pulsa **Empezar**.

**Región y hora.** La zona horaria (Península y Baleares, Canarias, Ceuta y Melilla o Portugal), si la hora se toma de Internet y si la quieres en formato de 24 horas.

**Tamaño del texto.** Normal, Grande o Muy grande. Al tocar uno, todo el asistente cambia para que veas cómo queda. Vale para todas las apps de Home, el salvapantallas incluido.

## Wi-Fi y nombre

**Wi-Fi.** Elige tu red, escribe la contraseña y pulsa **Conectar**. Si no sale, pulsa **Buscar de nuevo**. Puedes saltarte este paso, pero sin conexión no se puede instalar el panel de Home Assistant ni poner la hora automática.

**Nombre.** Cómo se llamará la pantalla en tu red, por Bluetooth y al proyectar. Si tienes más de una en casa, ponle el nombre de la habitación: Salón, Cocina, Entrada…

## Qué quieres instalar

Marca lo que vas a usar. Lo que no marques no se instala y no ocupa sitio.

| Opción | Para qué |
| --- | --- |
| Panel de Home Assistant | Tu panel a pantalla completa, que se abre solo al encender. Lo enseña Fully Kiosk |
| Altavoz de casa | Que la pantalla suene a la vez que el resto de altavoces, con tu servidor de música |
| Manejar la pantalla desde el PC | Ver y tocar la pantalla desde otro ordenador |
| F-Droid | Tienda de apps libres y gratuitas |
| Aurora Store | Apps de Google Play sin cuenta de Google |
| Ayuda | Esta guía y, si algo falla, contarlo y ver la respuesta |
| Monitor | Ver la pantalla por dentro: procesador, memoria, temperaturas y red |

Ayuda, F-Droid y Aurora Store vienen marcadas; Monitor, no. Ayuda y Monitor se desinstalan después como cualquier app.

Si marcas el panel o el altavoz, salen dos pasos más:

- **Home Assistant.** El asistente lo busca en tu red. Si no lo encuentra, escribe la dirección, por ejemplo `homeassistant.local:8123`. Si tu Home Assistant usa un certificado propio, añádelo en **Opciones avanzadas**.
- **Altavoz de casa.** Elige tu servidor de música de la lista o escribe su dirección.

## Proyectar y pantalla en reposo

**Proyectar.** Deja que esta pantalla reciba la imagen y el sonido del iPhone, el Mac, el ordenador con Windows o el móvil Android. Elige quién puede enviar:

- **Con código la primera vez** (viene así): la primera vez, los aparatos de Apple escriben un código de cuatro cifras que sale en la pantalla, y los demás piden permiso en ella.
- **Cualquiera de casa**: cualquier aparato conectado a tu red envía sin preguntar.
- **Con contraseña**: los aparatos de Apple usan una contraseña que eliges tú; los demás piden permiso la primera vez.

Viene activado. Si no lo vas a usar, desactiva **Recibir en esta pantalla** y Proyectar se quita; lo puedes poner cuando quieras desde **Actualizaciones → Apps de Home**, en **Opcionales**.

**Pantalla en reposo.** Qué pasa cuando nadie la toca:

- **Sale el salvapantallas**: la hora, el tiempo y tus fondos. Elige tras cuánto rato sale y tu ciudad, que es de donde salen el tiempo, la lluvia y los aviones.
- **Se queda lo que haya** (viene así): se queda delante el panel o la app que tengas abierta.

El despertador suena en los dos casos.

**Pantalla.** El brillo y, si no usas el salvapantallas, tras cuánto se apaga. Si la usas de panel o de reloj, elige **Nunca**.

**Navegación.** Cómo te mueves por la pantalla: con **Gestos** (viene así) o con **Botones**, siempre a la vista abajo. Está explicado en [Moverte por Home](moverte-por-home.md).

## Privacidad y opciones avanzadas

**Privacidad.** Si se pueden usar el micrófono y la cámara. La cámara viene desactivada.

**Ayuda a mejorar Home.** Si quieres, la pantalla cuenta una vez al día cómo está configurada y si las actualizaciones salen bien. Viene apagado: solo se envía si lo activas. El paso dice qué se envía y qué no se envía nunca.

**Opciones avanzadas.** IP fija, dirección MAC, certificados propios, depuración ADB y root. Si no los necesitas, pulsa **Seguir**. Tienen su explicación en la sección [Avanzado](README.md#avanzado).

## Resumen

Repasa todo. Toca una línea para cambiarla y, cuando esté bien, pulsa **Aplicar**.

La pantalla va diciendo lo que hace. No la apagues ni la desenchufes mientras tanto. Si algo no sale, lo enseña arriba y te deja volver al resumen; lo demás ya queda puesto. Al terminar, pulsa **Empezar a usarla**. No hace falta reiniciar.

## Dónde se cambia después

| Qué | Dónde |
| --- | --- |
| Idioma | Ajustes → Sistema → Idiomas |
| Tamaño del texto | Ajustes → Pantalla → Tamaño de la fuente |
| Wi-Fi | Ajustes → Redes e Internet |
| Nombre | Ajustes → Información del dispositivo → Nombre del dispositivo |
| Proyectar | App Proyectar |
| Salvapantallas | App Salvapantallas → Al dejar de usarla |
| Brillo y apagado | Ajustes → Pantalla |
| Gestos o botones | Ajustes → Sistema → Gestos → Navegación del sistema |
| Ayuda a mejorar Home | App Actualizaciones → Ajustes |
| Depuración ADB | Ajustes → Sistema → Opciones para desarrolladores |
