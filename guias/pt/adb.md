# Depuração ADB

O ADB permite controlar o ecrã a partir de um computador com comandos: instalar apps, ver o registo, copiar ficheiros. Vem desativado e é só para quem precisa.

> [!WARNING]
> Com o ADB ativado, quem tiver acesso à tua rede pode tentar controlar o ecrã. Ativa-o só enquanto o usares e desativa-o no fim.

## Ativá-lo

### No assistente

Em **Opções avançadas → Depuração (ADB)**. Fica ativado por USB e por Wi-Fi, e a tua rede fica aceite para a depuração sem fios.

### Depois, nas Definições

1. Em **Definições → Acerca do dispositivo**, toca sete vezes em **Número de compilação**. Aparecem as **Opções de programador**.
2. Entra em **Definições → Sistema → Opções de programador**.
3. Ativa **Depuração USB** ou **Depuração sem fios**.

Da primeira vez que um computador se ligar, o ecrã pergunta se o autorizas.

## Por Wi-Fi

1. Em **Opções de programador**, entra em **Depuração sem fios**.
2. Toca em **Sincronizar dispositivo com código de sincronização**.
3. No computador, escreve o endereço, a porta e o código que aparecem no ecrã:

| Passo | Comando |
| --- | --- |
| Sincronizar, só da primeira vez | `adb pair <IP>:<porta de sincronização> <código>` |
| Ligar | `adb connect <IP>:<porta>` |

A porta para ligar muda sempre que a depuração é ativada: vê-a em **Depuração sem fios**.

## Por cabo

É preciso o mesmo cabo que para instalar o Home: no Rev5, com o adaptador ligado ao conector interno. Está explicado no [guia de instalação](../INSTALL.md#2-rev4-or-rev5-and-connecting-it-to-the-pc), em inglês.

> [!IMPORTANT]
> Com o cabo USB do computador ligado, o ecrã não acaba de arrancar. Retira-o antes de o reiniciar.

## Desativá-lo

Em **Opções de programador**, desativa **Depuração USB** e **Depuração sem fios**.
