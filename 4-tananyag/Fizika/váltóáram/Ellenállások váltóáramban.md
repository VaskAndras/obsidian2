
## Sima Ohmos ellenállás
 
 ![[Pasted image 20240925232054.png]]


### Egyenáram 
- Fenti eset
- Kössünk sorosan egy izzót és egy ellenállást! Először egyenfeszültségre kapcsoljuk, majd azonos effektív értékű váltakozó feszültségre. Azt tapasztaljuk, hogy az izzó mindkét esetben azonos fényerővel világít. Az ohmos ellenállás értéke azonos az egyenáramú és a váltakozó áramú ellenállás esetén.
>[!Warning] Ismétlés
>Egyenes vezető ellenállása
$R=\rho\frac{l}{A}$

### Váltóáram 
- Lenti eset
- Nincs különbség
>[!Tip] Számolás
> Ellenállás
$R=\frac{\mathrm{U}_{eff}}{\mathrm{I}_{eff}}=\frac{\mathrm{U}_{max}}{\mathrm{I}_{max}}$ 

![[Pasted image 20240927185726.png]]

## Tekercs ellenállása


![[Pasted image 20240925233338.png]]
### Egyenáram
- Nincs ellenállás

### Váltóáram
- Váltakozó áram esetén az izzó fényereje csökken. Fokozhatjuk a fényerő csökkenését, ha növeljük a tekercs induktivitását (vasmagot teszünk a tekercsbe). 
- Az áramkör ellenállása, azaz impedanciája jelentősen megnőtt. A többletellenállás a tekercs önindukciójával magyarázható. 
- Az indukált áram akadályozza az őt létrehozó hatást (Lenz törvénye).
- A tekercsnek a váltakozó árammal szemben tanúsított ellenállását induktív ellenállásnak nevezzük. Az induktív ellenállás egyenesen arányos a váltakozó áram frekvenciájának és a tekercs induktivitásának a szorzatával az arányossági tényező a 2π.

>[!note] Fogalom
>A többletellenállást induktív ellenállásnak nevezzük. Jele: $\mathrm{X}_{L}$, mértékegysége az Ω

>[!tip] Számolás
>$\mathrm{X}_{L}=L*\omega$

- Az olyan tekercset, amelynek ohmos ellenállása nulla (vagy elhanyagolhatóan kicsi az induktív ellenálláshoz képest), ideális tekercsnek nevezzük.

### Feszültség és áramerősség
###### Azt vizsgáljuk, hogy egy egyenáramú áramkörben az áramkör zárásának és nyitásának pillanatában milyen lesz a feszültség és az áramerősség viszonya.
- Az áramkör zárásának pillanatában a gyors változás miatt az indukált feszültség maximális lesz. Ugyanakkor az áram Lenz-törvénye miatt csak lassan növekszik. 
- Az áramkör nyitásakor a mágneses mező gyors változása nagy feszültséget indukál, ami az előzővel ellentétes irányú. Ez késlelteti az áram megszűnését. 


![[Pasted image 20240927190732.png]]

###### Tehát tekercs jelenlétében az áram késve követi a feszültséget. Ideális esetben az áram $90^\circ$-os fáziskéséssel követi a feszültséget.


![[Pasted image 20240925234203.png]]

- Kétsugaras oszcilloszkóppal kimutathatjuk, hogy az ideális tekercsen folyó váltakozó áram az önindukció késleltető hatása miatt egynegyed periódust késik a tekercsen mérhető feszültséghez képest.
- Ez ideális esetben 90°-al késik

>[!tip] Számolás
>Pillanatnyi áramérősség
>$I=\mathrm{I}_{max}*\sin\left(\omega t - \frac{\pi}{2} \right)$


## Kapacitív ellenállás

- Kondenzátor ellenállása

- ![[Pasted image 20240925235157.png]]


### Egyenáram
- az izzó nem világít
- kondenzátor megszakítja az áramkört
### Váltóáram
- Az Izzó világít
- Ha váltakozó áramú áramkörbe helyezzük a kondenzátort, akkor nem jön létre szakadás, mert a periódusidő negyedrészében a kondenzátor feltöltődik, majd kisül, a harmadik negyedben ismét feltöltődik ellentétes polaritással, majd ismét kisül.
- A váltakozó árammal szemben a kondenzátor véges ellenállást jelent.
  
>[!tip] Számolás
>Pillanatnyi áramérősség
>$I=\mathrm{I}_{max}*\sin\left( \alpha*\omega t + \frac{\pi}{2} \right)$

### Mitől függ a kapacitív ellenállás?
#### A kondenzátor kapacitásától 
- Minél nagyobb a kondenzátor kapacitása, annál kisebb a kapacitív ellenállása. 
- Oka, a nagy kapacitású kondenzátor sok töltést tud tárolni, ezért feltöltődéskor is, és kisüléskor is nagy a töltés áramlás. 
- Ez nagy áramerősséget eredményez, ami kis ellenállás következménye. 
#### A váltakozó áram frekvenciájától 
- A váltakozó áram frekvenciája és a kapacitív ellenállás között fordított arányosság van, minél nagyobb a frekvencia 1s alatt annál többször töltődik fel és sül ki a kondenzátor. 
- Ez nagyobb töltés áramlást és kisebb ellenállást jelent.

###### A kapacitív ellenállás egyenesen arányos a váltakozó áram frekvenciájának és a kondenzátor kapacitásának a szorzatából képzett mennyiség reciprokával, az arányossági tényező $\frac{1}{2\pi}$.

>[!tip] Ebből:
>$$
>X_{C}=\frac{1}{2\pi fL}=\frac{1}{\omega L}
>$$

### Feszültség és áramerősség
###### Ábrázoljuk a pillanatnyi feszültség és áram értéket egy egyenáramú áramkörben lévő kondenzátoron az áramkör zárásának és nyitásának pillanatában!
![[Pasted image 20240927193700.png]]
- Az áramkör zárásakor a töltések akadály nélkül áramlanak a feltöltetlen kondenzátor felé.
- Ilyenkor nagy az áramerősség. Ugyanakkor a zárás pillanatában a fegyverzetek között a feszültség nulla. 
- Ahogy töltődik fel a kondenzátor úgy nő a fegyverzetek közötti feszültség, és csökken az áramerősség. 
- Az áramkör nyitásakor ellentétes irányú töltésáramlás indul meg, és a fegyverzetek közötti feszültség csökken.
###### Ideális esetben a kondenzátoron a feszültség 90°-al siet az áramhoz képest.
~~~
- ![[Pasted image 20240926215613.png]]
~~~



~~~
![[Pasted image 20240926215948.png]]
~~~



