# Kisaveikkaus-sovellus
## Sovelluksen tarkoitus
Sovelluksen tarkoituksena on luoda ympäristö kaveriporukoiden tms. kisaveikkauksien ylläpitämiseen. Sovellukseen siis luodaan kulloinkin tarpeellinen turnaus tai vastaava, johon voidaan kutsua osallistujia. Osallistujat voivat sitten täyttää veikkauksensa järjestelmään. Ylläpitäjä päivittää otteluiden tulokset, jolloin sovellus laskee kunkin käyttäjän pisteet halutun pisteytystavan mukaisesti, ja järjestää osallistujat paremmuusjärjestykseen.

## Sovelluksen toiminta
### Perustoiminta
Sovelluksen käytön perusflow on seuraava:
* Omistaja luo turnauksen, lisää ottelut aikatauluineen, ja valitsee pisteytystavan
* Osallistujat liittyvät turnaukseen, tekevät veikkauksensa ja alkavat jännittää tuloksia
* Omistaja täyttää otteluiden tapahduttua tulokset
* Halutessaan turnaus lukitaan heti alussa, tai tuloksia voi päivittää aina ennen kyseisen ottelun päivää
* Turnauksiin voidaan lisätä mahdollisesti erikoisempia kohteita, kuten avoimia kysymyksiä, maalikuningas yms. Avoimien kysymysten tapauksessa omistajan vastuulla on pisteyttää vastaukset
* Osallistujat pystyvät seuraamaan myös muiden osallistujien veikkauksia, tuloksia ja pisteitä

### Roolit
Sovelluksessa on kolmen luokan käyttäjiä:
* Ylläpitäjä pystyy muokkaamaan turnauksia, osallistujien veikkauksia
* Omistaja omistaa luomansa turnauksen, ja pystyy arvioimaan avoimia kysymyksiä, sekä myös itse osallistumaan veikkauksiin
* Osallistuja pystyy luomaan ja muokkaamaan omat veikkauksensa, sekä näkemään muiden samoissa turnauksissa olevien veikkauksia kyseiseen turnaukseen
