 ## Eredő ellenállás
Váltakozó áramú áramkörben az eredő ellenállást impedanciának nevezzük.

>[!note] Impedancia
>Látszólagos ellenállás 
>Váltóáramú körökben az ohmos, induktív és kapacitív ellenállás együttes ellenállása
>Jele: Z
>Mértékegysége: $\ohm$

>[!note] Admittancia
Az impedancia reciproka a váltakozó áramkör vezetőképessége az admittancia. 
Jele: Y 

### Az impedancia frekvenciafüggő és frekvencia független ellenállásokból áll. 
#### Frekvenciafüggő -- Reaktancia
- ide tartozik 
	- kapacitív ellenállás
	- induktív ellenállás
#### Ellenállásfüggő -- Rezisztencia
- tiszta ohmos ellenállás

### Ohm törvénye

>[!tip] Számolás
>$$
>Z = \frac{\mathrm{U}_{eff}}{\mathrm{I}_{eff}}=\frac{\mathrm{U}_{max}}{\mathrm{I}_{max}}
>$$

Számítások szerint sorosan kapcsolt ellenállások esetén a teljes kapocsfeszültség nem egyenlő a részfeszültségek összegével. Ennél a kapcsolásnál az effektív feszültségek és az ellenállások vektorként összegződnek.


![[Pasted image 20240926221509.png]]
- Az ábrán XL > XC. A három vektor eredőjének nagysága a Z impedancia. 
- A fázisszög (φ) az R és Z „vektorok” által bezárt szög.
- Pitagorasz-tétellel, illetve szögfüggvénnyel kiszámíthatjuk az impedancia és a fázisszög nagyságát.

>[!tip] Számolás
>$$
>Z=\sqrt{ R^2+(\mathrm{X}_{L}-\mathrm{X}_{C})^2 }
>$$
>Szöggel:
>$$
>tg\rho=\frac{\mathrm{X}_{L}-\mathrm{X}_{C}}{R}
>$$
>$$
>\cos \rho=\frac{R}{Z}
>$$

>[!tip] A feszültségforrás feszültsége:
>$$
>U^2=\mathrm{U}_{R}^{2}+(\mathrm{U}_{L}-\mathrm{U}_{C})^2
>$$
## Legkisebb elleállás
>[!warning] Legnagyobb áramerősség!!

Ha:
$$
\mathrm{X}_{C}=\mathrm{X}_{L}
$$
$$
\omega L= \frac{1}{2\pi C}
$$
$$
f=\sqrt{ \frac{1}{4\pi^2LC} }
$$

$$
f=\frac{1}{2\pi}\sqrt{ \frac{1}{LC} }
$$
>[!warning] Feszültség rezonancia 

## RL körök
$$
Z=\sqrt{ R^2+(\mathrm{X}_{L})^2 }
$$
$$
\cos \rho=\frac{R}{Z}
$$
## RC Körök
$$
Z=\sqrt{ R^2+(\mathrm{X}_{C})^2 }
$$
$$\cos \rho=\frac{R}{Z}$$
## Feszültségforrás feszültsége

$$
U^2=U_{R}^2+(U_{L}+U_{C})^2
$$

## Legkisebb ellenállás

Vektorosan:
- Ha 
  $$X_{C}=X_{L}$$
  $$\omega L=\frac{1}{\omega C}$$
$$
\omega^{2}=\frac{1}{LC}
$$
$$
4\pi^{2} f^{2}=\frac{1}{LC}
$$
$$
f=\frac{1}{2\pi}\sqrt{ \frac{1}{LC} }
$$
>[!note]
>Ez a frekvencia a rezonanciafrekvencia, ezen a frekvencián rezonálnak

