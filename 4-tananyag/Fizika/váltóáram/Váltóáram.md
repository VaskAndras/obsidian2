
### Váltakozó áramról akkor beszélünk, ha az áramerősség és a feszültség nagysága is és az iránya is periodikusan változik.

# Váltakozó feszültség
Váltakozó feszültségű áramot generátorral lehet előállítani
>[! Note] Generátor
>Az olyan elektromágneses indukció elvén alapuló berendezést, ami mágneses energiából képes elektromos energiát előállítani, generátornak nevezzük.

 Ha homogén mágneses térben megforgatunk egy vezetőkeretet, Akkor abban váltakozó lesz az indukált feszültség. Ha erre fogyasztót kapcsolunk akkor váltakozó áramú áramkör jön létre.
# Generátor működése

![[Pasted image 20240927182324.png]]

- A kísérlet során a vezetőkeretben indukálódott feszültség nagysága és iránya is periodikusan változik. 
- Figyeljük meg azt a helyzetet, amikor a nulla indukált feszültségű állapothoz képest a vezetőkeret síkja $\alpha$ szöggel fordul el. 
- A vezetőkeret kerületi sebességének nagysága $v_{k}$. A kerületi sebességvektor felbontható az indukcióvonalakkal párhuzamos és az indukcióvonalakra merőleges sebességkomponensekre.
- Mozgási indukció során csak az indukcióvonalakra merőleges sebességkomponenssel kell számolnunk.
 $$
v_{\perp}=v_{k}\sin \alpha
$$
Ahol:
$$
v_{k}=R\omega
$$

>[!warning] Váltakozó áram esetében 
>az ω-t, a váltakozó áram körfrekvenciájának nevezzük.

# Indukált feszültség
>[!note] Számolása
>Mágnesen indukció alapján:
$U_{i}=Blv_{\perp}=Blv_{k}\sin\alpha$

>[!note] Csúcsérték
Mivel a mágneses indukció (B), a vezetőszárak hossza (l), a kerületi sebesség nagysága ($v_{k}$) időben állandó, így a szorzatuk is egy állandó értéket ad. 
Ezt az állandót a váltakozó feszültség csúcsértékének nevezzük.
$\hat{U}=Blv_{k}$

### Indukált feszültség mértéke csúcsértékből
Az előző képletekből:
$$U_{i}=\hat{U}\sin\alpha$$
$$U_{i}=\hat{U}\sin\omega t$$


![[diagram-20240924.svg|#invert]]
A gerjesztett feszültség az idő szinuszos függvénye

>[!warning] Ismétlés
>$f=\frac{1}{T}$
>$\omega=2*\pi*f*\frac{2*\pi}{T}$
>$\alpha=\omega*t$

## Váltakozó áram effektív értéke

>[!note] Fogalom
>A váltakozó áram effektív értékének azt az áramerősséget értjük, mely ugyanannyi idő alatt ugyanannyi munkát végez mintha egyenáramú áramkör lenne.

>[!tip] számítás
>Effektív áramerősség
>$\mathrm{I}_{eff} = \frac{\mathrm{I}{max}}{\sqrt{ 2 }}$
>
>Effektív feszültség
>$\mathrm{U}_{eff} = \frac{\mathrm{I}{max}}{\sqrt{2}}$

A váltóárammal működő elekromos berendezéseken álltalában a feszültségérték az effektív feszültségre vonatkozik.

## Váltakozó áram pillanatnyi értéke

>[!tip] Számítás
>Pillanatnyi feszültség
>$U=\mathrm{U}_{max}*\sin(\omega*t)$
>
>Pillanatnyi áramerősség
>$I=\mathrm{I}_{max}\sin(\omega*t)$



