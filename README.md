# Vaja2-ADC-continuos-conversion-STM32F0

1.Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to?
-PC0.

2.Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?
-ADC_IN10.

3.V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. Kaj opazite?
-Vrednosti se spremenijo na enako vrednost APB1

4.Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana?
-4 MHz

5.Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 ciklov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah?
-62,875 µs.

Komentar:
-Program pretvarja analogno vrednost v digitalno desetiško. S spreminjanjem potenciometra se spreminja vrednost (kot je prikazano v videu). Vrednost lahko spremenimo od 0-255./p>

Domen Zidar in Tim Tušek
