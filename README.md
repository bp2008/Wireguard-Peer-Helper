# Wireguard-Peer-Helper
A single page web application helpful for generating WireGuard configuration files for clients when your wireguard system does not support config file generation (e.g. pfsense routers). This project requires a solid understanding of WireGuard configuration.

## Demo

You can run this application directly from the following URL:  
https://bp2008.github.io/Wireguard-Peer-Helper/index.html

Alternatively, download the `index.html` file and open it in a web browser.

Tunnels and peers added within the application are saved in the browser's local storage.  It is highly recommended to delete peers after exporting their configuration files, to prevent leaking their private keys.
