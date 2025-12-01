---
title: "Christmas Wish List 2025"
date: 2024-12-01
description: "Things I'd actually use"
hidemeta: true
---

For anyone wondering what to get me. Prices are approximate and I've linked Swedish stores where possible.

---

## The nerdy stuff

### ESP32 project parts

I want to build a Bluetooth receiver for my smart scale so it talks to Home Assistant instead of some Chinese cloud. Pretty cheap project:

- [Seeed XIAO ESP32-C3](https://www.electrokit.com/xiao-esp32c3) – tiny, USB-C powered, around 100 SEK
- Or the beefier [ESP32-S3 DevKitC](https://www.electrokit.com/esp32-s3-devkitc-1-u-n8r2) if I want to do more with it later (~200 SEK)
- A [battery holder](https://www.kjell.com/se/produkter/el-verktyg/arduino/tillbehor/batterihallare-for-18650-p87949) would be nice for making it portable

### Smart home

I have Home Assistant running with a SkyConnect dongle (Zigbee/Thread) but not many devices actually using it yet. The Hue bridge works fine but I'd rather have everything local.

**Sensors:**
- [Aqara door/window sensors](https://www.kjell.com/se/produkter/smarta-hem/xiaomi-mi-smart-home/sensorer/aqara-dorr-och-fonstersensor-p51520) – could use 2-3 more for the doors I haven't covered (~150 SEK each)
- [SONOFF SNZB-02D](https://www.amazon.se/dp/B0B6P4S8FF) – temperature/humidity with a screen, nice for the balcony (~100 SEK)
- [Aqara motion sensor P1](https://www.amazon.se/dp/B09QKVMMTB) – Zigbee 3.0, better range than the older ones (~200 SEK)
- [Aqara water leak sensor](https://www.amazon.se/dp/B07D39MSZS) – put one under the sink, one by the washing machine. Cheap insurance (~150 SEK each)
- [Soil moisture sensors](https://www.amazon.se/dp/B0BVWMRBWJ) – for the plants I keep forgetting to water (~150 SEK each)
- [IKEA VINDSTYRKA](https://www.ikea.com/se/sv/p/vindstyrka-luftkvalitetssensor-smart-60498242/) – air quality sensor, has PM2.5 and VOC. Works with SkyConnect (~300 SEK)

**Switches and control:**
- [Shelly Plus 1 Mini](https://www.kjell.com/se/produkter/smarta-hem/shelly/shelly-plus-1-mini-gen3-p51900) – fits behind existing switches, WiFi based so no hub needed (~200 SEK)
- [IKEA SOMRIG shortcut button](https://www.ikea.com/se/sv/p/somrig-genvaegsknapp-vit-smart-50563893/) – cheap Zigbee button, works with SkyConnect (~80 SEK)
- [IKEA TRADFRI shortcut button](https://www.ikea.com/se/sv/p/tradfri-genvaegsknapp-vit-smart-00517323/) – another cheap Zigbee option (~100 SEK)
- [Aqara Cube T1 Pro](https://www.amazon.se/dp/B0BLT7B5YN) – rotate/flip/shake to control things, surprisingly useful (~350 SEK)
- [IKEA RODRET dimmer](https://www.ikea.com/se/sv/p/rodret-fjaerrkontroll-vit-smart-80547836/) – two button Zigbee remote, good for bedside (~100 SEK)

**Zigbee network stuff:**
- [IKEA TRADFRI signal repeater](https://www.ikea.com/se/sv/p/tradfri-signalforstaerkare-30400396/) – Zigbee router, helps with range. I should have a few of these since the SkyConnect is USB-powered and weak on its own (~100 SEK)
- Any mains-powered Zigbee device acts as a router – the [IKEA smart plugs](https://www.ikea.com/se/sv/p/inspelning-smart-kontaktbrytare-00560878/) are cheap and extend the mesh (~130 SEK)
- [Sonoff Zigbee 3.0 USB dongle](https://www.amazon.se/dp/B09KXTCMSC) – backup coordinator in case SkyConnect dies (~200 SEK)

**The bigger stuff:**
- [Aqara FP2](https://www.amazon.se/dp/B0BXX7FZ2N) – mmWave presence sensor, knows if someone's in the room even if they're sitting still. Actually useful for automations unlike PIR sensors (~1,200 SEK)
- [Everything Presence One](https://shop.everythingsmart.io/products/everything-presence-one-kit) – similar to FP2 but more hackable, runs ESPHome (~500 SEK)
- [Shelly Pro 3EM](https://www.kjell.com/se/produkter/smarta-hem/shelly/shelly-pro-3em-p51839) – whole-house energy monitoring, goes in the electrical panel. Would be nice to see what's actually using power (~1,500 SEK)
- [Athom Smart Plugs](https://www.athom.tech/blank-1/tasmota-eu-plug-v2) with Tasmota pre-flashed – energy monitoring per device, runs locally (~200 SEK each)
- [Aqara smart lock U100](https://www.amazon.se/dp/B0BYX1GCQZ) – fingerprint + code + key, works with Home Assistant via Zigbee. No cloud needed (~2,500 SEK)

### Homelab

My home server is running out of space (95% full) and the office ThinkPad only has 4GB RAM which is painful.

**Storage - the urgent stuff:**
- [Samsung 870 EVO 2TB](https://www.inet.se/produkt/4401108/samsung-870-evo-2tb) – SATA SSD, would replace the full drive in the ProBook (~1,500 SEK)
- [NVMe enclosure](https://www.inet.se/produkt/4404879/icy-box-extern-m-2-nvme-ssd-ladd-usb-3-2-gen-2) – USB 3.2 Gen 2, for offsite backups (~400 SEK)

**Memory:**
- DDR3L SO-DIMM 8GB – the ThinkPad maxes out at 16GB total, even 8GB more would help a lot. It's old DDR3L 1600MHz. Check [Inet](https://www.inet.se/search?q=ddr3l+sodimm+8gb) or [Komplett](https://www.komplett.se/search?q=ddr3l+sodimm+8gb) (~250-400 SEK)

**Power:**
- [APC Back-UPS 650VA](https://www.komplett.se/product/1177245/datorutrustning/ups-stromfilter/ups/apc-back-ups-650va) – the router and switch really should be on battery backup (~1,200 SEK)
- [APC Back-UPS 1600VA](https://www.komplett.se/search?q=apc+1600va) – if you want to cover the servers too (~2,500 SEK)
- [Eaton 5E 850i](https://www.dustinhome.se/search?query=eaton+5e+850) – alternative to APC, similar specs (~1,000 SEK)

**Networking:**
- [QNAP QSW-1105-5T](https://www.inet.se/produkt/2203208/qnap-qsw-1105-5t-5-port-2-5gbe-switch) – 2.5GbE switch, the router already has 2.5G ports but everything else is gigabit (~900 SEK)
- [2.5G USB ethernet adapter](https://www.inet.se/produkt/3801016/tp-link-ue300-usb-3-0-gigabit-adapter) – for the laptops, to actually use that 2.5G switch (~300 SEK)
- More [Cat6A patch cables](https://www.kjell.com/se/search?query=cat6a) – you can never have enough

### NAS project

I've been thinking about building a proper NAS instead of running everything on the ProBook. A few options:

**The cheap way - used mini PC:**
- Used HP EliteDesk 800 G3/G4 mini or Lenovo ThinkCentre M720q – they show up on [Tradera](https://www.tradera.com/search?q=elitedesk+800+mini) and [Blocket](https://www.blocket.se/) for 1,000-2,000 SEK. Add drives and you're done.
- These have room for one 2.5" drive internally, but you can use USB for more

**The proper way - dedicated NAS case:**
- [Jonsbo N2](https://www.inet.se/produkt/6911032/jonsbo-n2-svart) – fits 5× 3.5" drives in a tiny case, looks like a piece of furniture. Needs an ITX board (~1,500 SEK for case only)
- [Fractal Node 304](https://www.inet.se/produkt/6901163/fractal-design-node-304-svart) – 6× 3.5" bays, been around forever, works great (~1,000 SEK)
- [TerraMaster F4-424 Pro](https://www.amazon.se/dp/B0CQ8Q5SN6) – if I want something prebuilt. 4-bay, N95 CPU, runs TrueNAS or whatever (~4,500 SEK)

**Parts if building from scratch:**
- Intel N100 board like the [CWWK N100](https://www.aliexpress.com/w/wholesale-cwwk-n100.html) – similar to my router, 6W TDP, has 4 SATA ports (~1,200 SEK from AliExpress)
- [WD Red Plus 4TB](https://www.inet.se/produkt/4401003/wd-red-plus-4tb) × 2 minimum for mirroring (~2,200 SEK)
- [Seagate IronWolf 4TB](https://www.inet.se/produkt/4401215/seagate-ironwolf-4tb) – alternative to WD (~1,100 SEK each)
- [PicoPSU 120W](https://www.amazon.se/dp/B005TWE5E6) + laptop brick – quieter than ATX PSU (~400 SEK)

**NAS software is free:**
- TrueNAS Scale – what I'd probably run, ZFS, Docker support
- Unraid – easier but costs money
- OpenMediaVault – Debian-based, simple

### Security and hacking

For learning and labbing. I have the network segmentation already, just need tools.

**Hardware:**
- [YubiKey 5 NFC](https://www.dustinhome.se/search?query=yubikey%205%20nfc) – hardware security key, works for SSH, GPG, and 2FA. I should really be using these (~600 SEK)
- [YubiKey 5C NFC](https://www.dustinhome.se/search?query=yubikey%205c%20nfc) – USB-C version for the laptop (~650 SEK)
- [Flipper Zero](https://www.amazon.se/dp/B0BJJNR8HR) – fun for learning about RFID, NFC, IR, sub-GHz radio. Every security person seems to have one (~2,500 SEK)

**WiFi stuff:**
- [Alfa AWUS036ACH](https://www.amazon.se/dp/B00VEEBOPG) – dual-band WiFi adapter, supports monitor mode and packet injection on Linux. The go-to for wireless pentesting (~500 SEK)
- [Alfa AWUS036ACHM](https://www.amazon.se/dp/B08SJBV1N3) – newer version, MediaTek chipset, better Linux support (~600 SEK)
- [WiFi Pineapple](https://shop.hak5.org/products/wifi-pineapple) – dedicated rogue AP platform, overkill but cool (~1,500 SEK from Hak5)

**Other toys:**
- [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky) – looks like a USB drive, types payloads. Good for demonstrating why you don't plug in random USB devices (~500 SEK from Hak5)
- [Proxmark3 Easy](https://www.amazon.se/dp/B09LYGMD4B) – RFID/NFC cloner and analyzer, way more capable than Flipper for card stuff (~600 SEK)
- [HackRF One](https://www.amazon.se/dp/B01JMQEKEG) – SDR that covers 1 MHz to 6 GHz, transmit and receive. For radio exploration (~2,500 SEK)
- [RTL-SDR v4](https://www.amazon.se/dp/B0CD7558GT) – cheaper receive-only SDR, good for learning (~400 SEK)
- [LAN Turtle](https://shop.hak5.org/products/lan-turtle) – covert ethernet implant for pentesting. Sits inline and gives you remote access (~700 SEK from Hak5)
- [Throwing Star LAN Tap](https://shop.hak5.org/products/throwing-star-lan-tap) – passive network tap for packet capture (~200 SEK)

**Books - actually useful ones:**
- "Practical Packet Analysis" by Chris Sanders – Wireshark deep dive
- "The Web Application Hacker's Handbook" – dated but still solid foundations
- "Penetration Testing" by Georgia Weidman – hands-on intro
- "Black Hat Python" – practical Python for security
- "Hacking APIs" – web API security testing
- "The Hacker Playbook 3" – red team tactics
- "Building Secure & Reliable Systems" – Google's SRE security book (free PDF)

Check [Adlibris](https://www.adlibris.com/se) for Swedish prices, usually 300-500 SEK each. Some are on [O'Reilly](https://www.oreilly.com/) if someone gets me that subscription.

**Learning platforms:**
- [TryHackMe](https://tryhackme.com/) premium subscription – guided rooms, good for learning. Has paths for different topics (~800 SEK/year)
- [Hack The Box](https://www.hackthebox.com/) VIP – more CTF-style, harder boxes, good once you know basics (~1,000 SEK/year)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) – free, excellent for web app security
- [PentesterLab Pro](https://pentesterlab.com/) – hands-on web security exercises (~900 SEK/year)
- [OffSec Learn One](https://www.offsec.com/courses/learn-one/) – expensive but includes OSCP prep if I ever go that route (~15,000 SEK/year)
- [O'Reilly Learning](https://www.oreilly.com/online-learning/) – all the books, videos, live training. Expensive but worth it if you use it (~4,000 SEK/year)

---

## Watch

I've been looking at fitness watches that don't require sending all my health data to some company. In order of how much I want them:

1. **[Withings ScanWatch 2](https://www.webhallen.com/se/search?query=scanwatch%202)** – looks like a real watch, syncs with their app but data is exportable. 38mm version. ~3,500 SEK
2. **[Garmin Forerunner 265](https://www.inet.se/produkt/6619413/garmin-forerunner-265-svart)** – ugly but very good. All data stays local if you want. ~4,500 SEK
3. **[Amazfit Balance](https://www.amazon.se/dp/B0CHXBF218)** – budget option, Zepp app is meh but works. ~2,000 SEK

---

## Cycling

My repair kit is basically non-existent right now:

- [Topeak Alien III](https://www.cykelkraft.se/topeak-alien-iii) – the Swiss army knife of bike multitools (~400 SEK)
- A proper mini pump, something like the [Topeak Roadie](https://www.cykelkraft.se/topeak-roadie-da-g) (~200 SEK)
- [Saddlebag](https://www.cykelkraft.se/topeak-aero-wedge-pack) to put it all in (~250 SEK)

Dream item: [Garmin Varia RTL515](https://www.inet.se/produkt/8701401/garmin-varia-rtl515-bakljus-radar) – it's a rear light with radar that warns you about cars approaching from behind. Sounds gimmicky but everyone who has one swears by it. ~2,200 SEK

---

## Gaming

Mostly play on PS5 these days.

- **PlayStation Store credit** – [500 SEK](https://www.webhallen.com/se/product/319159-PlayStation-Store-PSN-Ladda-ner-500-SEK) or [1000 SEK](https://www.webhallen.com/se/search?query=playstation%20store%201000), always useful
- **[SteelSeries Arctis Nova 7](https://www.inet.se/produkt/6606759/steelseries-arctis-nova-7-playstation-svart)** – wireless headset, works with PS5 and PC (~2,000 SEK)
- [8BitDo Ultimate Controller](https://www.webhallen.com/se/search?query=8bitdo%20ultimate) – good for retro games on the TV (~700 SEK)

---

## Reading

Currently reading on my phone which isn't great.

- **[Kobo Libra 2](https://www.elgiganten.se/search?search=kobo%20libra%202)** – works with Calibre, no Amazon lock-in. This is what I actually want. ~2,000 SEK
- [Kindle Paperwhite](https://www.amazon.se/dp/B09TMNTKGL) – fine if Kobo isn't available, just means I'm stuck with Amazon (~1,500 SEK)

---

## Coffee

I make pour-over most mornings. Could use:

- [Timemore C2 hand grinder](https://www.amazon.se/dp/B0833SDN8M) – way better than my current one (~600 SEK)
- [Hario V60 kit](https://www.kaffecompagniet.se/search?q=hario%20v60) if someone wants to get me a backup dripper (~350 SEK)
- Coffee beans from [Koppi](https://koppi.se/) or [Drop Coffee](https://dropcoffee.com/) – can never have too much good coffee

The [Fellow Stagg kettle](https://www.kaffecompagniet.se/search?q=fellow%20stagg) is beautiful and has temperature control but honestly hard to justify at 1,800 SEK for boiling water.

---

## Desk stuff

- [Logitech MX Master 3S](https://www.inet.se/produkt/6609605/logitech-mx-master-3s-gra) – my current mouse is dying (~1,000 SEK)
- [Keychron K3 Pro](https://www.maxgaming.se/search?q=keychron%20k3%20pro) – low profile mechanical keyboard (~1,100 SEK)

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
