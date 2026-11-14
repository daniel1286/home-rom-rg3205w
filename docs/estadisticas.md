# Estadísticas de Home

Para saber cuántas pantallas usan Home, en qué versión y si las actualizaciones salen bien. Nada de lo que se recoge
identifica a nadie.

## 1. Recuento por versión (con la búsqueda de actualizaciones)

Desde la 2.1, para buscar actualizaciones la app Actualizaciones pregunta a la dirección de Home
diciendo solo su versión, y el servidor contesta qué paquete toca. Cada cuánto busca sola se
elige en Actualizaciones → Ajustes: cada 6 horas, cada día (de serie), cada semana o nunca. La primera búsqueda sola de
cada día lleva además `diaria=1`, y el servidor suma uno a esa versión en ese día: ese es el recuento. Las búsquedas a
mano no cuentan. Por eso, una pantalla que busca cada semana se cuenta un día por semana, y una que no busca sola no se
cuenta. No se envía nada más, ni hay identificador, y la IP no se guarda. Los paquetes siguen saliendo de las Releases
de GitHub, firmados; la descarga pasa antes por la dirección de Home, que la cuenta (apartado 5).

Las pantallas con la 2.0 siguen leyendo `rg3205w.json` de las Releases de GitHub, y para ellas el recuento son las
descargas diarias de ese archivo que cuenta GitHub. Las descargas de la ROM y de las actualizaciones se cuentan igual.

## 2. «Ayuda a mejorar Home» (opcional)

Se elige en el asistente o en las novedades de cada versión, y se cambia cuando se quiera en Actualizaciones →
Ajustes. Allí, «Ver lo que se envía» enseña el mensaje exacto.

| Qué | Cuándo |
|---|---|
| Identificador al azar creado en la pantalla, versión y número de compilación de Home | Una vez al día |
| Modo (panel, altavoz o tablet), idioma, gestos o botones | Una vez al día |
| Funciones en uso: Salvapantallas, Proyectar (desde qué, en las últimas 24 horas), Bluetooth, root | Una vez al día |
| Resultado de una actualización (de qué versión a cuál, completa o incremental y, si falla, el motivo) | Al arrancar después de instalarla o, si falla antes de instalarse, en ese momento |

No se envían los fallos por falta de red, ni las instalaciones hechas a mano desde un archivo. Lo que no sale por no
haber red se guarda en la pantalla y se envía cuando la hay.

La 2.1 todavía no envía cómo se instaló ni datos de estabilidad (cierres de las apps de Home, reinicios inesperados,
tiempo de arranque, temperatura máxima, fallos de Bluetooth y Wi-Fi). El formato los admite; si una versión los empieza
a enviar, se dirá aquí y en sus novedades.

Al desactivarlo, la pantalla pide borrar todo lo que lleva su identificador, y deja de enviar. También se puede pedir
un identificador nuevo en Actualizaciones → Ajustes: se borra todo lo del anterior.

## 3. Instaladores

El instalador de Windows y el de la Raspberry Pi traen marcada, desde su primera pantalla, la casilla «Contar esta
instalación». Se puede desmarcar antes de empezar. Si está marcada, al terminar envían solo: si salió bien o en qué paso
falló, la versión del instalador, la versión de Home, el camino (cable o inalámbrico) y la duración. Sin identificador
y sin nada del ordenador.

Para saber qué versiones de Home hay, el instalador de Windows (desde su 2.1) pregunta a la dirección de Home
sin enviar nada: esa consulta no se cuenta ni se guarda. El servidor saca la lista de las
Releases de la ROM, y el zip sigue saliendo de ellas, pasando por la dirección de Home (apartado 5); el instalador
comprueba su huella SHA256 antes de usarlo.

### Informe de un fallo (solo si se pide)

Aparte de la casilla, y nunca automático. Si algo falla, el instalador ofrece «Enviar informe del fallo»: enseña el
registro exacto que se enviaría y solo lo envía si la persona pulsa «Enviar informe». Antes de enseñarlo lo limpia (sin
número de serie de la Askey, usuario ni nombre del PC, y sin direcciones de correo, IP o MAC) y se queda con el final,
que es donde está el fallo. La recogida vuelve a quitar correos, IP, MAC, tokens y direcciones para entrar en casa
desde fuera por si se escapara alguno. Devuelve un código
(`H-7K3Q2M`) para ponerlo en una incidencia de GitHub. Se borra a los 90 días.

## 4. App Ayuda (reportes que escribe la persona)

Desde la app Ayuda se puede contar un problema: se elige de qué es (Bluetooth, Wi-Fi, Salvapantallas…), se escribe y,
si se quiere, se añade el registro del sistema, que la app enseña entero antes de enviarlo. Nunca sale nada solo. Va
sin identificador de la pantalla; la pantalla y luego el servidor quitan correos, IP, MAC, tokens y direcciones para
entrar en casa desde fuera (las de DNS dinámico, Nabu Casa o túneles) de lo que se escriba o se adjunte.

Al enviarlo, la app recibe un código (`H-7K3Q2M`) y una clave que solo tiene ella. Con los dos enseña en qué estado
está el reporte y la respuesta de quien mantiene Home, y la persona lo borra cuando quiera: sin la clave, el servidor no
da ni el estado. Se borra solo a
los 90 días de su último cambio.

## 5. Descargas

Para que las cuentas no dependan de GitHub, el instalador de Windows y la app Actualizaciones (las dos desde su 2.1) bajan
los paquetes de Home por una puerta de la dirección de Home. El servidor
suma uno a ese archivo y esa versión en ese día, según venga del instalador o de la app, y manda a la Release de GitHub,
de donde sigue saliendo el archivo, firmado y con su huella. No se guarda nada más.

- En el instalador solo cuenta si «Contar esta instalación» está marcada. Desmarcada, no se cuenta y la
  puerta solo hace de paso hacia GitHub.
- Una descarga que sigue por donde se cortó no cuenta otra vez, ni las lecturas del final del paquete que hace la app
  para comprobar la firma antes de bajarlo.
- Las apps de Home que se actualizan solas, sin esperar a una OTA (Salvapantallas, Proyectar…), bajan igual por la
  puerta, desde la Release `apps`: se cuenta cuántas veces se baja cada APK, nada más. La lista de apps
  la pide Actualizaciones después de buscar la OTA, sin enviar nada, y esa consulta no se
  cuenta.
- Los modelos de voz de la app Voz bajan igual por la puerta, desde la Release `voz-1` de la ROM:
  solo pasan los cuatro modelos de su lista, y se cuenta cuántas veces se baja cada uno, nada más.
- Las descargas directas desde GitHub (la web, las pantallas con la 2.0, los instaladores 2.0 y el de la Raspberry Pi)
  salen de los contadores de GitHub, restando lo que ha pasado por la puerta.

## Lo que no se recoge nunca

Nombre del aparato, nombre de la red Wi-Fi, MAC, número de serie, ubicación, la ciudad del tiempo, la dirección de
Home Assistant, las apps instaladas ni nada de lo que se escribe. La dirección IP no se guarda: el servidor la ve al
recibir el envío, como cualquier servidor, pero no la escribe en ningún sitio, y los registros no la incluyen.

## Dónde se guarda y cuánto tiempo

En Cloudflare (Workers y una base de datos D1). Los días van sin hora. Lo que lleva identificador se borra a los 90 días;
antes, se resume por día sin identificadores (cuántas pantallas en cada versión, en cada modo…), y ese resumen se
conserva. Los resultados de las instalaciones y las descargas no llevan identificador y se conservan. Los informes de
fallos se borran a los 90 días.

Las cifras solo las ve quien mantiene Home, en un panel privado.

## Seguridad

- El servidor solo acepta lo que envían de verdad las apps de Home, con su formato exacto y de versiones publicadas. Lo
  demás se rechaza.
- Hay límites de envíos, contra quien intente llenarlo de datos inventados.
- Antes de guardar nada se quitan los correos, direcciones IP, MAC y contraseñas que se hubieran escrito o adjuntado.
- La clave para borrar un reporte no se guarda, solo su huella: ni quien mantiene Home puede hacerse pasar por ti.
- En Actualizaciones → Ajustes, «Ver lo que se envía» enseña el mensaje exacto antes de que salga.
