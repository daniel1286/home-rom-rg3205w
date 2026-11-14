# Primeiros passos

Da primeira vez que é ligado, o Home abre um assistente que deixa o ecrã pronto em poucos minutos. Aqui fica o que cada passo pede, o que convém escolher e onde se muda depois.

## Antes de começar

- O ecrã tem de estar ligado à corrente. Não tem bateria: se for desligado da tomada, apaga-se.
- Tem à mão a palavra-passe do teu Wi-Fi.
- Se o vais usar como painel do Home Assistant ou como coluna da casa, deixa o teu servidor ligado: o assistente procura-o na rede.

Em todos os passos tens **Voltar** em baixo à esquerda e **Seguinte** em baixo à direita. Quase nada é aplicado até ao fim, por isso podes avançar e recuar à vontade.

## Idioma, região e texto

**Olá.** Escolhe o idioma: o assistente muda logo e o ecrã fica nesse idioma. Depois toca em **Começar**.

**Região e hora.** O fuso horário (Espanha peninsular e Baleares, Canárias, Ceuta e Melilla ou Portugal), se a hora é obtida da Internet e se a queres no formato de 24 horas.

**Tamanho do texto.** Normal, Grande ou Muito grande. Ao tocar num tamanho, todo o assistente muda para veres como fica. Vale para todas as apps do Home, incluindo a proteção de ecrã.

## Wi-Fi e nome

**Wi-Fi.** Escolhe a tua rede, escreve a palavra-passe e toca em **Ligar**. Se a rede não aparecer, toca em **Procurar de novo**. Podes saltar este passo, mas sem ligação não é possível instalar o painel do Home Assistant nem acertar a hora automaticamente.

**Nome.** Como se vai chamar o ecrã na tua rede, por Bluetooth e ao projetar. Se tiveres mais do que um em casa, dá-lhe o nome da divisão: Sala, Cozinha, Entrada…

## O que queres instalar

Marca o que vais usar. O que não marcares não é instalado e não ocupa espaço.

| Opção | Para quê |
| --- | --- |
| Painel do Home Assistant | O teu painel em ecrã inteiro, que abre sozinho ao ligar. Quem o mostra é o Fully Kiosk |
| Coluna da casa | Que o ecrã toque ao mesmo tempo que as restantes colunas, com o teu servidor de música |
| Controlar o ecrã a partir do PC | Ver e tocar no ecrã a partir de outro computador |
| F-Droid | Loja de apps livres e gratuitas |
| Aurora Store | Apps do Google Play sem conta Google |
| Ajuda | Este guia e, se algo falhar, contar o problema e ver a resposta |
| Monitor | Ver o ecrã por dentro: processador, memória, temperaturas e rede |

A Ajuda, o F-Droid e a Aurora Store vêm marcados; o Monitor, não. A Ajuda e o Monitor desinstalam-se depois como qualquer app.

Se marcares o painel ou a coluna, aparecem mais dois passos:

- **Home Assistant.** O assistente procura-o na tua rede. Se não o encontrar, escreve o endereço, por exemplo `homeassistant.local:8123`. Se o teu Home Assistant usar um certificado próprio, adiciona-o em **Opções avançadas**.
- **Coluna da casa.** Escolhe o teu servidor de música na lista ou escreve o endereço.

## Projetar e ecrã em repouso

**Projetar.** Permite que este ecrã receba a imagem e o som do iPhone, do Mac, do computador com Windows ou do telemóvel Android. Escolhe quem pode enviar:

- **Com código da primeira vez** (vem assim): da primeira vez, os aparelhos da Apple escrevem um código de quatro algarismos que aparece no ecrã, e os outros pedem autorização nele.
- **Qualquer pessoa da casa**: qualquer aparelho ligado à tua rede envia sem perguntar.
- **Com palavra-passe**: os aparelhos da Apple usam uma palavra-passe escolhida por ti; os outros pedem autorização da primeira vez.

Vem ativado. Se não o fores usar, desativa **Receber neste ecrã** e o Projetar é removido; podes instalá-lo quando quiseres em **Atualizações → Apps do Home**, em **Opcionais**.

**Ecrã em repouso.** O que acontece quando ninguém lhe toca:

- **Aparece a proteção de ecrã**: a hora, o tempo e os teus fundos. Escolhe ao fim de quanto tempo aparece e a tua cidade, que é de onde vêm o tempo, a chuva e os aviões.
- **Fica o que estiver** (vem assim): fica à frente o painel ou a app que tiveres aberta.

O despertador toca nos dois casos.

**Ecrã.** O brilho e, se não usares a proteção de ecrã, ao fim de quanto tempo se desliga. Se o usares como painel ou relógio, escolhe **Nunca**.

**Navegação.** Como te deslocas pelo ecrã: com **Gestos** (vem assim) ou com **Botões**, sempre à vista em baixo. Está explicado em [Navegar no Home](moverte-por-home.md).

## Privacidade e opções avançadas

**Privacidade.** Se o microfone e a câmara podem ser usados. A câmara vem desativada.

**Ajudar a melhorar o Home.** Se quiseres, o ecrã conta uma vez por dia como está configurado e se as atualizações correm bem. Vem desligado: só é enviado se o ativares. O passo indica o que é enviado e o que nunca é enviado.

**Opções avançadas.** IP fixo, endereço MAC, certificados próprios, depuração ADB e root. Se não precisares deles, toca em **Continuar**. Estão explicados na secção [Avançado](README.md#avançado).

## Resumo

Revê tudo. Toca numa linha para a alterar e, quando estiver tudo bem, toca em **Aplicar**.

O ecrã vai mostrando o que está a fazer. Não o desligues nem o tires da tomada entretanto. Se algo não correr bem, aparece em cima e podes voltar ao resumo; o resto já fica configurado. No fim, toca em **Começar a usar**. Não é preciso reiniciar.

## Onde se muda depois

| O quê | Onde |
| --- | --- |
| Idioma | Definições → Sistema → Idiomas |
| Tamanho do texto | Definições → Ecrã → Tamanho do tipo de letra |
| Wi-Fi | Definições → Rede e Internet |
| Nome | Definições → Acerca do dispositivo → Nome do dispositivo |
| Projetar | App Projetar |
| Proteção de ecrã | App Proteção de ecrã → Quando deixa de ser usado |
| Brilho e desligar | Definições → Ecrã |
| Gestos ou botões | Definições → Sistema → Gestos → Navegação no sistema |
| Ajudar a melhorar o Home | App Atualizações → Definições |
| Depuração ADB | Definições → Sistema → Opções de programador |
