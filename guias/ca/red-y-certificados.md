# IP fixa, MAC i certificats

Opcions per a xarxes i servidors propis. Si no saps si les necessites, és que no les necessites: amb el que ve de sèrie, tot funciona.

## IP fixa

Normalment el router dona a la pantalla la seva adreça IP. Si vols que tingui sempre la mateixa, per exemple per entrar-hi per ADB o des de Home Assistant:

- **A l'assistent**, a **Opcions avançades → IP fixa**: la IP, la porta d'enllaç i el DNS. Primer cal connectar la Wi-Fi.
- **Després**, a **Configuració → Xarxa i Internet → Internet**, toca la roda dentada de la teva xarxa, després el llapis, i a **Opcions avançades → Configuració d'IP** tria **Estàtica**.

Una altra manera, sense tocar la pantalla: reserva la IP al teu router per a l'adreça MAC de la pantalla.

## Adreça MAC

És el número amb què el router reconeix la pantalla. A l'assistent, a **Opcions avançades → Adreça MAC**:

| Opció | Què fa |
| --- | --- |
| Mantén la de fàbrica | La de sempre de l'aparell. És el que ve de sèrie |
| Genera'n una de nova | Una a l'atzar, fixa per a la teva xarxa: el router veu una pantalla nova |

Després es canvia a la configuració de la teva xarxa, a **Privadesa**: **Utilitza una adreça MAC aleatòria** o **Utilitza l'adreça MAC del dispositiu**.

## Certificats propis

Si els teus servidors de casa fan servir https amb un certificat propi, la pantalla l'ha de conèixer per fiar-se'n.

- **A l'assistent**, a **Opcions avançades → Certificats propis**, toca **Afegeix un certificat** i tria el fitxer .crt o .pem.
- **Després**, a **Configuració → Seguretat i privadesa → Més opcions de seguretat → Encriptació i credencials → Instal·la un certificat → Certificat de CA**.

Queden al magatzem de l'usuari. Per treure'ls, ves a **Encriptació i credencials → Credencials de confiança**, pestanya **Usuari**.
