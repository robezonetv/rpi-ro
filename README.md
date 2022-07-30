# Raspberry Pi _ Read Only

Potrebuji dost casto nastavovat RPI do stavu RO rezimu. Primarne pro delsi vydrz MicroSD karty. Aktualne provozuji jiz 6 let jednu MicroSD kartu, a stale funguje. Primarni problem je prepisovani stejneho mista na MicroSD karte, ale take problem pri vypadcich elektricke energie, kdy dochazi k spatnemu zapisu a poskozeni karty nebo dat na karte zapsanych.

## Zdroj & know-how
Postupoval jsem dle navodu od [Andreas Schallwig](https://medium.com/@andreas.schallwig/how-to-make-your-raspberry-pi-file-system-read-only-raspbian-stretch-80c0f7be7353).

Tento deployment je testovan na verzi IMG [2022-04-04-raspios-bullseye-armhf-lite.img](https://downloads.raspberrypi.org/raspios_lite_armhf/images/raspios_lite_armhf-2022-04-07/2022-04-04-raspios-bullseye-armhf-lite.img.xz)

Na verzich:
- pyansible: 2.13.2
- python: 3.9.2
- jinja: 3.1.2
