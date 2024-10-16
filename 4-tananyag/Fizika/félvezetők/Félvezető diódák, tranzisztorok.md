## Elektroncsövek
![[Pasted image 20241011135617.png]]
#### Korábban
- Az elektroncsövek gyakorlatilag kis méretű katódsugárcsövek voltak.
- Az elektródák számától függően az elektroncső lehet **dióda** (két elektróda), **trióda** (három elektróda), **tetróda** (négy elektróda) stb.
- *Főként egyenirányításra, erősítésre, elektromos rezgés keltésére, illetve kijelzésre használták. 
>- Magas fogyasztásuk, melegedésük, nagy méretük és rövidebb élettartamuk miatt a félvezetők csaknem mindenhonnan kiszorították ezeket.

#### Jelenleg
- Különleges területeken használják
	-  nem érzékenyek a radioaktív sugárzásra és az elektromágneses zavarokra, szemben a félvezetőkkel.
- A professzionális **hangtechnika** is előszeretettel használja ezeket az erősítőkben, mert a szakértők szerint kellemesebb hangzást hoz létre. 
- Speciális elektroncsövet, úgynevezett magnet ront alkalmaznak a **mikrohullámú sütőkben** is.
## Diódák
### A félvezető dióda, p-n átmenet 
**A félvezető dióda (kristálydióda) általában szilícium alapanyagú, egy n- és egy p-típusú félvezető rétegből áll.**
##### Létrehozása
- A szilíciumkristály **egyik felét p-típusúan, a másik felét n-típusúan adalékolják**. 
- Elektromosan feszültségmentes állapotban a **p rétegből lyukak, az n rétegből elektronok diffundálnak** a másik rétegbe,
- **rekombinálódnak** (újraegyesülnek) az ott található elektronokkal, illetve lyukakkal.
- ![[Pasted image 20241011144404.png]]
- Emiatt a két réteg határán töltéshordozókban szegény határréteg alakul ki.
	- Magas ellenállás
- A határréteget p-n átmenetnek nevezik. 
	- Ennek vastagsága néhány mikronnál nem nő tovább. 
	- A határréteg kiszélesedését ugyanis gátolja a rácsionok között kialakult elektromos erőtér (potenciálgát). 
##### Egyensúlyi állapot jön létre.
![[Pasted image 20241011145134.png]]

### Félvezető dióda nyitó irányú kapcsolása
#### Ha +0,5 V és +0,7 V közötti feszültséget kapcsolunk a dióda végei közé (p->n) 
- az elektromos mező feltölti a határréteget töltéshordozókkal
- megszünteti annak szigetelő jellegét
- a dióda vezetővé válik **(nyitó irányú kapcsolás)**
- ![[Pasted image 20241011145956.png]]
### Félvezető dióda záró irányú kapcsolása 
#### Ha a külső feszültségforrás pozitív sarkát a dióda n oldalához, a negatívat a p oldalához 
- az elektromos mező kiszívja a mozgásképes töltéseket a határrétegből, kiszélesedik a határréteg. 
- **A dióda szigetelővé válik, lezár (záró irányú kapcsolás).**
![[Pasted image 20241011150327.png]]
### Félvezető dióda jelleggörbéje (karakterisztikája)
#### Nyitó irányú kapcsolás esetén
- a feszültség növelésével nő az áramerősség, a dióda vezeti az áramot 
#### A záró irányú kapcsolás esetén 
- A dióda csak nagyon kis mértékben vezet (az áramerősség néhány μA). 
- A letörési feszültség esetén az elektromos térerősség kiszakítja a határréteg vegyértékelektronjait
	- ütközési ionizációval további töltéshordozókat hoznak létre.
	- **Olyan nagy záró irányú áram jöhet létre, amely tönkreteszi a diódát. 
	- *Áramkorlátozó ellenállást kell alkalmazni a dióda védelmére
![[Pasted image 20241011150934.png]]

## A tranzisztor (bipoláris tranzisztor)
### A tranzisztort három adalékolt félvezető réteg alkotja, ezek neve: 
- **emitter (E)
- **bázis (B)  
- **kollektor (C).**
### A rétegek 
- n-p-n vagy p-n-p elrendezésűek. 
- A bázis jóval vékonyabb, mint a másik két réteg
- Elektromos kivezetés
### A tranzisztor két szembekapcsolt diódának tekinthető
- Belsejében két p-n átmenet (határréteg) van. 
### Áramkörei:
- az emitterbázis határréteg nyitó irányú
- a bázis-kollektor határréteg záró irányú feszültséget kap.
![[Pasted image 20241011151919.png]]

### Használata:
 - Elsősorban erősítőként és kapcsolóként működik
 - sok más célra is használható. 
 - Az áramerősítés mértéke akár többszázszoros is lehet. 
#### Egy egyszerű modell a tranzisztor működésének szemléltetésére: 
 - a tranzisztor egy zárható-nyitható csapként képzelhető el (bázis), amellyel az átfolyó víz (kollektoráram) könnyen, kis energiával szabályozható.
 - ![[Pasted image 20241011152153.png]]
 >[!note] Jobban tükrözné a tranzisztor működését egy olyan modell, amelyben a csap nyitását is a víz szabályozná.ű
## Trióda
### A tranzisztor elődje, a trióda három elektródát tartalmazott 
- **anód 
- **katód 
- **rács** 
> A rács fémhálóhoz hasonlítható elektróda, amelyen áthaladhatnak a katódból kilépő elektronok az anód felé haladva. 
###### A rácsfeszültséggel vezérelhető az anódáram, mint a tranzisztornál a bázis-emitter feszültséggel a kollektoráram
![[Pasted image 20241011152901.png]]
