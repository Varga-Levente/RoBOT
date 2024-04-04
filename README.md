# ESP32 alapú WiFi-vezérelt Robot kamerával

## Projekt Áttekintése

A projekt keretében egy WiFi-vezérelt robotot fejlesztettem, melynek alapja az ESP32 mikrovezérlő, és a kiegészítők között szerepel egy kamera, valamint 4 darab motor cserélhető akkumulátorokkal. A robot és az ehhez kapcsolódó mobilalkalmazás készítése a Debreceni Egyetem Informatikai Karának Mérnökinformatikus BSc képzésének Mobil Megoldások tantárgyában történt.

A robot és az alkalmazás fejlesztése egy hobbi projekt keretében valósult meg, melynek célja a mobil technológiák és a beágyazott rendszerek összekapcsolása, valamint a gyakorlati tapasztalatszerzés a hardver- és szoftverfejlesztés területén.

## Részletek

- **Hardver:**
  - Mikrovezérlő: ESP32-CAM
  - L298N motorvezérlő
  - 4 darab motor
  - 2 Cserélhető akkumulátor (18650)
  - Az alkatrészeket FDM 3D nyomtatással készítettem PLA filament felhasználásával

- **Szoftver:**
  - ESP32 vezérlő kódja az `ESP32-CAM Code` könyvtárban található Arduino `.ino` fájlban.
  - Mobilalkalmazás készült a robot vezérlésére és a kamera által rögzített képek megjelenítésére.

- **Jövőbeli tervek:**
  - Bluetooth vezérlési opció hozzáadása a robothoz és az applikációhoz
  - LoRa (Long Range Radio) vezérlés készítése ahol egy 2. ESP modul bridge szerepet tölt be és a WiFi vagy Bluetooth-on kapott otasításokat továbbítja LoRa segítségével
  - Hangszóró beépítése duda céllal
  - Ultrahangos távolság érzékelő beépítése az ütkötések elkerülésére (Legyen kikapcsolható APP-ból)

## További Információ

A projekt részletes leírása és dokumentációja megtalálható a mellékelt PDF fájlban.

A mobilalkalmazás külön repositoryban található, azonban jelenleg még nem publikus. (Későbbiekben linkelve lesz ide)

## Fejlesztő:
  - Varga Levente

---

*Végrehajtott projekt a Debreceni Egyetem Informatikai Karának Mérnökinformatikus BSc képzése Mobil Megoldások tantárgyában.*
