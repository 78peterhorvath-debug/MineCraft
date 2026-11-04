# Telepítés Windowsra

[← Kezdőlap](../README.md)

## 1. Minecraft 26.1.2

1. Nyisd meg a hivatalos Minecraft Launchert, és válaszd a **Java Editiont**.
2. **Telepítések → Új telepítés → release 26.1.2**.
3. Indítsd el egyszer, várd meg a főmenüt, majd zárd be a játékot és a Launchert.

## 2. Fabric

1. Töltsd le a **Download for Windows** telepítőt a [Fabric hivatalos oldaláról](https://fabricmc.net/use/installer/).
2. A telepítőben: **Client**, Minecraft **26.1.2**, Loader **0.20.1**, **Create profile** bepipálva.
3. A telepítési hely a Launcher Minecraft-mappája legyen, általában `%APPDATA%\.minecraft`. Egyéni telepítésnél ellenőrizd a saját útvonaladat.
4. Kattints az **Install** gombra, majd nyisd meg a Launchert.

## 3. Külön mappa a Fabricnak

Így a régi Forge-modok nem keverednek az újakkal.

1. **Telepítések → fabric-loader-0.20.1-26.1.2 → Szerkesztés**.
2. A Játékkönyvtárhoz válassz egy külön mappát, például `C:\Users\SAJAT_WINDOWS_NEV\AppData\Roaming\.minecraft-fabric-26.1.2`. A Windows-nevet cseréld a sajátodra.
3. Mentsd, indítsd el ezt a profilt egyszer, majd lépj ki.
4. A kiválasztott mappában keresd meg a `mods` almappát; ha nincs, hozd létre.

## 4. Modok

1. Bezárt játék mellett másold a [modlista](MODOK.md) kliensre jelölt fájljait a fenti `mods` mappába.
2. A `.jar` fájlokat **nem kell megnyitni vagy kicsomagolni**. Közvetlenül a `mods` mappába kerüljenek, ne egy újabb almappába.
3. Egy modból egy verzió maradjon. Régi Forge-fájlokat ne másolj ide.
4. A Fabric API is külön mod: a Fabric telepítő nem helyettesíti.

## 5. Belépés

Indítsd a **fabric-loader-0.20.1-26.1.2** profilt. **Többjátékos → Szerver hozzáadása**, majd add meg a szervezőtől kapott címet.

A külön játékmappának külön szerverlistája van. Ha itt üres a lista, vedd fel újra a címet: vasvari7b.falix.gg

Whitelisthez a **Java Edition játékosnevedet** add meg, ne az Xbox-becenevedet. Jelszót senkinek sem kell küldened.
