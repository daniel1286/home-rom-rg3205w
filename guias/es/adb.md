# Depuración ADB

ADB deja manejar la pantalla desde un ordenador con órdenes: instalar apps, ver el registro, copiar archivos. Viene desactivado y es solo para quien lo necesite.

> [!WARNING]
> Con ADB activado, quien tenga acceso a tu red puede intentar controlar la pantalla. Actívalo solo mientras lo uses y apágalo al terminar.

## Activarlo

### En el asistente

En **Opciones avanzadas → Depuración (ADB)**. Queda activado por USB y por Wi-Fi, y tu red queda aceptada para la depuración inalámbrica.

### Después, desde Ajustes

1. En **Ajustes → Información del dispositivo**, pulsa siete veces **Número de compilación**. Aparecen las **Opciones para desarrolladores**.
2. Entra en **Ajustes → Sistema → Opciones para desarrolladores**.
3. Activa **Depuración por USB** o **Depuración inalámbrica**.

La primera vez que se conecte un ordenador, la pantalla pregunta si lo autorizas.

## Por Wi-Fi

1. En **Opciones para desarrolladores**, entra en **Depuración inalámbrica**.
2. Pulsa **Vincular dispositivo con código de vinculación**.
3. En el ordenador, escribe la dirección, el puerto y el código que salen en la pantalla:

| Paso | Orden |
| --- | --- |
| Vincular, solo la primera vez | `adb pair <IP>:<puerto de vinculación> <código>` |
| Conectar | `adb connect <IP>:<puerto>` |

El puerto para conectar cambia cada vez que se activa: míralo en **Depuración inalámbrica**.

## Por cable

Hace falta el mismo cable que para instalar Home: en el Rev5, con el adaptador al conector interno. Lo tienes en la [guía de instalación](../INSTALAR.md#2-saber-si-es-rev4-o-rev5-y-conectarlo-al-pc).

> [!IMPORTANT]
> Con el cable USB del ordenador puesto, la pantalla no termina de arrancar. Quítalo antes de reiniciarla.

## Apagarlo

En **Opciones para desarrolladores**, desactiva **Depuración por USB** y **Depuración inalámbrica**.
