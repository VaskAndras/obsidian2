## A diódák alkalmazása 
### Legfőképpen
- **a váltakozó feszültség egyenirányítására 
- **feszültségszabályozásra használják.** 
#### Váltakozó feszültségből lüktető egyenfeszültséget hoznak létre.
- Az akkumulátoros töltőkben (pl. mobiltelefonok töltése)
- Az egyenfeszültségű tápegységekben (pl. laptop tápegysége) a hálózati feszültség egyenirányítására diódákat használnak
## Egyutas egyenirányító-kapcsolás
- Egy diódát alkalmaznak a váltakozó feszültség egyenirányításra.
![[Pasted image 20241011154346.png]]
#### Működése:
- Az $U_{1}$ váltakozó feszültséget a transzformátor primer tekercsére kapcsoljuk
- A dióda a szekunder __feszültség ($U_{2}$) pozitív félperiódusában vezet (nyitó irány)__
- A negatív __félperiódusban (záró irány) szigetelőként viselkedik.__ 
- Az egyenirányított feszültséget az $R_{t}$ ellenálláson tudjuk megmérni. 
- Az egyenfeszültség és annak teljesítményét integrálszámítással kapjuk: 
	- A számítások szerint az egyenfeszültség a váltakozó feszültség csúcsértékének 32%-a, 
	- a kimenő teljesítmény a bemenő teljesítmény 40,5%-a.

>[!note] 
>Erősen lüktető az egyenfeszültség, ugyanis a negatív félperiódusokban zérus

![[Pasted image 20241012103648.png]]

## Feszültségszabályozás diódákkal 
>[! note ] Zenerdiódák 
A feszültségszabályozásra is használt diódákat Zenerdiódáknak nevezzük. 
### Zenerdiódák működése
- Működése nyitó irányban megegyezik a a szílicium félvezető diódákkal,
- A záró irányban a letörési tartományban működik.
### Felhasználásuk
- Zener-diódákat tartalmaznak az elektronikus áramkörök tápegységei, továbbá a televíziókészülékek, nyomtatók
## Diódák alkalmazásai
### Fotodiódák
#### Belső fotoeffektus
- Bennük fény hatására elektron-lyuk párok keletkeznek,
- a fotodióda vezetővé válik. 
- Feszültség hatására áram keletkezik,
	- beeső fénnyel arányos
	- (fénymérés, fotocella). 
#### Szerepük
- Fényimpulzusokat elektromos jellé alakítják.
- Fotodiódákat alkalmaznak a digitális fényképezőgépekben is. 
	- Minden egyes képponthoz (pixelhez) egy miniatűr, szilíciumlapon kialakított fotodióda tartozik.
	- Ezek a fotodiódák a beeső fénnyel arányos töltéscsomagot küldenek tovább a velük sorosan kapcsolt kondenzátor felé. 
	- Ezekből a kondenzátorokból olvassa ki egy megfelelő áramkör a képnek megfelelő elektromos jeleket.
![[Pasted image 20241012211521.png]]

### Napelemek 
#### A napelemekben a fotodiódát áramforrásként használjuk: 
- az elnyelődő fény energiája elektron-lyuk párok létrehozására és szétválasztására fordítódik. 
- A napelem a fényenergiát villamos energiává alakítja
![[Pasted image 20241012211911.png]]
### LED-diódák 
##### light emitting diode
#### A dióda nyitó irányú kapcsolása esetén
- A határrétegbe áramló elektronok és lyukak rekombinálódnak
- energia szabadul fel.
- Féynkibocsátás. 
![[Pasted image 20241012212348.png]]
![[Pasted image 20241012212410.png]]
### A félvezető lézerek 
#### Lézerdiódák
- A LED-diódákhoz hasonlóan működnek. 
- Lényeges különbségek: 
	- a lézerfény időben és térben koherens, egyszínű, nagy az energiasűrűsége.
#### A lézerdiódák két vagy több komponensű félvezetők:
- Például: gallium-arzenid (Ga-As). 
- Az alapkristály Ga-As,
	- a p és n rétegek létrehozásához általában alumíniumot, foszfort adalékolnak.
- A szilíciumkristály vagy germániumkristály nem alkalmas LED- vagy lézerdióda gyártására.
![[Pasted image 20241012212904.png]]
#### Működése
- A lézerdiódákban a p-n átmenetben az elektron-lyuk rekombináció során a felesleges energia lézerfoton formájában sugárzódik ki. 
- A p-n átmenetre nyitó irányú feszültséget kapcsolnak. 
![[Pasted image 20241012212924.png]]
