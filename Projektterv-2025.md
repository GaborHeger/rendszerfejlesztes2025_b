# `Vasút` Projektterv `2025`

## 1. Összefoglaló 

A projekt célja egy korszerű, felhasználóbarát webalkalmazás fejlesztése, amely egy vasúti applikáció funkcióit
valósítja meg: menetrend keresés, jegyfoglalás, járatinformációk és felhasználói fiókkezelés. A rendszer asztali
és mobil böngészőből is elérhető lesz, reszponzív kialakítással. 
Az oldal célja átláthatobbá és gyorsabbá tenni a vasúti közlekedéssel való tájékozodást. 


## 2. A projekt bemutatása

`Ez a projektterv a Vasút projektet mutatja be, amely 2025-09-08-tól 2025-12-08-ig tart, azaz összesen 92 napon keresztül fog futni. A projekten három fejlesztő fog dolgozni, az elvégzett feladatokat pedig négy alkalommal fogjuk prezentálni a megrendelőnek, annak érdekében, hogy biztosítsuk a projekt folyamatos előrehaladását.`


### 2.1. Rendszerspecifikáció

`A webalkalmazásnak raktároznia kell az adott menetrendeket. A felhasználók tudnak keresni a mentrendek között, melyik vonatok állnak
meg az általuk megadott állomáson, a megadott idősávban. Van felhasználói fiók. A felhasználók tudnak jegyet/bérletet venni.`


### 2.2. Funkcionális követelmények

 - `Menetrend keresés`
 - `Útvonaltervezés`
 - `Jegyfoglalás (CRUD)`
 - `Járatinfórmációk megjelenítése`
 - `Felhasználói fiókkezelés (CRUD)`



### 2.3. Nem funkcionális követelmények

 - `Reszponzív megjelenés`
 - `Adatok biztonságos tárolása`
 - `A legfrissebb technológiákat használja a rendszer`


## 3. Költség- és erőforrás-szükségletek

Az erőforrásigényünk összesen `75` személynap, átlagosan `25` személynap/fő.

A rendelkezésünkre áll összesen `3 * 70 = 210` pont.


## 4. Szervezeti felépítés és felelősségmegosztás

A projekt megrendelője `Héger Gábor`. A `Vasút` projektet a projektcsapat fogja végrehajtani, amely `jelenleg három fejlesztőből áll. A csapat pályakezdő programozókból áll.`
 - `Fehér Dajana`
 - `Géczi Zsófia`
 - `Veszprémi Csongor`



### 4.1 Projektcsapat

A projekt a következő emberekből áll:

| Név          | Pozíció          |   E-mail cím (stud-os)        |
|--------------|------------------|-------------------------------|
| `Fehér Dajana` | Projektmenedzser | `feherrrd@gmail.com`    |
| `Géczi Zsófia` | Projekt tag      | `h158224@stud.u-szeged.hu`    |
| `Veszprémi Csongor`   | Projekt tag      | `veszcso2016@gmail.com`    |



## 5. A munka feltételei

### 5.1. Munkakörnyezet

A projekt a következő munkaállomásokat fogja használni a munka során:

 - `Munkaállomások: 3 db,  2 db Windows 11-es operációs rendszerrel, 1db MacOS 26.0 operációs rendszerrel`
 - `Acer laptop (CPU: i5 5200U, RAM: 8 GB, GPU: Nvidia 920M)`
 - `Acer Nitro 5 laptop (CPU: i3 5005U, RAM: 4 GB, GPU: Nvidia 920M)`
 - `AMacbook Air M3 (CPU: Apple M3, RAM: 8†GB, GPU: 10-core)`

A projekt a következő technológiákat/szoftvereket fogja használni a munka során: 

 - `Heroku platformszolgáltatás a webalkalmazás hosztolásához`
 - `Heroku által biztosított PostgreSQL adatbázisszerver`
 - `Spring Boot keretrendszer`
 - `Thymeleaf dinamikus tartalom megjelenítés a felhasználói felületen`
 - `Maven szoftverprojekt menedzselő szoftver`
 - `Eclipse IDE fejlesztőkörnyezet`
 - `Git verziókövető (GitLab)`
 
```
Milyen gépet használnak a projekttagok, milyen operációs rendszeren fejlesztenek, milyen szoftverkörnyezetben, stb.
```

### 5.2. Rizikómenedzsment

| Kockázat                                    | Leírás                                                                                                                                                                                     | Valószínűség | Hatás  |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|--------|
| `Betegség`                                  | `Súlyosságtól függően hátráltatja vagy bizonyos esetekben teljes mértékben korlátozza a munkavégzőt, így az egész projektre kihatással van. Megoldás: a feladatok átcsoportosítása`        | `nagy`       | `erős` |
| `Kommunikációs fennakadás a csapattagokkal` | `A csapattagok között nem elégséges az információ áramlás, nem pontosan, esetleg késve vagy nem egyértelműen tájékoztatjuk egymást. Megoldás: még gyakoribb megbeszélések és ellenőrzések` | `kis`        | `erős` |



## 6. Jelentések

### 6.1. Munka menedzsment
A munkát `Fehér Dajana` koordinálja. `Fő feladata, hogy folyamatosan egyeztessen a csapattagokkal az előrehaladásról és a fellépő problémákról, esetlegesen a megoldásban is segítséget nyújhat a projekt csúszásának elkerülése végett. További feladata a heti szinten tartandó csoportgyűlések időpontjának és helyszínének leszervezése, erről email-ben tájékoztatja a projektcsapatot.`



### 6.2. Csoportgyűlések

`A csapat heti szinten egyszer ül össze megbeszélni az elmúlt hét történéseit, és a következő hét feladatait.
Szükség esetén hét közben is összehívható egy második csoportgyűlés.`

`1. megbeszélés:`
 - `Időpont: 2025.10.05.`
 - `Hely: SZTE Irinyi épület - Szeged, Tisza Lajos krt. 103`
 - `Résztvevők: TFehér Dajana, Géczi Zsófia, Veszprémi Csongor`
 - `Érintett témák: Ismerkedés, projekttéma kiválasztása`

`2. megbeszélés:`
 - `Időpont: 2025.10.12.`
 - `Hely: Discord`
 - `Résztvevők: Fehér Dajana, Géczi Zsófia, Veszprémi Csongor`
 - `Érintett témák: A projektben használt technológiák rögzítése, a projektterv áttekintése, szerepkörök és vállalások kiosztása`



### 6.3. Minőségbiztosítás

A projekt minden részét minden csapattag átnézi bemutatás előtt, hogy az elvárt módon működjön a webalkalmazás, szükség esetén belejavítunk
egymás munkájába. Az elkészült terveket a terveken nem dolgozó csapattársak közül átnézik, hogy megfelel-e a specifikációnak és az egyes diagramtípusok összhangban vannak-e egymással. 

Az alábbi lehetőségek vannak a szoftver megfelelő minőségének biztosítására:
- Specifikáció és tervek átnézése (kötelező)
- Teszttervek végrehajtása (kötelező)
- Unit tesztek írása (választható)
- Kód átnézése (code review) egy, a modul fejlesztésében nem résztvevő csapattag által (választható)

### 6.4. Átadás, eredmények elfogadása

A projekt eredményeit a megrendelő, `Héger Gábor` fogja elfogadni. A projektterven változásokat csak a megrendelő írásos engedélyével lehet tenni. A projekt eredményesnek bizonyul, ha specifikáció helyes és határidőn belül készül el. Az esetleges késések pontlevonást eredményeznek. 
Az elfogadás feltételeire és beadás formájára vonatkozó részletes leírás a következő honlapon olvasható: https://okt.inf.szte.hu/rf1/

### 6.5. Státuszjelentés

Minden mérföldkő leadásnál a projekten dolgozók jelentést tesznek a mérföldkőben végzett munkájukról a a megadott sablon alapján. A gyakorlatvezetővel folytatott csapatmegbeszéléseken a csapat áttekintik és felmérik az eredményeket és teendőket. Továbbá gazdálkodnak az erőforrásokkal és szükség esetén a megrendelővel egyeztetnek a projektterv módosításáról.

## 7. A munka tartalma

### 7.1. Tervezett szoftverfolyamat modell és architektúra

`A szoftver fejlesztése során az agilis fejlesztési modellt alkalmazzuk, mivel a fejlesztés során nagy hangsúlyt fektetünk a folyamatos kommunikcióra. A fejlesztés során a szoftver specifikációi rugalmasan vátozhatnak, és ezzel a módszertannal tudunk a leggyorsabban alkalmazkodni az új elvárásokhoz.`

`A webalkalmazás az MVC (modell-view-controller) felépítést követi, a szerver és a kliens függetlenek, csupán API végpontok segítségével kommunikálnak.`



### 7.2. Átadandók és határidők

A főbb átadandók és határidők a projekt időtartama alatt a következők:


| Szállítandó |                 Neve                                                        |   Határideje  |
|:-----------:|:---------------------------------------------------------------------------:|:-------------:|
|      D1     |      Projektterv és Gantt chart, prezentáció, egyéni jelentés               | `2025-10-13`  |
|    P1+D2    |      UML, adatbázis- és képernyőtervek, prezentáció, egyéni jelentés        | `2025-10-27`  |
|    P1+D3    |      Prototípus I. és tesztelési dokumentáció, egyéni jelentés              | `2025-11-10`  |
|    P2+D4    |      Prototípus II. és frissített tesztelési dokumentáció, egyéni jelentés  | `2025-12-01`  |



## 8. Feladatlista

A következőkben a tervezett feladatok részletes összefoglalása található.



### 8.1. Projektterv (1. mérföldkő)

Ennek a feladatnak az a célja, hogy `megvalósításhoz szükséges lépéseket, az erőforrásigényeket, az ütemezést, a felelősöket és a feladatok sorrendjét meghatározzuk, majd vizualizáljuk Gantt diagram segítségével.`

Részfeladatai a következők:

#### 8.1.1. Projektterv kitöltése

Felelős: `Mindenki`

Tartam:  `4 nap`

Erőforrásigény:  `1 személynap/fő`


#### 8.1.2. Bemutató elkészítése

Felelős: `Géczi Zsófia, Fehér Dajana`

Tartam:  `2 nap`

Erőforrásigény:  `0.5 személynap`

Szeged, `2021-10-25`.
