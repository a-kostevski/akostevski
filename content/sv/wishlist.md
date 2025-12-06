---
title: "Önskelista Jul 2025"
date: 2025-12-01
description: "Saker jag faktiskt skulle använda"
hidemeta: true
---

Du har hamnat här för du frågat vad jag önskar mig i present/gåva.

---

## Nördigt

### ESP32 projekt

Jag vill bygga en Bluetooth-mottagare till min smarta våg så att den pratar med Home Assistant istället för något kinesiskt moln. Rätt billigt projekt:

- [Seeed XIAO ESP32-C3](https://www.electrokit.com/xiao-esp32c3)
  – Billigt och gör det den ska (100 kr)
- [ESP32-S3 DevKitC](https://www.electrokit.com/esp32-s3-devkitc-1-u-n8r2)
  - Lite dyrare och gör lite mer (200 kr)
- [Arduino sensor](https://www.electrokit.com/arduino-nano-esp32-with-headers)
  - Dyrast och ger gott om utrymme för hopp och lek
    <https://www.digikey.se/sv/products/detail/olimex-ltd/ESP32-POE/10258717?utm_source=chatgpt.com>

### Smarta hem

Jag har Home Assistant igång med en SkyConnect-dongel (Zigbee/Thread) men inte så många enheter som faktiskt använder det än. Hue-bryggan funkar bra men jag vill helst ha allt lokalt.

**Sensorer:**

- [Aqara dörr/fönstersensorer](https://www.kjell.com/se/produkter/smarta-hem/xiaomi-mi-smart-home/sensorer/aqara-dorr-och-fonstersensor-p51520) x 3 (ca 150 kr styck)
  - Stängde jag verkligen dörren och fönstren där hemma?
- [Aqara rörelsesensor P1](https://www.kjell.com/se/varumarken/aqara)
  - Zigbee 3.0 rörelsedetektor (ca 200 kr)
- [Aqara vattenläckagesensor](https://www.kjell.com/se/produkter/sakerhet-overvakning/vattenlarm/aqara-t1-lackagedetektor-p57866) x 2 (ca 240 kr st)
  - En under diskmaskinen och en under vasken
- [Frient Smart Energimätare](https://www.kjell.com/se/produkter/smarta-hem/smarta-sensorer/smarta-energimatare/frient-smart-energimatare-for-elcentral-p52023)
  - Få koll på elförbrukning (ca 700 kr)
- [Termometer & Hygrometer](https://www.kjell.com/se/produkter/smarta-hem/smarta-hem-losningar/aqara-smarta-hem/aqara-t1-termometer-och-hygrometer-p57864) (ca 230 kr)
  - Hur ska man annars veta hur varmt det är inomhus?
- [Athom Smart Plugs](https://www.athom.tech/blank-1/tasmota-esp32-c3-eu-plug-v3)
  - Smarta uttag

**Strömbrytare och styrning:**

- [Shelly Plus 1 Mini](https://www.kjell.com/se/produkter/smarta-hem/shelly/shelly-plus-1-mini-gen-3-p51900)
  - Passar bakom befintliga strömbrytare, WiFi-baserad så ingen hubb behövs (ca 200 kr)
- [Aqara FP2](https://www.kjell.com/se/produkter/smarta-hem/smarta-hem-losningar/aqara-smarta-hem/aqara-presence-sensor-fp2-narvarosensor-p65051) – mmWave närvarosensor, vet om någon är i rummet även om de sitter stilla. Faktiskt användbart för automationer till skillnad från PIR-sensorer (ca 1 200 kr)
- [Everything Presence One](https://shop.everythingsmart.io/products/everything-presence-one-kit) – liknande FP2 men mer hackbar, kör ESPHome (ca 500 kr)

### Hemmalabb

**Ström**

- [APC Back-UPS 650VA](https://www.komplett.se/product/1177245/datorutrustning/ups-stromfilter/ups/apc-back-ups-650va) – routern och switchen borde verkligen vara på batteribackup (ca 1 200 kr)
- [APC Back-UPS 1600VA](https://www.komplett.se/search?q=apc+1600va) – om du vill täcka servrarna också (ca 2 500 kr)
- [Eaton 5E 850i](https://www.dustinhome.se/search?query=eaton+5e+850) – alternativ till APC, liknande specifikationer (ca 1 000 kr)

### Säkerhet och hacking

För lärande och labbande. Jag har redan nätverkssegmenteringen, behöver bara verktyg.

**Vuxenleksaker:**

- [YubiKey 5 NFC](https://www.kjell.com/se/varumarken/yubico/dator/datortillbehor/sakerhetsnycklar/yubico-yubikey-5c-nfc-sakerhetsnyckel-med-usb-c-p65607)
  - Hårdvarusäkerhetsnyckel, fungerar för SSH, GPG och 2FA. Jag borde verkligen använda dessa (ca 900 kr)
- [Flipper Zero](https://shop.flipperzero.one/products/flipper-zero)
  - Kul för att lära sig om RFID, NFC, IR, sub-GHz radio. Alla säkerhetspersoner verkar ha en (ca 2 500 kr)
- [WiFi Pineapple](https://shop.hak5.org/products/wifi-pineapple)
  - Dedikerad rogue AP-plattform, overkill men cool (ca 1 500 kr från Hak5)
- [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky?variant=353378649)
  - Ser ut som ett USB-minne, skriver payloads. Bra för att demonstrera varför man inte ska plugga in slumpmässiga USB-enheter (ca 500 kr från Hak5)
- [Proxmark3 Easy](https://www.amazon.se/dp/B09LYGMD4B)
  - RFID/NFC-klonare och analysator, mycket mer kapabel än Flipper för kortsaker (ca 600 kr)
- [HackRF One](https://www.amazon.se/dp/B01JMQEKEG)
  - SDR som täcker 1 MHz till 6 GHz, sända och ta emot. För radioutforskning (ca 2 500 kr)
- [RTL-SDR v4](https://www.amazon.se/dp/B0CD7558GT)
  - Billigare mottagnings-SDR, bra för att lära sig (ca 400 kr)
- [LAN Turtle](https://shop.hak5.org/products/lan-turtle)
  - Dolt ethernet-implantat för pentesting. Sitter inline och ger fjärråtkomst (ca 700 kr från Hak5)
- [Throwing Star LAN Tap](https://shop.hak5.org/products/throwing-star-lan-tap)
  - Passiv nätverks-tap för paketfångst (ca 200 kr)

---

## Läsning

- **[Kobo Clara BW](https://www.elgiganten.se/product/mobiler-tablets-smartklockor/lasplatta/kobo-clara-bw-lasplatta-16gb-svart/767065)**
  - Fungerar med Calibre, inget Amazon-låsning. Det här är vad jag faktiskt vill ha. ca 2 000 kr

---

**Lärplattformar:**

- [TryHackMe](https://tryhackme.com/) premium-prenumeration
  - Guidade rum, bra för lärande. Har lärstigar för olika ämnen (ca 800 kr/år)
- [Hack The Box](https://www.hackthebox.com/) VIP
  - Mer CTF-stil, svårare boxar, bra när man kan grunderna (ca 1 000 kr/år)
- [PentesterLab Pro](https://pentesterlab.com/)
  - Praktiska webbsäkerhetsövningar (ca 900 kr/år)
- [OffSec Learn One](https://www.offsec.com/courses/learn-one/)
  - Dyrt men inkluderar OSCP-förberedelse om jag någonsin går den vägen (ca 15 000 kr/år)

---

## Var man köper

Det mesta av detta finns hos:

- [Kjell & Company](https://www.kjell.com/se) – smarta hem, kablar, ESP32-grejer
- [Inet](https://www.inet.se/) – teknik, nätverk, lagring, chassin
- [Webhallen](https://www.webhallen.com/) – gaming, elektronik
- [Komplett](https://www.komplett.se/) – allmän teknik, UPS
- [Amazon.se](https://www.amazon.se/) – när ingen annan har det
- [Electrokit](https://www.electrokit.com/) – elektronikkomponenter
- [Dustin Home](https://www.dustinhome.se/) – YubiKeys, företagsgrejer
- [Adlibris](https://www.adlibris.com/se) – böcker
- [Cykelkraft](https://www.cykelkraft.se/) – cykelgrejer
- [Hak5](https://shop.hak5.org/) – säkerhetshårdvara (skickas från USA)
- [IKEA](https://www.ikea.com/se/sv/) – förvånansvärt bra för billiga Zigbee-grejer
- [Tradera](https://www.tradera.com/) / [Blocket](https://www.blocket.se/) – begagnad hårdvara
