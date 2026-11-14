# Panel web

Co panel web ves como está a pantalla e cambias os seus axustes desde o navegador do móbil ou do ordenador, sen tocala. Só funciona dentro da casa e vén apagado: só o ten quen o escolle.

## Acendelo

- **No asistente**, marca **Panel web** en **Que queres instalar**. Queda instalado e acendido.
- **Se actualizaches desde a 2.0**, ofrécese nas novidades da 2.1: **Instalar e acender o panel web**.
- **Se non o marcaches**, ponlo desde **Actualizacións → Apps de Home → Opcionais**, con **Poñer**. Ponse apagado.
- **Se xa o tes**, abre a app **Panel web** e activa **Acendido**, arriba á dereita.

Mentres está acendido hai un aviso fixo, «Panel web acendido», co botón **Apagar**.

## Emparellar o móbil ou o ordenador

1. Na pantalla, abre a app **Panel web**. En **Abrir o panel** saen o enderezo e un código QR.
2. Escanea o código co móbil, ou escribe o enderezo tal como sae, co `:8443` do final. Se o escribes sen `https://`, a pantalla lévate soa á versión segura.
3. A primeira vez, o navegador avisa de que o certificado non é dunha autoridade coñecida. É normal: é desta pantalla. Comproba que a súa pegada (SHA-256) é a da app, que sae en **Abrir o panel** debaixo do enderezo. No navegador vese tocando o aviso ou o cadeado xunto ao enderezo e abrindo os detalles do certificado. Se coincide, continúa.
4. En **Emparella este navegador**, toca **Pedir o código**. Na pantalla sae o código de 6 cifras; vale 2 minutos.
5. Escríbeo en **Código da pantalla**. Se queres, ponlle un nome ao aparello, para recoñecelo despois na lista.
6. Toca **Emparellar**.

Xa estás no panel. As seguintes veces ese navegador entra directamente, sen código.

> [!TIP]
> Se na pantalla sae un código que non pediches, toca **Pechar** e ese código deixa de valer. Alguén da túa rede, tamén o móbil dun convidado conectado á túa wifi, está tentando emparellar un navegador.

## Que se pode facer

| Parte | Que hai |
| --- | --- |
| Estado | Versión, temperatura, procesador, memoria, wifi e tempo acendida |
| Pantalla e son | Brillo, apagar ou acender a pantalla, tamaño do texto e volume da música e das alarmas |
| Protector de pantalla | Se sae, aos cantos minutos e a cidade do tempo |
| Proxectar | Acendelo ou apagalo, quen pode enviar e cortar o que se está a recibir |
| Actualizacións | Se está ao día, buscar agora e cada canto busca soa. A instalación confírmase sempre na pantalla |
| Aparellos | Os navegadores emparellados, cando se usaron por última vez, e quitalos |
| Últimos cambios | Que se cambiou desde o panel e desde que aparello |
| Reiniciar | Con dúas confirmacións no navegador e unha conta atrás de 15 segundos na pantalla, con **Cancelar** |

O que nunca se pode facer desde o panel: cambiar a wifi ou o seu contrasinal, a depuración ADB, o root ou os certificados; instalar ou quitar apps; ver o rexistro do sistema; usar a cámara ou o micrófono.

## Seguro dentro da casa

- Só escoita na wifi da casa e rexeita o que non veña da casa. Non abre nada no router nin pasa por ningunha nube.
- Todo vai cifrado (HTTPS), cun certificado propio desta pantalla. A súa chave gárdase no almacén de chaves de Android e nunca sae da pantalla.
- Cada cambio sae un momento na pantalla e queda apuntado en **Últimos cambios**, co aparello que o fixo.
- Un navegador que non se usa en 90 días ten que volver emparellarse.

## Se non deixa emparellar

| O que pasa | Que facer |
| --- | --- |
| Non sae o código na pantalla | Abre a app **Panel web** na pantalla e toca **Emparellar**: sae o código que está en uso ou un novo |
| «Ese non é o código. Quedan … intentos.» | Mira ben o código da pantalla e escríbeo outra vez |
| «O código caducou. Pide outro.» | Pasaron os 2 minutos: toca **Pedir o código** outra vez |
| «Demasiados intentos con ese código. Pide outro.» | Pide un código novo |
| «Agarda … segundos antes de pedir outro código.» | Agarda o que di e volve pedilo |
| «Xa hai 12 aparellos emparellados. Quita algún desde a pantalla.» | Na app, en **Aparellos emparellados**, quita algún que xa non uses |

## Quitar un aparello ou apagar o panel

- **Na pantalla**, na app **Panel web**: en **Aparellos emparellados**, toca **Quitar** nun ou, se hai máis dun, **Quitar todos**.
- **No navegador**: en **Aparellos emparellados** da páxina, toca **Quitar** no que queiras, ou abaixo **Desemparellar este navegador**. Ese navegador volve pedir o código.
- **Apagalo**: toca **Apagar** no aviso ou desactiva **Acendido** na app. Apagado, non hai nada escoitando.
- Se cres que alguén ten unha copia do certificado, toca **Facer un certificado novo** na app. A pegada cambia e cada navegador avisará unha vez máis.

## Quitalo ou volver poñelo

O panel web desinstálase coma calquera app, e vólvese poñer desde **Actualizacións → Apps de Home → Opcionais**. Tes os pasos en [Quitar ou volver poñer apps](quitar-o-poner-apps.md).

- Ao volver poñelo instálase apagado: abre a app e activa **Acendido**.
- A pantalla fai outro certificado: cada navegador avisará unha vez máis e haberá que emparellalos de novo.
- Ao actualizar o panel, en cambio, o certificado non cambia e os navegadores seguen entrando sen código.
