# Gyakori hibák

[← Kezdőlap](../README.md)

| Hiba | Első teendő |
|---|---|
| „This server requires Fabric API installed on your client” | Ellenőrizd, hogy a Fabric-profil indul, és annak saját `mods` mappájában van a Fabric API és a közös csomag. |
| Inventory Profiles Next inkompatibilitás | A kipróbált páros: **IPN 2.3.8 + libIPN 6.9.0**, Fabric 26.1.2. A Kotlin is kell. Ne maradjon régi libIPN ugyanott. |
| Eltűnt a szerverlista | A külön játékmappának saját listája van. Add hozzá újra a szervert. |
| Modokkal összeomlik a játék | Zárd be, ellenőrizd a Fabricot, a 26.1.2-t, a függőségeket és a duplikált fájlokat. A pontos hibát őrizd meg. |
| Nem működik egy gyorsgomb | Ellenőrizd a billentyűkiosztást és az ütközéseket. |
| Whitelist miatt nem enged be | A karbantartónak a **Java Edition játékosnevet** add meg, ne az Xbox-becenevet. |

## Hitelesítő szerverek nem elérhetők

A teszt során a Falix naplója ezt írta: `Couldn't verify username because servers are unavailable`. Néhány újrapróbálkozás után sikerült csatlakozni. Ez a fiókellenőrzés elakadása; a konkrét hálózati ok még nincs megállapítva.

## Hibajelentéshez

Írd le, melyik lépésnél történt, és küldd el a pontos hibaüzenetet, valamint a mod/profil verzióját. Nyilvános bejegyzésből hagyd ki az IP-címeket, fiókadatokat és mások személyes adatait.
