# Panel de Home Assistant

La pantalla puede enseñar tu panel de Home Assistant a pantalla completa y abrirlo sola cada vez que se enciende. Lo hace Fully Kiosk, que el asistente instala si marcas **Panel de Home Assistant**.

## Cómo queda configurado

En el asistente:

1. Marca **Panel de Home Assistant** en **Qué quieres instalar**.
2. En el paso **Home Assistant**, elige el tuyo de la lista o escribe su dirección, por ejemplo `homeassistant.local:8123`.

Al aplicar, el asistente baja Fully Kiosk de su web, comprueba que es el de verdad, le pone la dirección de tu Home Assistant y lo deja como pantalla de inicio. Al terminar, ya sale tu panel.

## Si tu Home Assistant usa https con un certificado propio

Añade el certificado en el asistente, en **Opciones avanzadas → Certificados propios** (un fichero .crt o .pem), para que el panel lo acepte. Lo tienes en [IP fija, MAC y certificados](red-y-certificados.md).

## Cambiar la dirección

La dirección se cambia en los ajustes de Fully Kiosk: desliza desde el borde izquierdo para abrir su menú, entra en sus ajustes y cambia la página de inicio (**Start URL**).

Algunas opciones de Fully son de pago; para enseñar el panel no hacen falta.

## Con el salvapantallas

Si quieres que salga el salvapantallas de Home con el panel:

- En Fully, apaga su opción para mantener la pantalla encendida (**Keep Screen On**). Si no, el salvapantallas no sale nunca.
- No uses a la vez el salvapantallas de Fully.

Más en [El salvapantallas](salvapantallas.md).

## Volver al inicio de siempre

Si dejas de usar el panel, cambia la pantalla de inicio: desliza desde arriba, abre **Ajustes** con la rueda y ve a **Aplicaciones → Aplicaciones predeterminadas → Aplicación de inicio**. Elige **Trebuchet**, el inicio de Android.
