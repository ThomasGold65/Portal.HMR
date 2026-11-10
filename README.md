# Housing Management – Eigenaarsportaal

Eigenaarsportaal voor de vastgoedportefeuille van Thomas van der Blom: huurgroei, betalingen, onderhoud, contracten en kaart.

- `index.html` bevat een inlogscherm. Het dashboard zelf staat er versleuteld in (AES-256-GCM, sleutel afgeleid van gebruikersnaam en wachtwoord met PBKDF2) en wordt pas na inloggen in de browser ontsleuteld. Het wachtwoord staat nergens in deze repository.
- Gehost via GitHub Pages op https://portal.hmr.goldmarketing.nl (zie `CNAME`).
- DNS: CNAME-record `portal.hmr` → `thomasgold65.github.io` (Strato).
