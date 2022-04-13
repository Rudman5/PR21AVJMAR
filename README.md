
## Člani skupine

| Ime in priimek |
| -------------- |
| Andraž Rudman |
| Jaka Maležič |
| Alen vidmar |


## Podatki

Podatke za projektno nalogo smo našli na spletnem portalu [covid-19.sledilnik.org](https://covid-19.sledilnik.org/sl/data) na temo covid-19 v sloveniji.



## Cilji
- Vizualizacija odvisnost hospitalizacije od cepljenja. 
- Ugotoviti kdaj se virus najbolj širi.
- 



## Opis podatkovne zbirke
Atributi se nahajajo v različnih ".csv" datotekah in so razvrščeni:
- `bolnisnice.csv`: Stanje v bolnisnicah med 10.3.2020 in 5.4.2022. Atributi:datum, skupno stevilo postelj, polnih postelj, praznih postelj, mest na intenzivni, zasednih mest na intenzivni, skupaj raspiratorji, prosti raspiratorji, 
- `cepljenje.csv`: Stevilo cepljenih po dnevih med 26.12.2020 in 5.4.2022. Atributi: datum, stevilo cepljenih, stevilo cepljenih z drugim odmirkom, stevilo cepljenih s tretjim odmerkom
- `hospitalizacije.csv`: V tej podaktkovni zbirki imamo stevilo hospiatiliziranih, razdeljon na starostne skupine in nato v skupini cepljeni in necepljeni
- `okuzbe.csv`: V tej zbirki imamo število okuzb glede na skupine, necepljeni potrjeni, polno cepljeni potrjeni, cepljeni z dodatnim odmirkom potrjeni
- `okuzbe2.csv`: V tej zbirki imamo atribute: datum, stevilo opravljenih testov, stevilo pozitivnih testov, stevilo opravljenih hagt testov, stevilo pozitivnih hagt testov



## Priprava podatkov.
Na začetku smo odstranili podatk ki ih nismo potrebovali. 
Nato smo se odločili da bomo naše podatke povezovali z datumi meritev.


Potem smo se lotili iskanja zanimivih podatkov in njihove vizualizacije. 


## Začetne ugotovitve in vizualizacija.

Prikaz števila okuženih na mesec v skupinah: cepljeni, necepljeni
[![Figure-1.png](https://i.postimg.cc/7P3cQSFp/Figure-1.png)](https://postimg.cc/jCjZDndX)

[![Figure-2.png](https://i.postimg.cc/VkQJLQGS/Figure-2.png)](https://postimg.cc/F7prDqQm)

Število okužb v letnem času:

[![Figure-3.png](https://i.postimg.cc/nL5z5yDc/Figure-3.png)](https://postimg.cc/Mc7qfr5h)

Sedem dnevno povprečje okužb:

[![Figure-4.png](https://i.postimg.cc/rmx8HKTQ/Figure-4.png)](https://postimg.cc/G83w83Hy)

Število polno cepljenih:

[![Figure-5.png](https://i.postimg.cc/Cx9pVSmt/Figure-5.png)](https://postimg.cc/RW1D75rQ)






