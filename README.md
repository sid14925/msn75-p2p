# MSN 7.5 stílusú P2P Messenger (nem hivatalos rajongói projekt)

Szerver és regisztráció nélküli, MSN Messenger 7.5 stílusú P2P csevegő:
belépés névvel és Peer ID-vel, üzenetek betűtípus- és színválasztással,
azonnali képküldés (vágólapról és behúzással is), fájlküldés, hang- és
webkamerás hívás, képernyő-stream, csoportos beszélgetés. Minden adat
közvetlenül, WebRTC-n megy a két gép között.

## Böngészőben

| Oldal | Leírás |
|---|---|
| **https://sid14925.github.io/msn75-p2p/** | **Alapváltozat** — a klasszikus kinézettel, az eredeti MSN 7.5 hangulatjelekkel, hangokkal és grafikákkal. |
| **https://sid14925.github.io/msn75-p2p/lite.html** | **Alternatív (lite) változat** — copyright-tisztított: saját rajzolt ikonok, Unicode-emojik, szintetizált hangok. |

A két változat használói egymással is tudnak csevegni.

## Android

| Letöltés | Leírás |
|---|---|
| **[MSN75-P2P.apk](MSN75-P2P.apk)** | Alapváltozat (klasszikus kinézet) |
| [MSN75-P2P-Lite.apk](MSN75-P2P-Lite.apk) | Alternatív, copyright-tisztított változat |

Android 7.0 vagy újabb szükséges. Telepítés előtt engedélyezni kell az
ismeretlen forrásból való telepítést. A két APK külön csomagnevű, így
egymás mellé is telepíthető.

Az alkalmazás úgy működik, mint egy megszokott mobil üzenetküldő: indításkor
a partnerlista látszik, beszélgetéskor a csevegőablak, és a rendszer vissza
gombja lép vissza a listához.

## Beállítások

A jobb alsó fogaskerék ikonnal állítható a **méretezés** (100–250%, mint a
Windows kijelző-nagyítása), az asztal háttérszíne és az ablakok színe.
Nyelv: magyar / angol az Eszközök menüben.

## Jogi megjegyzések

- Ez egy **nem hivatalos rajongói projekt**, amely semmilyen kapcsolatban
  nem áll a Microsoft Corporationnel. Az „MSN" és „MSN Messenger" a
  Microsoft védjegyei.
- Az alapváltozat (`index.html`, `MSN75-P2P.apk`) a Microsoft MSN Messenger
  7.5 programjából származó erőforrásokat (hangulatjelek, hangok, logók,
  képek) tartalmaz, amelyek a Microsoft Corporation szerzői jogvédelem
  alatt álló tulajdonai. Ezeket a repó tulajdonosa nosztalgia-célból, saját
  döntésére és felelősségére teszi elérhetővé; a Microsoft kérésére
  eltávolításra kerülnek.
- A lite változat (`lite.html`, `MSN75-P2P-Lite.apk`) nem tartalmaz
  Microsoft-tulajdonú anyagot.
- A saját fejlesztésű kód MIT licencű.
- A beágyazott [PeerJS](https://github.com/peers/peerjs) könyvtár MIT
  licencű — © 2015 Michelle Bu and Eric Zhang, http://peerjs.com. Teljes
  licencszöveg: https://github.com/peers/peerjs/blob/master/LICENSE
