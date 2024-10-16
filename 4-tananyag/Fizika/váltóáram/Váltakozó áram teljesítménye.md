## Pillanatnyi teljesítmény
##### Egyenáramú áramkörben a teljesítményt a feszültség és az áramerősség szorzata adja.
>[!warning] Ismétlés
>Egyenáramú áramkör esetén 
>$P=U*I$

##### Váltakozó áramú áramkörben a feszültség és az áramerősség pillanatnyi értékeinek a szorzatát pillanatnyi teljesítménynek nevezzük. 
>[!note] Pillanatnyi teljesítmény 
>A pillanatnyi teljesítmény számértéke megmutatja, hogy mennyi energiát venne fel a fogyasztó időegység alatt, ha a feszültség és az áramerősség nem változna.
## Ohmos ellenállás
- A fenti esetben a feszültség és az áramerősség állandó, ezért a teljesítmény
- Váltóáram esetében a A feszültés értéke folyamatosan változik, ezért 
 markdown
 ![[Pasted image 20240925225944.png]]

- Ohmos ellenállás esetén a feszültség és áramerősség pillanatnyi értékei azonos fázisban változnak, nincs fáziseltolódás. A teljesítmény mindig pozitív, a nulla és a maximális érték között mozog. Ezt a teljesítményt hatásos vagy átlagos teljesítménynek nevezzük.
>[!tip] Számítás
>$$
>\mathrm{P}_{hatásos} = \mathrm{U}_{eff}*\mathrm{I}_{eff}=\frac{\hat{U}}{\sqrt{ 2 }}
\frac{\hat{I}}{\sqrt{2}}=\frac{1}{2}\hat{U}\hat{I}
>$$

## Induktív ellenállás
![[Pasted image 20240926224037.png]]
##### A pillanatnyi teljesítmény-idő grafikonból látható
Az ideális tekercs negyedperiódusonként energiát vesz fel a generátortól a mágneses mezejének a felépítéséhez
ugyanakkora energiát a következő negyed periódusban vissza is szolgáltat. 
>[!warning] Az ideális tekercsnek időbeni átlagban a fogyasztása nulla.
## Kapacitív ellenállás

![[Pasted image 20240926224443.png]]

###### A pillanatnyi teljesítmény-idő grafikonból látható
- Az ideális kondenzátor is negyedperiódusonként energiát vesz fel a generátorból 
- és ugyanakkora energiát a következő negyedperiódusban vissza is szolgáltat. 
- Amikor pozitív a teljesítmény, a kondenzátor feltöltődik, felvesz energiát az áramforróstól. 
- A negatív teljesítmény fordított irányú energiaáramlást jelent, a kondenzátor kisül, és az elektromos mező energiája átalakul az áramforrás energiájává. 
>[!warning] Az ideális kondenzátornak időbeni átlagban a fogyasztása nulla.

## RC vagy RL kör teljesítményfelvétele 
- Időbeni átlagban jelentősebb a generátortól felvett teljesítmény, mint amit az induktív ellenállás és a kondenzátor visszaszolgáltat. 
- Váltakozó áramú áramkörben az U* I szorzat a felvett teljesítményt nem jellemzi. 
#### Ezt a teljesítményt látszólagos teljesítménynek nevezzük.
>[!note] Látszólagos teljesítmény
>- Meddő része
>- hatásos része
>	- van.

$$
 \mathrm{P}_{látszólagos}=\mathrm{U}_{eff}*\mathrm{I}_{eff}
 $$
$$
\begin{aligned} 
P_{\text {látszólagos }} & =U_{\text {eff }} \cdot I_{\text {eff }}, \\ P_{\text {hatásos }} & =U_{\text {eff }} \cdot I_{\text {eff }} \cdot \cos \varphi, \\ P_{\text {meddō }} & =U_{\text {eff }} \cdot I_{\text {eff }} \cdot \sin \varphi .\end{aligned}
$$
#### A fenti hatásos és látszólagos teljesítmény kapcsolata
>[!tip] Számítás
>$$
>P_{látszólagos}^2=P_{hatásos}^2*P_{meddő}^2
>$$



