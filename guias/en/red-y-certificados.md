# Static IP, MAC and certificates

Options for your own networks and servers. If you're not sure whether you need them, you don't: everything works with the defaults.

## Static IP

Normally the router gives the screen its IP address. If you want it to always have the same one, for example to connect over ADB or from Home Assistant:

- **In the setup wizard**, under **Advanced options → Static IP**: the IP, the gateway and the DNS. You need to connect to Wi-Fi first.
- **Later**, in **Settings → Network & internet → Internet**, tap the gear next to your network, then the pencil, and under **Advanced options → IP settings** choose **Static**.

Another way, without touching the screen: reserve the IP in your router for the screen's MAC address.

## MAC address

It's the number your router recognizes the screen by. In the setup wizard, under **Advanced options → MAC address**:

| Option | What it does |
| --- | --- |
| Keep the factory one | The device's original one. This is the default |
| Generate a new one | A random one, fixed for your network: the router sees a new screen |

Later, you change it in your network's settings, under **Privacy**: **Use randomized MAC** or **Use device MAC**.

## Own certificates

If your home servers use https with their own certificate, the screen needs to know it to trust them.

- **In the setup wizard**, under **Advanced options → Own certificates**, tap **Add certificate** and choose the .crt or .pem file.
- **Later**, in **Settings → Security & privacy → More security settings → Encryption & credentials → Install a certificate → CA certificate**.

They're kept in the user store. To remove them, go to **Encryption & credentials → Trusted credentials**, **User** tab.
