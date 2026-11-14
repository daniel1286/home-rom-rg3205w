# IP fija, MAC y certificados

Opciones para redes y servidores propios. Si no sabes si las necesitas, no las necesitas: con lo de serie, todo funciona.

## IP fija

Normalmente el router le da a la pantalla su dirección IP. Si quieres que tenga siempre la misma, por ejemplo para entrar por ADB o desde Home Assistant:

- **En el asistente**, en **Opciones avanzadas → IP fija**: la IP, la puerta de enlace y el DNS. Primero hay que conectar la Wi-Fi.
- **Después**, en **Ajustes → Redes e Internet → Internet**, toca la rueda de tu red, luego el lápiz, y en **Opciones avanzadas → Ajustes de IP** elige **Estática**.

Otra forma, sin tocar la pantalla: reserva la IP en tu router para la dirección MAC de la pantalla.

## Dirección MAC

Es el número con el que el router reconoce la pantalla. En el asistente, en **Opciones avanzadas → Dirección MAC**:

| Opción | Qué hace |
| --- | --- |
| Mantener la de fábrica | La de siempre del aparato. Es lo que viene de serie |
| Generar una nueva | Una al azar, fija para tu red: el router ve una pantalla nueva |

Después se cambia en los ajustes de tu red, en **Privacidad**: **Usar MAC aleatoria** o **Usar MAC del dispositivo**.

## Certificados propios

Si tus servidores de casa usan https con un certificado propio, la pantalla tiene que conocerlo para fiarse de ellos.

- **En el asistente**, en **Opciones avanzadas → Certificados propios**, toca **Añadir certificado** y elige el fichero .crt o .pem.
- **Después**, en **Ajustes → Seguridad y privacidad → Más ajustes de seguridad → Cifrado y credenciales → Instalar un certificado → Certificado de CA**.

Quedan en el almacén de usuario. Para quitarlos, en **Cifrado y credenciales → Credenciales de confianza**, pestaña **Usuario**.
