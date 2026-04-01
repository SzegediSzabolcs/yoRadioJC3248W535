# yoRadio – Magyar verzió JC3248W535 (AXS15231B) kijelzővel

ESP32-S3 alapú internet rádió **magyar nyelvű felülettel**, csak a **fő névnapok** kijelzésével és teljes támogatással a Guition JC3248W535 modulhoz (AXS15231B vezérlő + kapacitív érintőképernyő).

## 📻 A projektről

Ez a projekt egy erősen módosított **yoRadio** (eredeti: e2002/yoradio) fork.  
Célja egy egyszerűen használható, szép kinézetű, magyar nyelvű internet rádió készítése a népszerű Guition JC3248W535 ESP32-S3 kijelzős modulra.

### Főbb módosítások és javítások:
- Saját egyedi bootlogo
- Alap: **V-Tom** verzió
- **romekb** által hozzáadott teljes támogatás a **JC3248W535** modulhoz (AXS15231B vezérlő + kapacitív érintőképernyő)
- Teljes magyar nyelvű felület (korábbi magyar verzióban lévő hibákat kijavítottam)
- **Csak a fő magyar névnapok** jelennek meg (a másodlagosak nincsenek benne a tisztább megjelenés érdekében)
- Kisebb hibajavítások és optimalizálások a stabil működéshez

## ✨ Funkciók
- Internet rádió (több száz magyar és külföldi állomás)
- Időjárás-jelentés és óra
- **Magyar névnapok** (csak a fő névnapok)
- Kapacitív érintőképernyő támogatás (AXS15231B)
- Webes konfiguráció (WiFi, állomások stb.)
- Alacsony fogyasztású képernyővédő üzemmód
- Egyszerű, letisztult magyar felület

## ⚙️ Konfiguráció

A projekt legfontosabb beállításai a **`myoptions.h`** fájlban találhatók (a fájlok között megtalálod).  
Itt minden lényeges dolgot ki- és bekapcsolhatsz, például:
- Névnapok megjelenítése
- Használt DAC típusa
- Egyéb funkciók (pl. RTC, rotary encoder támogatás stb.)

Mielőtt feltöltenéd a kódot a Guition JC3248W535-re, mindenképpen nézd át és állítsd be igényeid szerint ezt a fájlt!

## 🛠️ Használt alkatrészek
Az összes szükséges alkatrész linkje megtalálható a repo **Aliexpress** mappájában.

Főbb komponensek:
- Guition JC3248W535 kijelző modul (AXS15231B vezérlővel)
- PCM5102 DAC modul
- Rotary encoder (opcionális)
- DS3231 RTC modul

## 📥 Telepítés
1. Töltsd le a legfrissebb release-t
2. Használd az Arduino IDE-t
3. A részletes flashing útmutatót lásd az eredeti yoRadio wiki-n

## ❤️ Köszönet
- **e2002** – az eredeti yoRadio projektért [](https://github.com/e2002/yoradio)
- **V-Tom** – az alap verzióért
- **romekb** – a JC3248W535 + AXS15231B támogatás hozzáadásáért
- Mindenkinek, aki a magyar fordításhoz hozzájárult

---

Ha tetszik a projekt, adj egy ⭐-t a repónak!  
Kérdésed vagy javaslatod van? Nyugodtan nyiss Issue-t.

**Kellemes rádiózást! 🎵**
