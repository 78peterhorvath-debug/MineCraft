# Telepítés Windowsra

[← Kezdőlap](../README.md)

## 1. Fabric

1. Töltsd le a **Download for Windows** telepítőt a [Fabric hivatalos oldaláról](https://fabricmc.net/use/installer/).
2. A telepítőben: **Client**, Minecraft **26.1.2**, Loader **0.20.1**, **Create profile** bepipálva.
3. A telepítési hely a Launcher Minecraft-mappája legyen.  Egyéni telepítésnél ellenőrizd a saját útvonaladat. Általában valami ilyesmi: `C:\Users\WINDOWS\AppData\Roaming\.minecraft`
4. Kattints az **Install** gombra.

## 2. Külön mappa a Fabricnak

Így a régi modok nem keverednek az újakkal.

1. Nyisd meg a Launchert, DE MÉG NE INDÍTS EL SEMMIT!!!!
2. **Telepítések → fabric-loader-0.20.1-26.1.2 → Itt menj a jobb oldali 3 pötyre! Szerkesztés/edit**. 
3. Megjelenik az az elérési út, ahol neked a jelenlegi minecraft példány van telepítve, lehet hogy ömlesztve a sokféle verzió, ezért célszerű ennek a verziónak külön könyvtárat létrehozni. Ami jelenleg neked `\AppData\Roaming\.minecraft`-ra végződik, azt ekészítsd ki mondjuk erre: `C:\Users\WINDOWS\AppData\Roaming\.minecraft-fabric-26.1.2`. és SAVE! Elmenit ezt az elérési utat.
4. Most a luncherben indítsd el `fabric-loader-0.20.1-26.1.2` verziót. A játék elindul és abba a mappába, amit kézzel megadtál letölti, ami neki kell.
5. Miután a játék elindult a bal alsó sarokban ezt kell látnod: 26.1.2 (Modolt) - Ha ezt látod sirályság van!
6. Lépj ki és keresd meg a fenti elérési úton a `fabric-loader-0.20.1-26.1.2\mods` mappát.
7. Ha nincs `mods` mappát, hozd létre.

## 3. Modok

„A telepítéshez a közös csomagot használd! A korábbi modjaidat hagyd a régi játékmappában!”
Vagy letöltöd a `https:\\modrinth.com` oldalról a megfelelő modot, vagy az általam githubra feltöltött példányokat használod. Ezek működnek! Egyenlőre ne használj mást, juss be a szerverre és akkor bővíthetitek a mod-okat, csak egyeztessetek, mert néhánynak a szerver oldali párját is telepíteni kell. Ha az elején mindent is behajítasz a mods könyvtárva, nem fogod tudni mitől akad a játék.

Amennyiben még is a letöltés mellett döntesz, a `https:\\modrinth.com` -on írd a keresőbe amire szükséged van! (Ne azt hogy Ferrari pls!) Pl: liblPN. Kartt rá és válaszd a version fület. Channel: Release, Game version: 26.1.2, Platform. fabric. Ha nem ezeket állítod be, rossz verzót kapsz. A listából minndig a legfrissebbet töltsd le. Soha se beta, vagy alfa verziót. azok nem stabilak. Letöltés után másold a mods mappába. lehetőleg ne 10-essével. max 2-3. Utána luncherben indítsd el a fabric-loader-0.20.1-26.1.2 -t. Így ha valami akad, könnyen kitalálod, melyik mods lehet a ludas. 
Ha végképp nem boldogulsz küldj hibajelentés-ről képet Máténak. 

## 4. Belépés

Indítsd a **fabric-loader-0.20.1-26.1.2** profilt. **Többjátékos → Szerver hozzáadása**

A külön játékmappának külön szerverlistája van. Ha itt üres a lista, vedd fel újra a címet: vasvari7b.falix.gg

Whitelisthez a **Java Edition játékosnevedet** add meg, ne az Xbox-becenevedet. Jelszót senkinek sem kell küldened.

A Whitelist azért kell, hogy ne tudjon minden jöttment csatlakozni a szerverhez, mert most mindenkit beenged, hogy azok széttrollkodjanak mindnet.
