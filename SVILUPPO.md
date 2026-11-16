# SVILUPPO - surgelati (istruzioni da sviluppare)

Repo creata il 16/11/2026 dal template mistraltemplate1. Leggi prima CLAUDE.md e docs/CLONAZIONE.md.

## Obiettivo
Sito sui prodotti surgelati: catalogo, catena di produzione e catena del freddo (dal produttore al cliente), contenuti informativi. Brief originale di Mirco: "prodotti surgelate, catena di costruzione ecc." (da chiarire con lui se "catena di costruzione" = filiera di produzione o altro).

## Da fare, in ordine (commit unico alla fine)
1. Chiarire con Mirco: B2B (ristorazione) o B2C? Shop vero o vetrina? Consegna a domicilio?
2. Menu e categorie IT+EN (esempi: Carne, Pesce, Verdure, Piatti pronti, Dolci e gelati).
3. Home e Chi siamo IT+EN con testi veri, via i segnaposto (Servizi, prodotto-esempio, categoria-esempio).
4. Pagina "La filiera": produzione, lavorazione, abbattimento, stoccaggio, trasporto a temperatura controllata, consegna.
5. Pagina "Catena del freddo": temperature, conservazione a casa, scongelamento. Solo da fonti ufficiali (Ministero della Salute, EFSA), mai scrivere a caso.
6. Catalogo in _data/catalogo.json (prezzi in centesimi), una pagina per prodotto in _negozio/.
7. Palette: ghiaccio e azzurro (il default teal del template va gia' bene); eventualmente personalizza_clone.py.
8. whatsapp ed email in _config.yml (ora vuoti).
9. Articoli blog (1 per volta, con fonti): come si surgela, durata di conservazione, norme etichettatura.
10. Verifica con automation\controllo.ps1 (TUTTO OK), poi un solo push con ..\pubblica.ps1.

## Stato
- Repo online: https://github.com/cialdecompatibili-netizen/surgelati
- Sito: https://cialdecompatibili-netizen.github.io/surgelati/ (admin: /admin/)
- Stato attuale: clone grezzo, ancora tutto segnaposto.
