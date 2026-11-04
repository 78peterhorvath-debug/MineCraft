# Karbantartói jegyzet

[← Kezdőlap](../README.md)

## Jelenleg ellenőrzött alap

- Minecraft Java 26.1.2, Fabric Loader 0.20.1, a szervernaplóban Java 25.
- A telepített verziók: [modlista](MODOK.md).
- A konzolban a sikeres indulás jelzése: `Done` és `Server is online`.
- Készült Drive-ra mentés a teljes alap összeállítás után.

## Átadás előtt

- [X] A jelenlegi teljes szerverről új, dátumozott mentés; másolat a Falixon kívül is.
- [ ] Hátizsák készítése, használata és újracsatlakozás utáni tartalma tesztelve.
- [ ] Ultimine használata és a területvédelemmel való együttműködése tesztelve.
- [ ] Flan: második játékos nem tud engedély nélkül rombolni/ládát használni a védett területen.
- [ ] A Flan hat kompatibilitási hibája kivizsgálva vagy a korlát dokumentálva.
- [ ] A játékosok Java-nevei összegyűjtve; whitelist bekapcsolva, amikor mindenki felkerült.
- [ ] `online-mode=true` ellenőrizve; operátori jogok csak a szükséges kezelőknek.
- [ ] Külső Falix-indítás engedélyezve és kipróbálva; indítási cím megosztva a csoportban.
- [ ] Közös játékszabályok elfogadva, Fullbright/radar kérdése eldöntve.
- [ ] Játékoscsomag terjesztése és letöltési helye véglegesítve.

## Beállítási kiindulópont

Javaslat volt **8 chunk látótávolság**, **5 chunk szimulációs távolság**. A végleges beállítást a panelen ellenőrizni kell; a dokumentáció nem igazolja, hogy minden javaslat mentve lett. Öt egyidejű játékossal próbáljuk ki, és mérhető gond esetén változtassunk.

## Frissítés menete

1. Szólj a játékosoknak, majd állítsd le szabályosan a szervert.
2. Készíts mentést a világról, a beállításokról és a modokról. A Flan adatai és a Ledger adatbázisa is legyen benne.
3. Kevés változást végezz egyszerre. Indítsd el, nézd meg a naplót, és próbálj csatlakozni.
4. A klienscsomagot is frissítsd, ha szükséges. A modlistát és a változásokat írd át ebben a repositoryban.

Az automatikus világmentés a jelenlegi állapotot tárolja, a külön biztonsági mentés korábbi állapothoz enged visszatérni. A GitHub nem helyettesíti a világmentést.

## Modfájlok megosztása

Elsőként a pontos verziókat és a hivatalos letöltési linkeket osszuk meg. Kész `.jar` csomag közzététele előtt ellenőrizni kell az egyes készítők újraterjesztési feltételeit. Alternatíva egy olyan importálható modcsomag, amely a fájlokat a hivatalos helyükről tölti le.

Ne töltsünk fel teljes szervermentést, személyes játékosadatokat, hitelesítési adatot vagy panelhozzáférést a nyilvános repositoryba.
