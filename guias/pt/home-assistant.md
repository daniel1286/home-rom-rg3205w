# Painel do Home Assistant

O ecrã pode mostrar o teu painel do Home Assistant em ecrã inteiro e abri-lo sozinho sempre que é ligado. Quem o faz é o Fully Kiosk, que o assistente instala se marcares **Painel do Home Assistant**.

## Como fica configurado

No assistente:

1. Marca **Painel do Home Assistant** em **O que queres instalar**.
2. No passo **Home Assistant**, escolhe o teu na lista ou escreve o endereço, por exemplo `homeassistant.local:8123`.

Ao aplicar, o assistente transfere o Fully Kiosk do site oficial, verifica que é o verdadeiro, configura-o com o endereço do teu Home Assistant e deixa-o como app inicial. No fim, o teu painel já aparece.

## Se o teu Home Assistant usar https com um certificado próprio

Adiciona o certificado no assistente, em **Opções avançadas → Certificados próprios** (um ficheiro .crt ou .pem), para que o painel o aceite. Está explicado em [IP fixo, MAC e certificados](red-y-certificados.md).

## Mudar o endereço

O endereço muda-se nas definições do Fully Kiosk: desliza a partir da margem esquerda para abrir o menu, entra nas definições e altera a página inicial (**Start URL**).

Algumas opções do Fully são pagas; para mostrar o painel não são precisas.

## Com a proteção de ecrã

Se quiseres que a proteção de ecrã do Home apareça com o painel:

- No Fully, desliga a opção que mantém o ecrã ligado (**Keep Screen On**). Caso contrário, a proteção de ecrã nunca aparece.
- Não uses ao mesmo tempo a proteção de ecrã do Fully.

Mais informações em [A proteção de ecrã](salvapantallas.md).

## Voltar à app inicial de sempre

Se deixares de usar o painel, muda a app inicial: desliza a partir de cima, abre as **Definições** com a roda dentada e vai a **Apps → Apps predefinidas → App inicial**. Escolhe **Trebuchet**, a que o Android traz de origem.
