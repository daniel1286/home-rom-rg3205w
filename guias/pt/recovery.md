# O recovery

O recovery é um pequeno sistema à parte que arranca em vez do Home para instalar atualizações. O Home traz o TWRP com um design próprio, em espanhol. Normalmente não é preciso entrar nele: a app Atualizações usa-o sozinha.

## Quando aparece

- **Ao atualizar**: depois de **Instalar e reiniciar**, o ecrã arranca no recovery, instala a versão enquanto mostra o progresso e volta sozinho ao Home.
- **Se quiseres entrar por tua conta**, com o [ADB](adb.md): `adb reboot recovery`.

## O que se pode fazer

| Para | Toca em |
| --- | --- |
| Voltar ao Home | **Reiniciar → Sistema** |
| Ir para o fastboot, para reinstalar o Home | **Reiniciar → Bootloader** |
| Desligar | **Reiniciar → Apagar** |

> [!CAUTION]
> No recovery pode apagar-se tudo. Se não souberes o que faz uma opção, não lhe toques e volta ao Home com **Reiniciar → Sistema**.

## Se ficar no recovery

Se o recovery avisar de um erro ao instalar, toca em **Reiniciar → Sistema**. Ao arrancar, a app Atualizações diz o que aconteceu: está explicado em [Se uma atualização não for instalada](si-no-se-instala.md). Se o ecrã já não arrancar, [reinstala o Home](volver-a-instalar.md).
