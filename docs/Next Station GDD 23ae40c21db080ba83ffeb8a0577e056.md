# Next Station GDD

# Ⓜ️Alapinformációk

- 🚄Játék címe: Next Station
- 💾Verzió: 1.0.0.
- 🙋‍♂️Fejlesztő neve: Magó Barnabás
- 📅Dátum: 2025 július-2025 augusztus
- 🖥️Platform: PC

# 🎲Játék koncepciója

- ✍️Rövid leírás: A játékos célja, hogy az adott várost a lehető leghatékonyabban kösse össze egy metróhálózattal. A játék alapkoncepcióját s Gémklub “következő megálló: Párizs” című játéka adja.
- Műfaj: Logikai
- 🎥Nézet: 2D

# 🕹️Játékmenet

- 🎯Cél: A játékos a lehető legtöbb pontot szerezze a 4 kör (4 különböző metróvonal) letelte után. Pontszámítás később.
- 👾Játékmenet loop: A játékos 4 különböző színnel (sárga, piros, kék, zöld) épít metróhálózatot. Egy színen belül 11 kör van, ahol a játékos egy adott szimbólumot kap, és az adott feltételek mellett ilyen szimbólumú mezőre terjeszkedhet.

# 🖱️Mechanikák

- 🏗️Építési szabályok:
    - ✅összekötni 2 állomást egy egyenes vonallal, ami  vízszintesen, függőlegesen vagy átlósan halad, követve a szürkével jelölt lehetséges vonalakat a térképen.
    - ✅ az első szakasz amit rajzol mindig egy kezdőállapotból indul ki és egy helyes szimbólumban végződik.
    - ✅ minden szakasznak a metróvonal egy végéből kell kiindulnia.
    - ⛔️olyan szakaszt rajzolni ami nem követ egy szürkével jelölt vonalat
    - ⛔️megváltoztatni a vonal irányát
    - ⛔️átmenni egy olyan állomáson hogy a szakasz a következőnél érjen véget
    - ⛔️metróvonalakat keresztezniük egymást, színtől függetlenül
    - ⛔️2 állomás között több szakaszt berajzolni. színtől függetlenül
    - ⛔️hurkot képezni

# 🗺️Pályák

- 🧭Pályák száma: 1 (Budapest), később több város, egyre nehezebbek.

# 🎨Felhasználói felület

- 🚦Főmenü: Játék kezdése, kilépés, szabályok
- 🚏HUD: Aktuális szín, szimbólum, következő kör gomb, állomások mint gomb, vonal építés gomb, pontszám
- 🗺️Térkép: Egyszerűsített városi közlekedési térkép, közlekedési csomópontok (szimbólummal), szürke összeköttetések

# 📐Technológia

- 💻Fejlesztői környezet: Java, Java Swing (grafika)
- 💿Kódkezelés: GitHub
- 🌄Grafika készítéséhez:
- 🎹Zene: még kitalálni
- ⌨️IDE: IntelliJ

# 📆Ütemezés

1. GDD
2. Skeleton (logika)
3. Teszt
4. Grafika
5. Hang
6. Hibajavítás
7. Kiadás