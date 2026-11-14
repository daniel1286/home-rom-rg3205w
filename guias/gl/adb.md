# Depuración ADB

ADB permite manexar a pantalla desde un ordenador con ordes: instalar apps, ver o rexistro, copiar ficheiros. Vén desactivado e é só para quen o precise.

> [!WARNING]
> Co ADB activado, quen teña acceso á túa rede pode tentar controlar a pantalla. Actívao só mentres o uses e apágao ao rematar.

## Activalo

### No asistente

En **Opcións avanzadas → Depuración (ADB)**. Queda activado por USB e por wifi, e a túa rede queda aceptada para a depuración sen fíos.

### Despois, desde Configuración

1. En **Configuración → Acerca do dispositivo**, toca sete veces **Número de compilación**. Aparecen as **Opcións de programador**.
2. Entra en **Configuración → Sistema → Opcións de programador**.
3. Activa **Depuración por USB** ou **Depuración sen fíos**.

A primeira vez que se conecte un ordenador, a pantalla pregunta se o autorizas.

## Por wifi

1. En **Opcións de programador**, entra en **Depuración sen fíos**.
2. Toca **Vincular dispositivo cun código de vinculación**.
3. No ordenador, escribe o enderezo, o porto e o código que aparecen na pantalla:

| Paso | Orde |
| --- | --- |
| Vincular, só a primeira vez | `adb pair <IP>:<porto de vinculación> <código>` |
| Conectar | `adb connect <IP>:<porto>` |

O porto para conectar cambia cada vez que se activa: mírao en **Depuración sen fíos**.

## Por cable

Fai falta o mesmo cable que para instalar Home: no Rev5, co adaptador ao conector interno. Tes isto na [guía de instalación](../INSTALAR.md#2-saber-si-es-rev4-o-rev5-y-conectarlo-al-pc).

> [!IMPORTANT]
> Co cable USB do ordenador posto, a pantalla non remata de arrincar. Quítao antes de reiniciala.

## Apagalo

En **Opcións de programador**, desactiva **Depuración por USB** e **Depuración sen fíos**.
