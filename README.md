# Vaja-6-Vec-kanalna-scan-mode-ADC-pretvorba-z-Nucleo-L476RG
2.
d)	Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. To bodo pini:
PA0 (A0), PA1 (A1) in PA4 (A2).
Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? 
A
f)	Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? 
ADC1_IN5, ADC1_IN6 in ADC1_IN9
h)	V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4 MHz. Koliko bo izbrana vrednost parametra? 
Asynchronous clock mode divided by 4.
j)	Koliko je privzeta vrednost paramtera Number of Conversion? 
1 
k)	Čas vzorčenja Sampling Time izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah? 
26,125 μs 

3.
e)	Kaj pomeni kratica DMA? 
Direct Memory Access.

Komentar:
Z večkanalno ADC pretvorbo v SCAN načinu beremo vrednosti na treh potenciometrih. Vrednosti, ki so shranjene v array-u opazujemo na debug-u.
