# Veikala meklētājs

## Apraksts
Ievadot (vai noskaidrojot) izpildītdatora atrašanās vieto, izvada sarakstu ar 5 tuvākajiem veikaliem. 
## Galvenās funkcijas
- Ievadīt/Noskaidrot lietotāja atrašanās vietu.
- Izmantot API vai tā lokālu kopiju lai dabūtu veikalu atrašanās vietas.
  - OpenStreetMap aptuvens rīgas rajons https://overpass-api.de/api/map?bbox=24.0340,56.9320,24.1687,56.9741
  - Atgriež XML formātu, būs nepieciešams to apstrādāt.
    - Vairākas opcijas, [TinyXML2](https://github.com/leethomason/tinyxml2) izklausas labs.
    - Veikalu koordinātes iespējams nepieciešams saglabāt lai nav atkātroti jāapstrādā fails.
- Sakārtot tās pēc attāluma no lietotāja
- Izvadīt ~5 tuvākos veikalus
## Izmantotās tehnoloģijas
- C++
- SFML library
## Izmantotie avoti
- [SFML dokumentācija](https://www.sfml-dev.org/style.php)
