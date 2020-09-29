# Funkcionális Specifikáció

## Áttekintés
A technológiai fejlődéssel egy új szegmens nyílt meg az emberek számára, mint adat megosztás és tárolás. A Weboldal preztízs kérdés lett. A cégekről több információt lehetett megtudni, amennyiben volt weblapjuk, könnyebben lehet velük így a kapcsolatot felvenni. Privát személyek esetében sincs ez másképpen. Az emberek könnyebben tudnak így információt megosztani magukról, közelebb tudják így hozni magukhoz az embereket és már találkozó előtt is szimpátiát tudnak nyerni. 
Úgy gondoljuk, hogy sokkal környezet kímélőbb az önéletrajzot egy weboldalon megjeleníteni és frissen tartani, mint papírra nyomtatni. 


## Jelenlegi helyzet

Jelenleg, ha az ember állásinterjúra megy papír alapon nyújt be önéletrazot és kísérő levelet. Szerintünk ebből a két dokumentumból nem derül ki, hogy az adott ember milyen is. Kell egy független bemutatkozás, érdeklődési kör ismertetés, hogy komplexebb kép alakuljon ki a pályázóról. 
Úgy gondoljuk, hogy egy ilyen személyes weblap elősegíti a pályázót a sikeres felvételhez, amennyiben pedig egy másik cég HR-ese talál rá a weboldalra nem csak le tudja tölteni az önéletrajzot, de a kapcsolatot is fel tudja venni az adott személlyel. 

## Vágyálomrendszer

Egy egyszerű weblapot csinálunk ahol a kezdőlap egy bemutatkozó oldal. Itt a felhasználóról egy rövid bemutatkozó szöveg található egy menü szerkezettel ahol kitudja választani, hogy melyik oldalra kíván tovább menni. Választhatja az önéletrajzot és a Videókat. A vieók menüpont alatt a felhasználó kedvenc videói találhatóak egy rövid leírással. Az Önéletrajz menüpontot választva egy olyan oldal fog megnyílni ahol a felhasználó önéletrajza található táblázatos formában, alatta pedig két gomb fog lehetőséget nyújtani a gyors e-mail küldésére és az önéletrajz letöltésére. 

## Jelenlegi üzleti folyamatok

Jelenleg az önéletrajzot az emberek papír alapon nyújtják be, ami nem túl környezet barát és sajnos nem ismerik meg a jelentkezőt csak beskatulyázzák első "ránézés" alapján. A Weboldalunk ezbben segítene a felhasználóknak, hiszen nem lenne szükség a papír alapú önéletrajzra és látatlanban is sokkal jobban kikörvonalazódik a munkavállaló számára, hogy az adott ember aki jelentkezett a munkára, milyen személyiség.

## Igényelt üzleti folyamatok
Igény szerint, ha az emberek normális weboldalt szeretnének készítettni akkor egy olyan céget kell keresniük, akik rendelkeznek referenciával és értenek a design-oláshoz. Az előre elkészített weboldalak sokszor nem személyre szabhatóak és el van bennük reklám helyezve, hogy az ingyenességet vagy éppen a minimális árakat fent tudják tartani. Egy saját oldal esetében a fenntartás érdekéből lehet reklámozni, de így a tulajdonos dönti el, hogy milyen reklámokat helyez el az oldalán.

## Követeleménylista 
### Funkcionális követelmények:
  k1: Vezérlés: 
	Videók, Bemutató, Önéletrajz
	Egységes háttérkép
  k2: Kezdőoldal:
 	Kép beillesztés
 	Rövid Bemutató
  k3: Videók:
	Beágyazott videók a Youtube-ról
	Videó leírás.
	Különböző betűtípus a Bemutató és az Önéletrajz oldaltól.
  k4: Önéletrajz:
	EuroPass kialakítású önéletrajz megjelenítés
	Gomb: Különböző háttérszín
	Gomb1: Email küldése
	Gomb2: Önéletrajz letöltése
	Különböző betűtípus a kezdőlaptól

## Képernyőtervek

## Használati esetek
Hozzáférések jogultság szerint:
	-Egyszerű felhasználó

Egyszerű felhasználó: 
	-Szabadon megtekintheti az oldalakat.
	-Az önéletrajzi oldalon található email küldése funkció használata
	-Önéletrajz letöltése pdf formátumban.
	-Videók lejátszása, megállítása, hangerő szabályozása

## Forgatókönyvek
Az alkalmazás a webböngészőkben fut, nem kell hozzá semmiféle szerver oldali erőforrás. 
A kezdőoldal az egy rövid ismertető oldal a önéletrajz tulajdonosáról. A kezdő oldalon felül található egy navigációs menü, amely segítségével tekinthetjük meg minden további oldalt. Ez a menü mindegyik oldalon egyaránt megtalálható és az aktuális oldal kimelve látható.
A navigációs menüben a kiválasztott oldalra kattontva nyílik meg az új oldal. A videók menüpontra kattintva nyílik meg az oldal, az oldalon a feltöltött videók láthatóak, ezek lejátszására, megállítására, hangerőszabályozására van lehetőség. 
Amennyiben az önéletrajzot szeretné megtekinteni akkor táblázatos (euro pass-os) formátumban tekinthető meg a rövid ismertető. Az ismertető alatt két gomb található, az egyik gomb az önéletrajz PDF formátumban való letöltését biztosítja, míg a másik az alapértelmezett levelző programot nyitja meg, ahol az önéletrajz tulajdonosának vanj lehetőség emailt küldeni. 
Valamint minden oldal alján található egy gomb ami a kezdő oldalra, azaz a bemutatkozó oldalra írányít vissza.

## Funkciók


## Fogalomszótár
HTML: Alapértelmezett leíró nyelv, weboldalak készítésére szokás használni.

CSS: HTML oldalak stílusnak leírására használatos nyelv.