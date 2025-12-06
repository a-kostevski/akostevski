---
title: "Christmas Wish List 2025"
date: 2025-12-01
description: "Things I'd actually use"
hidemeta: true
---

Du har hamnat här för du frågat vad jag önskar mig i present/gåva.
Jag kommer

---

## The nerdy stuff

### ESP32 projekt

I want to build a Bluetooth receiver for my smart scale so it talks to Home Assistant instead of some Chinese cloud. Pretty cheap project:

- [Seeed XIAO ESP32-C3](https://www.electrokit.com/xiao-esp32c3)
  – Billigt och gör det den ska (100 sek)
- [ESP32-S3 DevKitC](https://www.electrokit.com/esp32-s3-devkitc-1-u-n8r2)
  - Lite dyrare och gör lite mer (200 sek)
- [Arduino sensor](https://www.electrokit.com/arduino-nano-esp32-with-headers)
  - Dyrast och ger gott om utrymme för hopp och lek
    <https://www.digikey.se/sv/products/detail/olimex-ltd/ESP32-POE/10258717?utm_source=chatgpt.com>

### Smart home

I have Home Assistant running with a SkyConnect dongle (Zigbee/Thread) but not many devices actually using it yet. The Hue bridge works fine but I'd rather have everything local.

**Sensors:**

- [Aqara door/window sensors](https://www.kjell.com/se/produkter/smarta-hem/xiaomi-mi-smart-home/sensorer/aqara-dorr-och-fonstersensor-p51520) x 3 (ca 150 SEK styck)
  - Stängde jag verkligen dörren och fönstrena där hemma?
    – temperatur/luftfuktighet med skärm, nice for the balcony (~100 SEK)
- [Aqara motion sensor P1](https://www.kjell.com/se/varumarken/aqara).
  - Zigbee 3.0 rörelsedetektor (ca 200 SEK)
- [Aqara water leak sensor](https://www.kjell.com/se/produkter/sakerhet-overvakning/vattenlarm/aqara-t1-lackagedetektor-p57866) x 2 (ca 240 SEK st)
  - En under diskmaskinen och en under vasken
- [Frient Smart Energimätare](https://www.kjell.com/se/produkter/smarta-hem/smarta-sensorer/smarta-energimatare/frient-smart-energimatare-for-elcentral-p52023)
  - Få koll på erlförbrukning (ca 700 SEKF)
- [Thermometer & Hygrometer](https://www.kjell.com/se/produkter/smarta-hem/smarta-hem-losningar/aqara-smarta-hem/aqara-t1-termometer-och-hygrometer-p57864) (ca 230 SEK)
  - Hur ska man annars veta hur varmt det är inomhus?
- [Athom Smart Plugs](https://www.athom.tech/blank-1/tasmota-esp32-c3-eu-plug-v3)
  - Smarta uttag
    **Switches and control:**

- [Shelly Plus 1 Mini](https://www.kjell.com/se/produkter/smarta-hem/shelly/shelly-plus-1-mini-gen-3-p51900)
  - fits behind existing switches, WiFi based so no hub needed (~200 SEK)

- [Aqara FP2](https://www.kjell.com/se/produkter/smarta-hem/smarta-hem-losningar/aqara-smarta-hem/aqara-presence-sensor-fp2-narvarosensor-p65051) – mmWave presence sensor, knows if someone's in the room even if they're sitting still. Actually useful for automations unlike PIR sensors (~1,200 SEK)
- [Everything Presence One](https://shop.everythingsmart.io/products/everything-presence-one-kit) – similar to FP2 but more hackable, runs ESPHome (~500 SEK)

### Homelab

**Power**

- [APC Back-UPS 650VA](https://www.komplett.se/product/1177245/datorutrustning/ups-stromfilter/ups/apc-back-ups-650va) – the router and switch really should be on battery backup (~1,200 SEK)
- [APC Back-UPS 1600VA](https://www.komplett.se/search?q=apc+1600va) – if you want to cover the servers too (~2,500 SEK)
- [Eaton 5E 850i](https://www.dustinhome.se/search?query=eaton+5e+850) – alternative to APC, similar specs (~1,000 SEK)

<!-- ### NAS project -->
<!---->
<!-- I've been thinking about building a proper NAS instead of running everything on the ProBook. A few options: -->
<!---->
<!-- - [Jonsbo N2](https://www.inet.se/produkt/6911032/jonsbo-n2-svart) – fits 5× 3.5" drives in a tiny case, looks like a piece of furniture. Needs an ITX board (~1,500 SEK for case only) -->
<!-- - [Fractal Node 304](https://www.inet.se/produkt/6901163/fractal-design-node-304-svart) – 6× 3.5" bays, been around forever, works great (~1,000 SEK) -->
<!---->
<!-- **Parts if building from scratch:** -->
<!---->
<!-- - Intel N100 board like the [CWWK N100](https://www.aliexpress.com/w/wholesale-cwwk-n100.html) – similar to my router, 6W TDP, has 4 SATA ports (~1,200 SEK from AliExpress) -->
<!-- - [WD Red Plus 4TB](https://www.inet.se/produkt/4401003/wd-red-plus-4tb) × 2 minimum -->
<!--   - Man kan aldrig ha för mycket minne. -->
<!-- - [Seagate IronWolf 4TB](https://www.inet.se/produkt/4401215/seagate-ironwolf-4tb) -->
<!--   – alternativ till WD( -->
<!-- - [PicoPSU 120W](https://www.amazon.se/dp/B005TWE5E6) + laptop brick – quieter than ATX PSU (~400 SEK) -->
<!---->

### Security and hacking

For learning and labbing. I have the network segmentation already, just need tools.

**Vuxenleksaker:**

- [YubiKey 5 NFC](https://www.kjell.com/se/varumarken/yubico/dator/datortillbehor/sakerhetsnycklar/yubico-yubikey-5c-nfc-sakerhetsnyckel-med-usb-c-p65607)
  - hardware security key, works for SSH, GPG, and 2FA. I should really be using these (~900 SEK)
- [Flipper Zero](https://shop.flipperzero.one/products/flipper-zero)
  - fun for learning about RFID, NFC, IR, sub-GHz radio. Every security person seems to have one (~2,500 SEK)

- [WiFi Pineapple](https://shop.hak5.org/products/wifi-pineapple)
  - dedicated rogue AP platform, overkill but cool (~1,500 SEK from Hak5)

- [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky?variant=353378649)
  - looks like a USB drive, types payloads. Good for demonstrating why you don't plug in random USB devices (~500 SEK from Hak5)
- [Proxmark3 Easy](https://www.amazon.se/dp/B09LYGMD4B)
  - RFID/NFC cloner and analyzer, way more capable than Flipper for card stuff (~600 SEK)
- [HackRF One](https://www.amazon.se/dp/B01JMQEKEG)
  - SDR that covers 1 MHz to 6 GHz, transmit and receive. For radio exploration (~2,500 SEK)
- [RTL-SDR v4](https://www.amazon.se/dp/B0CD7558GT)
  -cheaper receive-only SDR, good for learning (~400 SEK)
- [LAN Turtle](https://shop.hak5.org/products/lan-turtle)
  - covert ethernet implant for pentesting. Sits inline and gives you remote access (~700 SEK from Hak5)
- [Throwing Star LAN Tap](https://shop.hak5.org/products/throwing-star-lan-tap)
  - passive network tap for packet capture (~200 SEK)

---

## Reading

- **[Kobo Clara BW](https://www.elgiganten.se/product/mobiler-tablets-smartklockor/lasplatta/kobo-clara-bw-lasplatta-16gb-svart/767065)**
  - works with Calibre, no Amazon lock-in. This is what I actually want. ~2,000 SEK

---

<!---->
<!-- - "Practical Packet Analysis" by Chris Sanders – Wireshark deep dive -->
<!-- - "The Web Application Hacker's Handbook" – dated but still solid foundations -->
<!-- - "Penetration Testing" by Georgia Weidman – hands-on intro -->
<!-- - "Black Hat Python" – practical Python for security -->
<!-- - "Hacking APIs" – web API security testing -->
<!-- - "The Hacker Playbook 3" – red team tactics -->
<!-- - "Building Secure & Reliable Systems" – Google's SRE security book (free PDF) -->

**Learning platforms:**

- [TryHackMe](https://tryhackme.com/) premium subscription
  - guided rooms, good for learning. Has paths for different topics (~800 SEK/year)
- [Hack The Box](https://www.hackthebox.com/) VIP
  - more CTF-style, harder boxes, good once you know basics (~1,000 SEK/year)
- [PentesterLab Pro](https://pentesterlab.com/)
  - hands-on web security exercises (~900 SEK/year)
- [OffSec Learn One](https://www.offsec.com/courses/learn-one/)
  - expensive but includes OSCP prep if I ever go that route (~15,000 SEK/year)

---

## Where to buy

Most of this stuff is available at:

- [Kjell & Company](https://www.kjell.com/se) – smart home, cables, ESP32 stuff
- [Inet](https://www.inet.se/) – tech, networking, storage, cases
- [Webhallen](https://www.webhallen.com/) – gaming, electronics
- [Komplett](https://www.komplett.se/) – general tech, UPS
- [Amazon.se](https://www.amazon.se/) – when nowhere else has it
- [Electrokit](https://www.electrokit.com/) – electronics components
- [Dustin Home](https://www.dustinhome.se/) – YubiKeys, business stuff
- [Adlibris](https://www.adlibris.com/se) – books
- [Cykelkraft](https://www.cykelkraft.se/) – bike stuff
- [Hak5](https://shop.hak5.org/) – security hardware (ships from US)
- [IKEA](https://www.ikea.com/se/sv/) – surprisingly good for cheap Zigbee stuff
- [Tradera](https://www.tradera.com/) / [Blocket](https://www.blocket.se/) – used hardware
