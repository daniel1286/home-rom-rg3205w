# IP fixo, MAC e certificados

Opções para redes e servidores próprios. Se não sabes se precisas delas, não precisas: com o que vem de origem, tudo funciona.

## IP fixo

Normalmente é o router que dá ao ecrã o seu endereço IP. Se quiseres que tenha sempre o mesmo, por exemplo para entrar por ADB ou a partir do Home Assistant:

- **No assistente**, em **Opções avançadas → IP fixo**: o IP, o gateway e o DNS. Primeiro é preciso ligar o Wi-Fi.
- **Depois**, em **Definições → Rede e Internet → Internet**, toca na roda dentada da tua rede, depois no lápis, e em **Opções avançadas → Definições de IP** escolhe **Estático**.

Outra forma, sem mexer no ecrã: reserva o IP no teu router para o endereço MAC do ecrã.

## Endereço MAC

É o número com que o router reconhece o ecrã. No assistente, em **Opções avançadas → Endereço MAC**:

| Opção | O que faz |
| --- | --- |
| Manter o de fábrica | O de sempre do aparelho. É o que vem de origem |
| Gerar um novo | Um aleatório, fixo para a tua rede: o router vê um ecrã novo |

Depois, muda-se nas definições da tua rede, em **Privacidade**: **Utilizar MAC aleatório** ou **Utilizar MAC do dispositivo**.

## Certificados próprios

Se os teus servidores de casa usarem https com um certificado próprio, o ecrã tem de o conhecer para confiar neles.

- **No assistente**, em **Opções avançadas → Certificados próprios**, toca em **Adicionar certificado** e escolhe o ficheiro .crt ou .pem.
- **Depois**, em **Definições → Segurança e privacidade → Mais definições de segurança → Encriptação e credenciais → Instalar um certificado → Certificado da AC**.

Ficam guardados no armazenamento do utilizador. Para os remover, vai a **Encriptação e credenciais → Credenciais fidedignas**, separador **Utilizador**.
