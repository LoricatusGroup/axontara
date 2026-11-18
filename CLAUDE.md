# axontara – útmutató Claude-nak

Egyoldalas statikus weboldal: a teljes oldal a `20260408 axontara website.html` fájl.
A deploy (`.github/workflows/deploy.yml`) ezt `index.html`-ként teszi ki a GitHub
Pagesre; más fájl nem kerül ki.

A felhasználó magyarul ír, válaszolj magyarul.

- Push a `main`-re élesít, ezért ágon dolgozz és PR-t nyiss.
- Ellenőrzés: `python3 -m http.server` a gyökérből, majd Playwrighttal képernyőkép
  asztali és telefonos szélességben.
- Ha a fájlt átnevezed, a `deploy.yml` `cp` sorát is frissíteni kell.
