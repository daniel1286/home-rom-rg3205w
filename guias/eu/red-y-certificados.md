# IP finkoa, MAC helbidea eta ziurtagiriak

Sare eta zerbitzari propioetarako aukerak. Behar dituzun ez badakizu, ez dituzu behar: berez datorrenarekin, dena dabil.

## IP finkoa

Normalean, bideratzaileak ematen dio pantailari bere IP helbidea. Beti bera izatea nahi baduzu, adibidez ADB bidez edo Home Assistantetik sartzeko:

- **Laguntzailean**, **Aukera aurreratuak → IP finkoa** atalean: IPa, atebidea eta DNSa. Lehenik, Wi-Fi sarera konektatu behar da.
- **Gero**, **Ezarpenak → Sareak eta Internet → Internet** atalean, ukitu zure sarearen gurpila, gero arkatza, eta **Aukera aurreratuak → IP ezarpenak** atalean aukeratu **Estatikoa**.

Beste modu bat, pantaila ukitu gabe: erreserbatu IPa zure bideratzailean, pantailaren MAC helbidearentzat.

## MAC helbidea

Bideratzaileak pantaila ezagutzeko erabiltzen duen zenbakia da. Laguntzailean, **Aukera aurreratuak → MAC helbidea** atalean:

| Aukera | Zer egiten duen |
| --- | --- |
| Fabrikakoa mantendu | Gailuaren betikoa. Hori da berez datorrena |
| Berri bat sortu | Ausazko bat, zure sarerako finkoa: bideratzaileak pantaila berri bat ikusten du |

Gero, zure sarearen ezarpenetan aldatzen da, **Pribatutasuna** atalean: **Erabili ausaz aukeratutako MAC helbidea** edo **Erabili gailuaren MAC helbidea**.

## Ziurtagiri propioak

Etxeko zerbitzariek https eta ziurtagiri propioa erabiltzen badituzte, pantailak ezagutu egin behar du haietaz fidatzeko.

- **Laguntzailean**, **Aukera aurreratuak → Ziurtagiri propioak** atalean, ukitu **Gehitu ziurtagiria** eta aukeratu .crt edo .pem fitxategia.
- **Gero**, **Ezarpenak → Segurtasuna eta pribatutasuna → Segurtasun-ezarpen gehiago → Enkriptatzea eta kredentzialak → Instalatu ziurtagiri bat → CA ziurtagiria** atalean.

Erabiltzailearen biltegian geratzen dira. Kentzeko, **Enkriptatzea eta kredentzialak → Kredentzial fidagarriak** atalean, **Erabiltzailea** fitxan.
