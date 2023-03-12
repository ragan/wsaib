Zadanie 3.1

Spółka akcyjna dysponuje kapitałem, na który składa się:
- 100 tysięcy akcji uprzywilejowanych o wartości nominalnej 100 zł / akcja; dywidenda wynosi 8% wartości nominalnej w skali roku; akcje uprzywilejowane spółki nie są przedmiotem obrotu giełdowego, były one sprzedawane według wartości nominalnej. 
- 1 milion 800 tysięcy akcji zwykłych o wartości nominalnej 60 zł/akcja; akcje spółki są notowane na giełdzie, ich cena wynosi obecnie 145 zł/akcję.
- 80 tysięcy obligacji o wartości nominalnej 1 tys. zł/obligacja, oprocentowanych 12% w skali roku; aktualna cena rynkowa obligacji wynosi 1050 zł,
- długoterminowy kredyt bankowy w wysokości 60 800 000 zł, stopa oprocentowania kredytu wynosi 10% w skali roku. 
Spółka charakteryzuje się dobrą kondycją finansową. Dywidenda wypłacona w poprzednim roku właścicielom akcji zwykłych wyniosła 29 zł/akcję. Na podstawie ubiegłych la ustalono, że wzrasta ona przeciętnie o 2,6% rocznie. Ostatnia wypłata odsetek dla posiadaczy obligacji nastąpiła przed 2 miesiącami. Spółka płaci podatek dochodowy według 19% stopy podatkowej. 
Oblicz średni ważony koszt kapitału firmy.

Rozwiązanie zad. 3.1

Algorytm postępowania:

1. Obliczamy koszt (wyrażony w %) poszczególnych składowych kapitału spółki 

Koszt kapitału akcyjnego uprzywilejowanego:
```math
\mathrm{K}_{u} = \frac{0,08*100}{100}*100\%=8\%
```
Koszt kapitału akcyjnego zwykłego:
```math
\mathrm{K}_{Z} = (\frac{29}{145}+0,026)*100\%=22,6\%
```
Koszt kapitału z emisji obligacji:
```math
\mathrm{V}_{0} = 1050*(1-\frac{2}{12}*\frac{12}{100})=1029zł
```
```math
\mathrm{K}_{0} = \frac{0,12*1000}{1029}*(1-0,19)*100\%=9,44\%
```
Koszt kapitału z kredytu bankowego:

```math
\mathrm{K}_{K} = 10*(1-0,19)=8,1\%
```

2. Obliczamy wartość rynkową poszczególnych składników kapitału spółki

Kapitał akcyjny uprzywilejowany:
```math
100 tys. akcji * 100zł / akcja = 10 000 000zł
```
Kapitał akcyjny zwykły:
```math
1 800 000 akcji * 145zł / akcja = 261 000 000zł
```
Kapitał z emisji obligacji:
```math
80000 obligacji * 1029zł/obligacja = 82 320 000zł
```

3. Tworzymy tabelę z kolumnami:
    - składnik kapitału
    - wartość rynkowa składnika
    - % udział składnika w całym kapitale czyli Ux (ułamek)
    - koszt kapitału czyli Kx (wyrażony w %)
    - obliczamy średni ważony koszt kapitału czyli Ux * Kx
    - sumujemy wszystkie Ux*Kx (czyli dla każdego rodzaju kapitału) i otrzymujemy średni koszt kapitału spółki wyrażony w %

|Składniki kapitału|Wartość rynkowa|Udział Ux|Koszt kapitału Kx(%)|Obliczenie średniego ważonego kosztu kapitału|
|------------------|---------------|---------|--------------------|---------------------------------------------|
|akcje uprzywilejowane|10 000 000|0,024|8|0,19%|
|akcje zwykłe|261 000 000|0,630|22,6|14,24%|
|obligacje|82 320 000|0,199|9,44|1,88%|
|kredyt bankowy|60 800 000|0,147|8,1|1,19%|
|suma|414 120 000|1,000||17,50%|

Średni koszt kapitału spółki wynosi więc 17,50%
