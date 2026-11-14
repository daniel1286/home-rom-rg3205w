# Painel web

Com o painel web vês como está o ecrã e alteras as suas definições a partir do navegador do telemóvel ou do computador, sem lhe tocar. Só funciona dentro de casa e vem desligado: só o tem quem o escolhe.

## Ligá-lo

- **No assistente**, marca **Painel web** em **O que queres instalar**. Fica instalado e ligado.
- **Se atualizaste a partir da 2.0**, é proposto nas novidades da 2.1: **Instalar e ligar o painel web**.
- **Se não o marcaste**, instala-o a partir de **Atualizações → Apps do Home → Opcionais**, com **Instalar**. Fica instalado, mas desligado.
- **Se já o tens**, abre a app **Painel web** e ativa **Ligado**, em cima à direita.

Enquanto está ligado, há um aviso fixo, «Painel web ligado», com o botão **Desligar**.

## Emparelhar o telemóvel ou o computador

1. No ecrã, abre a app **Painel web**. Em **Abrir o painel** aparecem o endereço e um código QR.
2. Lê o código com o telemóvel, ou escreve o endereço tal como aparece, com o `:8443` do fim. Se o escreveres sem `https://`, o ecrã leva-te sozinho para a versão segura.
3. Da primeira vez, o navegador avisa que o certificado não é de uma autoridade conhecida. É normal: é deste ecrã. Confirma que a impressão digital (SHA-256) é a da app, que aparece em **Abrir o painel** por baixo do endereço. No navegador, vês a impressão digital tocando no aviso ou no cadeado junto ao endereço e abrindo os detalhes do certificado. Se coincidir, continua.
4. Em **Emparelhe este navegador**, toca em **Pedir o código**. No ecrã aparece o código de 6 algarismos; é válido durante 2 minutos.
5. Escreve-o em **Código do ecrã**. Se quiseres, dá um nome ao aparelho, para o reconheceres depois na lista.
6. Toca em **Emparelhar**.

Já estás no painel. Das próximas vezes, esse navegador entra diretamente, sem código.

> [!TIP]
> Se no ecrã aparecer um código que não pediste, toca em **Fechar** e esse código deixa de ser válido. Alguém da tua rede, incluindo o telemóvel de um convidado ligado ao teu Wi-Fi, está a tentar emparelhar um navegador.

## O que se pode fazer

| Parte | O que tem |
| --- | --- |
| Estado | Versão, temperatura, processador, memória, Wi-Fi e tempo ligado |
| Ecrã e som | Brilho, desligar ou ligar o ecrã, tamanho do texto e volume da música e dos alarmes |
| Proteção de ecrã | Se aparece, ao fim de quanto tempo e a cidade do tempo |
| Projetar | Ligá-lo ou desligá-lo, quem pode enviar e cortar o que está a receber |
| Atualizações | Se está atualizado, procurar agora e de quanto em quanto tempo procura sozinho. A instalação é sempre confirmada no ecrã |
| Aparelhos | Os navegadores emparelhados, quando foram usados pela última vez, e removê-los |
| Últimas alterações | O que foi alterado a partir do painel e a partir de que aparelho |
| Reiniciar | Com duas confirmações no navegador e uma contagem decrescente de 15 segundos no ecrã, com **Cancelar** |

O que nunca se pode fazer a partir do painel: alterar o Wi-Fi ou a sua palavra-passe, a depuração ADB, o root ou os certificados; instalar ou remover apps; ver o registo do sistema; usar a câmara ou o microfone.

## Seguro dentro de casa

- Só escuta no Wi-Fi de casa e rejeita o que não venha de lá. Não abre nada no router nem passa por nenhuma nuvem.
- Tudo vai cifrado (HTTPS), com um certificado próprio deste ecrã. A sua chave é guardada no armazenamento de chaves do Android e nunca sai do ecrã.
- Cada alteração aparece por momentos no ecrã e fica registada em **Últimas alterações**, com o aparelho que a fez.
- Um navegador que não seja usado durante 90 dias tem de voltar a ser emparelhado.

## Se não deixar emparelhar

| O que acontece | O que fazer |
| --- | --- |
| O código não aparece no ecrã | Abre a app **Painel web** no ecrã e toca em **Emparelhar**: aparece o código que está em uso ou um novo |
| «Esse não é o código. Restam … tentativas.» | Olha bem para o código do ecrã e escreve-o outra vez |
| «O código expirou. Peça outro.» | Passaram os 2 minutos: toca outra vez em **Pedir o código** |
| «Demasiadas tentativas com esse código. Peça outro.» | Pede um código novo |
| «Aguarde … segundos antes de pedir outro código.» | Espera o tempo indicado e volta a pedi-lo |
| «Já há 12 aparelhos emparelhados. Remova algum no ecrã.» | Na app, em **Aparelhos emparelhados**, remove algum que já não uses |

## Remover um aparelho ou desligar o painel

- **No ecrã**, na app **Painel web**: em **Aparelhos emparelhados**, toca em **Remover** num deles ou, se houver mais do que um, em **Remover todos**.
- **No navegador**: em **Aparelhos emparelhados**, na página, toca em **Remover** no que quiseres, ou em baixo em **Desemparelhar este navegador**. Esse navegador volta a pedir o código.
- **Desligá-lo**: toca em **Desligar** no aviso ou desativa **Ligado** na app. Desligado, não há nada à escuta.
- Se achares que alguém tem uma cópia do certificado, toca em **Criar um certificado novo** na app. A impressão digital muda e cada navegador volta a avisar mais uma vez.

## Removê-lo ou voltar a instalá-lo

O painel web desinstala-se como qualquer app e volta a instalar-se a partir de **Atualizações → Apps do Home → Opcionais**. Está explicado em [Remover ou voltar a instalar apps](quitar-o-poner-apps.md).

- Ao voltar a instalá-lo, fica desligado: abre a app e ativa **Ligado**.
- O ecrã cria outro certificado: cada navegador volta a avisar mais uma vez e é preciso emparelhá-los de novo.
- Ao atualizar o painel, pelo contrário, o certificado não muda e os navegadores continuam a entrar sem código.
