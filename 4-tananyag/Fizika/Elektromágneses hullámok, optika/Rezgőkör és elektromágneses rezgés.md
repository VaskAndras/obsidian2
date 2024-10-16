## Rezgőkör 
#### Rezgőkörnek nevezzük a C kapacitású kondenzátorból és az L induktivitású tekercsből álló vezetőkört.
- Ha a vezetőkörben az ohmos ellenállás elhanyagolható, akkor ideális rezgőkörről beszélünk.
### Működése
![[Pasted image 20241012214425.png]]
- Ha a kondenzátort egyenáramú áramforrásra kapcsolva feltöltjük, akkor a fegyverzetek között elektromos tér keletkezik. 
- Ezt követően a kapcsolót az 1-es helyzetből a 2-be kapcsoljuk. 
- Ilyenkor, ha középállású áramerősségmérő van a körben, az néhány lengést végez. 
### Energiaátalakulás rezgőkörben 
##### Kondenzátor oldala
- t=0 pillanatban a kondenzátor maximálisan fel van töltve. 
- A rezgőkör teljes energiamennyisége elektrosztatikus mező formájában a kondenzátor fegyverzetei között van. 
$$
E=\frac{1}{2}CU^2
$$
![[Pasted image 20241012215742.png]]
##### Tekercs oldala
- A kondenzátor maximális feltöltődése utáni pillanatban megindul a kondenzátor kisülése. 
- Csökken a fegyverzetek közötti elektromos mező energiája
- Az áram növekedése miatt nő a tekercsben a mágneses mező energiája. 
- $t=\frac{T}{4}$ időpillanatban az áram maximális lesz. 
- A rezgőkör teljes energiáját a tekercs tárolja mágneses mező formájában
$$
E=\frac{1}{2}LI^2
$$
![[Pasted image 20241012215730.png]]
##### 3. lépés
- A következő pillanatban megszűnik az a forrásos elektromos mező, ami eddig a töltések áramlását biztosította.
- Az áram lassan csökken.
- A tekercsben a mágneses mező változását idézi elő. 
- Ekkor Lenz-törvénye szerint feszültség indukálódik. 
- Az indukált feszültség által indított áram elkezdi feltölteni a kondenzátort, 
	- az előzővel ellentétes polaritással.
- $t=\frac{T}{2}$ időpillanatra nullává válik a mágneses mező
	- ekkorra a kondenzátor már feltöltődött.
![[Pasted image 20241012215719.png]]

#### A következő félperiódusban az előzőhöz hasonló folyamat játszódik le, de ellentétes irányba.
![[Pasted image 20241012215654.png]]
>[!note] Elektromágneses rezgés
>A rezgőkörben az elektromos és mágneses mező energiájának periodikus egymásba alakulását elektromágneses rezgésnek nevezzük

## Csillapítatlan és csillapított elektromágneses rezgések 
#### Ha a rezgőkörnek nem lenne vesztesége, akkor a rezgések amplitúdója állandó lenne. 
- Ebben az ideális esetben alakulna ki a csillapítatlan elektromágneses rezgés. 
#### Az ohmos ellenállás, a mágneses és dielektromos veszteségek miatt a rezgések amplitúdója folyamatosan csökken.
- Így a valóságban csillapított elektromágneses rezgések jönnek létre.
## Rezgőkör saját frekvenciája
- Egy rezgőkörben minden külső vezérlés nélkül kialakuló elektromágneses rezgések frekvenciáját a rezgőkör saját frekvenciájának (f0) nevezzük. 
$$
E_{C}=E_{L}
$$
$$
\frac{1}{2}CU^2=\frac{1}{2}LI^2
$$
$$
CI^2X_{C}^2=LI^2
$$
$$
C\frac{1}{4\pi^2f_{0}^2C^2}=L
$$
$$
f_{0}^2=\frac{1}{4\pi^2 LC}
$$
#### Thomson formula:
$$
f_{0}=\frac{1}{2\pi \sqrt{ LC }} 
$$
__Látható, hogy a rezgőkör saját frekvenciája csak a kondenzátor kapacitásától és a tekercs induktivitásától függ__

## Csatolt rezgések, induktív csatolás
#### Csatolt rezgésről akkor beszélünk, ha két rezgőkör egymással olyan kapcsolatban van, hogy egymásnak energiát tudnak átadni.
- Ha az 1. rezgőkörben elektromágneses rezgéseket hozunk létre
- Rövid időn belül a 2. rezgőkörben is kialakulnak az elektromágneses rezgések
##### Oka
- Az 1. tekercsben az időben változó mágneses mező létrehoz egy örvényes elektromos mezőt, amely áramot indít a 2. rezgőkörben.
- ###### Ezt a jelenséget induktív csatolásnak nevezzük. 
##### Kialakulása
A két rezgőkör között akkor a legtökéletesebb az energiaátadás, ha a két rezgőkör saját frekvenciája megegyezik, 
- vagyis $L_{1}C_{1}=L_{2}C_{2}$ 
- Ilyenkor lép fel a __rezonancia.
