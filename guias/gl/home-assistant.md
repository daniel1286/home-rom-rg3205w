# Panel de Home Assistant

A pantalla pode amosar o teu panel de Home Assistant a pantalla completa e abrilo soa cada vez que se acende. Faino Fully Kiosk, que o asistente instala se marcas **Panel de Home Assistant**.

## Como queda configurado

No asistente:

1. Marca **Panel de Home Assistant** en **Que queres instalar**.
2. No paso **Home Assistant**, escolle o teu da lista ou escribe o seu enderezo, por exemplo `homeassistant.local:8123`.

Ao aplicar, o asistente descarga Fully Kiosk da súa web, comproba que é o de verdade, ponlle o enderezo do teu Home Assistant e déixao como pantalla de inicio. Ao rematar, xa aparece o teu panel.

## Se o teu Home Assistant usa https cun certificado propio

Engade o certificado no asistente, en **Opcións avanzadas → Certificados propios** (un ficheiro .crt ou .pem), para que o panel o acepte. Tes isto en [IP fixa, MAC e certificados](red-y-certificados.md).

## Cambiar o enderezo

O enderezo cámbiase na configuración de Fully Kiosk: esvara desde o bordo esquerdo para abrir o seu menú, entra na súa configuración e cambia a páxina de inicio (**Start URL**).

Algunhas opcións de Fully son de pagamento; para amosar o panel non fan falta.

## Co protector de pantalla

Se queres que apareza o protector de pantalla de Home co panel:

- En Fully, apaga a súa opción para manter a pantalla acendida (**Keep Screen On**). Se non, o protector de pantalla non aparece nunca.
- Non uses á vez o protector de pantalla de Fully.

Máis en [O protector de pantalla](salvapantallas.md).

## Volver ao inicio de sempre

Se deixas de usar o panel, cambia a pantalla de inicio: esvara desde arriba, abre **Configuración** coa roda dentada e vai a **Aplicacións → Aplicacións predeterminadas → Aplicación de inicio**. Escolle **Trebuchet**, o inicio de Android.
