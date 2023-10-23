This is a vanilla JavaScript example how to use Web3modal with different  wallet providers.

The example works with

* In-browser wallets (MetaMask, Opera, Brave),

* Mobile wallets through QR code scanning (WalletConnect)

* Account-based wallets (Fortmatic, others)

The code uses simple unprocessed in-browser JavaScript.
Dependencies, like the Web3Modal library itself,
are loaded over Unpkg CDN. The code is extensively
commented and short.

# Web3 wallets and HTTPS hosting limitations

Because of limitations how wallet operate within a web browser
and web security,
you should not run this example, or any Web3modal code,
out of your file system or insecure HTTP protocol
(even using localhost).

The APIs of different wallet providers
may fail in funny and obscure way.
Assuming you have a working Node environment set up on a UNIX
system you can do:

```sh
npm i -g --only=prod https-localhost
sudo serve .
```


