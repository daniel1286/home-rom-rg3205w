# IP fixa, MAC e certificados

Opcións para redes e servidores propios. Se non sabes se as precisas, non as precisas: co que vén de serie, todo funciona.

## IP fixa

Normalmente o router dálle á pantalla o seu enderezo IP. Se queres que teña sempre o mesmo, por exemplo para entrar por ADB ou desde Home Assistant:

- **No asistente**, en **Opcións avanzadas → IP fixa**: a IP, a porta de enlace e o DNS. Primeiro hai que conectar a wifi.
- **Despois**, en **Configuración → Rede e Internet → Internet**, toca a roda dentada da túa rede, logo o lapis, e en **Opcións avanzadas → Configuración de IP** escolle **Estática**.

Outra forma, sen tocar a pantalla: reserva a IP no teu router para o enderezo MAC da pantalla.

## Enderezo MAC

É o número co que o router recoñece a pantalla. No asistente, en **Opcións avanzadas → Enderezo MAC**:

| Opción | Que fai |
| --- | --- |
| Manter a de fábrica | A de sempre do aparello. É o que vén de serie |
| Xerar unha nova | Unha ao chou, fixa para a túa rede: o router ve unha pantalla nova |

Despois cámbiase na configuración da túa rede, en **Privacidade**: **Usar MAC aleatorio** ou **Usar MAC do dispositivo**.

## Certificados propios

Se os teus servidores da casa usan https cun certificado propio, a pantalla ten que coñecelo para fiarse deles.

- **No asistente**, en **Opcións avanzadas → Certificados propios**, toca **Engadir certificado** e escolle o ficheiro .crt ou .pem.
- **Despois**, en **Configuración → Seguranza e privacidade → Máis configuración de seguranza → Encriptación e credenciais → Instalar un certificado → Certificado de CA**.

Quedan no almacén do usuario. Para quitalos, en **Encriptación e credenciais → Credenciais de confianza**, separador **Usuario**.
