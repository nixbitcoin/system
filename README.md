# nixbitcoindev's system

This repository serves as a meta repository for my entire system setup. Here, you can find links to various guides and NixOS projects to help you deploy security-hardened and privacy-preserving self-hosted systems.

## Philosophy

* Extreme privacy
* Greatest possible security
* Easy deployment
* Dedicated bare-metal devices
* Always open to issues and PRs

## Projects

### [pfSense router](https://github.com/nixbitcoin/pfSense-guide)

Run a VLAN segmented network routed over multiple VPNs. Based on the rock solid pfSense. Includes config files. Graphical guide. Will stay pfSense for now, because FreeBSD's networking features are just too good.

### [Bitcoin Node](https://github.com/fort-nix/nix-bitcoin)

Run a fully-featured, security hardened, and privacy preserving Bitcoin node. Includes bitcoind, clightning, lnd, liquid, electrs and much more. Constantly under development. Deploy easily with NixOS.

### [Cloud server](https://github.com/nixbitcoin/OpenBSD-Nextcloud)

Control your own data and make it available from anywhere. Currently a guide based on OpenBSD. Will soon be an easily deployable NixOS project using NixOS 20.09, Nextcloud 21, hardened Nginx, Postgresql, and Krops with password-store protected secrets files.

### QubesOS + i3 laptop

Use the fully-compartmentalized QubesOS with a great window manager. All in dark mode. Graphical guide coming soon.

### Darknet Box

All three projects will be merged into one darknet box using NixOS.

#### [i2p relay](https://satmeir.com/posts/openbsd-i2pd)

Access the most underrated darknet out there. Chat on i2prc (i2p hidden irc), browse i2p sites, and use i2p mail all from your own 24/7 running i2p relay. Currently a guide based on OpenBSD. Will soon be an easily deployable NixOS project using NixOS 20.03, i2pd 2.32.1, and Krops with password-store protected secrets files.

#### Tor bridge

Provide secret uplinks to the Tor network for people with censored internet. Become a Tor network hero. Will soon be an easily deployable NixOS project using NixOS 20.03, Tor 0.4.3.5.

#### ZNC+Tor bouncer

Access the greatest chat rooms on earth with a ZNC bouncer routed over Tor. Easily deployable NixOS project using NixOS 20.03, ZNC 1.8.1, Tor 0.4.3.5, and Krops with password-store protected secrets files. Freenode instructions included.
