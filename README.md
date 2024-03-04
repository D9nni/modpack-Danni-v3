# Modpack Danni - v3

<div align="center"><img src="https://i.imgur.com/RudMARB.png"></div>

#### Ce moduri contine modpackul?

###### cleo
    1. hudfix.cs - scoate zerourile in plus de la bani
    2. ccontrol.cs - cruise control
    3. changer.cs - schimba vremea /sett /setw - necesita SAMPFUNCS
    4. cp.cs - arata distanta in timp real pana la checkpoint sub radar
    5. fara efect de caldura.cs (a.k.a noMoreHaze.cs)
    6. memory512.cs - incarca texturile la distanta mai mare

###### modloader

Se pot vedea in ierarhia de fisiere, numele sunt foarte sugestive.

    1. modul "fara tufe" elimina tufisurile daca ii setati prioritate mai mare de 50 si dati relog
    2. modul "fara nori" elimina doar norii care incurca atunci cand zburati

###### asi
    1. OutfitFix.asi - crash fix pt interactiunea cu textdrawuri
    2. SAMP.asi - anticrasher
    3. SAMPFUNCS.asi
    4. Screenshot.asi - face screenshoturi mai rapid si nu mai apare in chat textul
    5. colormod.asi - culori mai frumoase
    6. map.asi - harta pe M

###### alte moduri
    1. mod de faruri (VEHTXD2.txd si gta_sa.exe)

[*Descrierea veche (2018)](https://forum.bugged.ro/topic/294852-modpack-by-danni-for-low-medium-pc-v3/)

*au fost scoase modurile .sf care erau interzise pe anumite servere si alte moduri problematice

#### Instalare
    
    1. Creeaza un folder cu un GTA curat.

    2. Instaleaza SAMP peste noul GTA.

    3. Descarca modurile de pe github. 
    3.1. Mergi pe coloana din dreapta paginii la sectiunea Releases si apasa pe Latest.
    3.2. Din josul paginii descarca arhiva .zip cu modurile.

    4. Trage modurile din arhiva in folderul cu jocul.

#### Probleme

La anumite ore seara in interioare e intuneric, se repara cu un /setw 5 de obicei.

Antivirusul v-ar putea detecta SAMPFUNCS ca virus. Modurile pot functiona si fara sampfuncs daca stergeti changer.cs din folderul cleo.
Totusi, va recomand sa il pastrati pentru ca s-ar putea sa aveti nevoie de acel mod de schimbat vremea.

Daca instalati firstPerson modul de Screenshot.asi nu va mai functiona bine (va face ss si samp-ul si modul)

Daca ati identificat un bug, puteti deschide un issue.

#### Recomandari
    
1. Folositi si samp addon peste moduri, pentru a face asta instalati intai sampaddon si apoi samp 0.3.7 peste
dupa ce ati instalat modurile.

#### Alte moduri recomandate:

1. [TheBestSpeedometer](https://forum.bugged.ro/topic/309747-thebestspeedometer-by-gumball3000-cel-mai-bun-vitezometru/)

2. [Mod de tir](https://forum.bugged.ro/topic/310128-mod-de-tir/) 




