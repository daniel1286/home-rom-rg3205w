# Reinstalar o Home

Se quiseres deixar o ecrã como novo, ou se algo correu tão mal que já não arranca, podes reinstalar o Home a partir de um computador. Para ficar em dia não é preciso: basta [atualizar](actualizar.md).

> [!WARNING]
> Instalar o Home a partir do computador apaga tudo o que está no ecrã: apps, definições e dados.

## O que é preciso

- Um computador com Windows 10 ou 11 de 64 bits.
- O cabo USB com que instalaste o Home. No Rev5, com o adaptador ligado ao conector interno.
- O instalador, [Instalar-Home.exe](https://github.com/daniel1286/home-instalador-rg3205w/releases/latest/download/Instalar-Home.exe), que transfere o Home e o instala numa janela.

## Como se faz

O [guia de instalação](../INSTALL.md), em inglês, explica-o passo a passo. Com o Home já instalado, entrar no fastboot é mais fácil do que da primeira vez:

- A partir do [recovery](recovery.md): **Reiniciar → Bootloader**.
- Ou com o [ADB](adb.md): `adb reboot bootloader`.

## Se não arrancar nem entrar no fastboot

Resta o resgate por EDL, o modo de emergência do processador. É para quem tem alguma experiência: está explicado no [guia de instalação](../INSTALL.md#11-backup-and-rescue-over-edl).
