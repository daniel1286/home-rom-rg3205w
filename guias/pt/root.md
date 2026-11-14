# Root com o Magisk

Com root, as apps a que deres permissão podem alterar todo o sistema. O Home traz o Magisk preparado, mas o root vem desligado: só é ativado se o pedires.

> [!CAUTION]
> Uma app com root pode estragar o sistema ou ler tudo o que está no ecrã. Ativa-o só se souberes para que precisas dele, e dá permissão só a apps de confiança.

## Ativar no assistente

Em **Opções avançadas → Root (Magisk)**, ativa **Permitir root com o Magisk**. Ao aplicar, é instalada a app do Magisk.

A partir daí, sempre que uma app pede root, o Magisk pergunta-te antes de o dar. A única que o recebe sem perguntar é o Fully Kiosk, se usares o painel do Home Assistant.

## Ativar ou desativar depois

O root é decidido ao ligar o ecrã, conforme uma definição. Se não o ativaste no assistente, muda-se com o [ADB](adb.md):

| Para | Comando |
| --- | --- |
| Ativar | `adb shell settings put global home_root 1` |
| Desativar | `adb shell settings put global home_root 0` |

Depois, reinicia o ecrã. Com o root ativado, a app do Magisk instala-se sozinha ao arrancar. Com o root desativado, nenhuma app o recebe; a app do Magisk pode ser desinstalada como qualquer outra.

## As atualizações

As atualizações do Home mantêm o root como estiver: a definição não muda. O Magisk vem sempre dentro do Home e é atualizado com cada versão.
