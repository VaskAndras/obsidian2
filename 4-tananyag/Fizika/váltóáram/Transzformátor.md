 >[!note] Három magyar mérnök találmánya
> Déri Miksa, Bláthy Ottó, Zipernowszky Károly. 

## Működése
#### Ez egy áram átalakító berendezés. 
- A közös lemezelt vasmagon helyezkedik el a primer és a szekunder tekercs. 
- A primer tekercsre kapcsolják az átalakítani kívánt váltakozó áramot. 
- Ennek hatására a zárt vasmagban egy időben változó mágneses mező alakul ki. 
- Ez indukál feszültséget a szekunder tekercsben. 
#### A szekunder és a primer oldalon mérhető feszültségek aránya megegyezik a menetszámok arányával.
>[!tip] Számolás
>$$
\frac{U_{\text{szekunder}}}{U_{\text{primer}}}=\frac{N_{\text{szekunder}}}{N_{\text{primer}}}
>$$

## Teljesítménye
##### Ideális esetben a primer oldalon felvett teljesítmény megegyezik a szekunder oldalon leadott teljesítménnyel 
- (teljesítmény felvétel csak akkor történik, ha a szekunder oldalt terheljük). 
- A levezetésből látható, hogy az egyes oldalakon mérhető áramerősségek fordított arányban vannak a menetszámmal.
>[!tip] Levezetés
>$$P_{sz}=P_{p}$$
>$$I_{sz}U_{sz}=I_{p}=U_{p}$$
>$$\frac{I_{sz}}{I_{p}}=\frac{U_{p}}{U_{sz}}=\frac{N_{p}}{N_{sz}}$$


## Felhasználása

#### A transzformátor fontos szerepet tölt be a villamos energia gazdaságos szállításában.
- A nagy távolságok miatt jelentős lehet a távvezetékek R ellenállásán fellépő $I^2R$ teljesítményveszteség, amely a vezetékeket melegíti. 
- Mivel a veszteség az áramerősség négyzetével arányos, az áramerősség csökkenése nagy megtakarításokat eredményezhet. 
	- Ha például 220 $V$ helyett 220 $kV$-on továbbítják az energiát, akkor az áramerősség csak ezredrésze lesz az eredetinek. 
	- A vezetékben fellépő veszteség pedig a fenti összefüggést felhasználva milliomod részére csökken, ezért gyorsan megtérül a transzformátorállomás építési költsége. 
- Ezért a fogyasztók által igényelt teljesítményt kis áramerősségű, de nagy feszültségű távvezetékeken szállítják. 
- A generátor és a távvezeték között feltranszformálást, a távvezeték és a fogyasztó között letranszformálást alkalmaznak.

![[Pasted image 20240927210845.png]]  


### Nézzük az elektromos hálózat működési sémáját: 
- Az erőműben a háromfázisú generátor által előállított áramot 400 kV-ra feltranszformálják. 
- Így szállítják a távvezetéken, majd az adott területre érve letranszformálják 40 kV-ra. 
- 40 kV-on szállítják a körzetekben, ahol a központi áramelosztóban újabb letranszformálás következik, most már 1500 V-ra. 
- Így továbbítják a végső állomásra, ahol 220 V-ra transzformálják le, majd így kerül a fogyasztókhoz. 

##### Az első üzemi célokra használható transzformátort 1885-ben Bláthy Ottó, Déry Miksa és Zipernowszky Károly magyar mérnökök készítették.
