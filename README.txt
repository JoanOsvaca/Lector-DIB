LECTOR DIB BOVÍ — PROTOTIP INICIAL

Fitxers:
- index.html: aplicació web d'una sola pàgina.

Funcions:
- Càmera del mòbil amb càmera posterior preferida.
- OCR periòdic en directe.
- Extracció aproximada del número FR... i la data.
- Afegeix automàticament quan detecta dues lectures estables.
- Evita duplicats pel número d'identificació.
- Edició manual, eliminació de files, ordenació pels últims quatre números.
- Exportació CSV compatible amb Excel, còpia JSON i importació CSV.

IMPORTANT:
- És un prototip; cal provar-lo amb DIB reals i ajustar l'OCR. Revisa les dades abans d'utilitzar-les.
- Necessita connexió a internet per carregar Tesseract.js i els models OCR.
- Per accedir a la càmera des del mòbil, publica'l en un allotjament HTTPS (per exemple, Render Static Site o GitHub Pages).
- Les dades es mantenen només en memòria mentre la pàgina està oberta; exporta el CSV/JSON abans de tancar-la.
- Encara no hi ha base de dades compartida ni accés d'usuaris.
