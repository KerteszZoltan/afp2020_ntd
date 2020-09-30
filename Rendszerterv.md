# Rendszerterv

## A rendszer célja
 A rendszer célja, hogy a Követelmény és Funkcionális specifikációban meghatározott megrendelői folyamatok megvalósuljanak.
 Egy olyan online bemutatkozó oldalt szeretnénk létrehozni, ami használhatóságban, megjelenésben és funkcióit tekintve,a megrendelőkívánságainak eleget tesz. 
 A weboldalt bárki elfogja tudni érni és a megrendelő álltal megosztott információkat láthatja. Fontosnak tartjuk, hogy a megrendelő oldala mindig napra kész legyen.
 Az oldalunk célja, népszerűsíteni a megrendelőt és egyben a szoftver gyártó cégünket.

## Projektterv

	    Dátum		    Tevékenység						            Résztvevő(k)
	
    2020.09.17.-09.29.	    Dokumentációk elkészítése és véglegesítése
    2020.09.28.		    Fejlesztés megkezdése
    2020.10.01.		    Projekt átadása						        A projektben résztvevő összes szereplő

## Üzleti folyamatok modellje

	Üzleti szereplõk:
		-Tulajdonos
		-Project készítői

	Támogatandó üzleti folyamatok:
		-Információk frissítése
		-Videók feltöltése

	Üzleti folyamatok leírása:

	Lejátszás:
		Az oldalon letudjuk játszani a meglévő videókat. Ehhez saját online lejátszót kell használni.

	Videók feltöltése:
		A tulajdonosnak és az admin(ok)-nak lehetőségük lesz videók és azok leírásának feltöltésére.

	Modell:
		Kezdőoldal -> Önéletrajz -> Önéletrajz letöltés
				-> E-mail küldés
				-> Videók

## Követelmények

- Funkcionális követelmények 
  - Kezdőoldal (index.html)
  - Videók oldal (video.html)
  - Önéletrajz oldal (cv.html)
  - Minden oldalról minden oldal elérése
- Nem funkcionális követelmények
 - Oldalanként különböző betűtípus
  - Oldalanként megegyező háttér

## Funkcionális terv
### Rendszerszereplők:
-   Megtekintők

### Rendszerhasználati esetek és lefutásaik:
- Megtekintő:
  - Kezdőoldal megtekintése -> Videók/Önéletrajz megtekintés
  - Önéletrajz oldal megtekintés -> Videók/Kezdőoldal megtekintés
  - Videók oldal megtekintés -> Kezdőoldal/Önéletrajz megtekintése.

### Menü-hiererchia:
-Kezdő oldal
-Önéletrajt oldal
-Videók oldal
## Absztrakt modell
---------
## Implementációs terv
A Webes felület főként HTML, és CSS nyelven fog készülni. Ezeket a technológiákat amennyire csak lehet külön fájlokba írva készítjük, és úgy fogjuk egymáshoz csatolni a jobb átláthatóság, könnyebb változtathatóság, és könnyebb bővítés érdekében.

## Karbantartási terv