# EtherWalletGUI
A lightweight wallet implementation. At the moment it supports key creation and conversion between various formats.

It is complemented by the following packages:
- [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) to sign transactions
- [ethereumjs-icap](https://github.com/ethereumjs/ethereumjs-icap) to manipulate ICAP addresses
- [store.js](https://github.com/marcuswestin/store.js) to use browser storage

Motivations are:
- be lightweight
- work in a browser
- use a single, maintained version of crypto library (and that should be in line with `ethereumjs-util` and `ethereumjs-tx`)
- support import/export between various wallet formats
- support BIP32 HD keys

Features not supported:
- signing transactions
- managing storage (neither in node.js or the browser)

## Preview

<div align="center">
  <img src="https://raw.githubusercontent.com/0xc0d3x/EtherWalletGUI/0xc0d3x-release-1/info.png"/>
  <br>
  <img src="https://raw.githubusercontent.com/0xc0d3x/EtherWalletGUI/0xc0d3x-release-1/send.png"/>
</div>
