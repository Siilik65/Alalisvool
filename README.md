# Alalisvoolu kordamine

See on staatiline veebileht: veebis avaldamiseks ei ole Pythonit vaja.

## Muutmine

- Kogu lehe tekst, kujundus ja JavaScript on failis `index.html`.
- Pildid ja skeemid peavad jääma samasse kausta; failinimede muutmisel uuenda viiteid ka `index.html` failis.
- GitHubis saad `index.html` avada ja valida faili muutmise. Otsi soovitud tekst `Ctrl+f` abil ning salvesta muudatus commit'ina. Pane tähele, et samas failis on ka HTML, CSS ja JavaScript.
- Kohalikuks eelvaateks ava terminal selles kaustas ja käivita `python -m http.server 8000`. Seejärel ava `http://localhost:8000`.

## GitHub Pagesi avaldamine

1. Repositooriumis ava **Settings → Pages**.
2. Vali **Deploy from a branch**, haruks `main` ja kaustaks `/ (root)`, seejärel salvesta.
3. GitHub Pages avaldab lehe antud aadressil. Iga `main` harus salvestatud muudatus avaldatakse automaatselt.
4. Oma domeeni lisamiseks sisesta see samal Pagesi lehel väljale **Custom domain** ning lisa domeenihalduris GitHubi kuvatud DNS-kirjed. Vaata [GitHubi domeenijuhendit](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

Kõik lehe failid, sealhulgas `index.html` ja pildid, peavad paiknema repositooriumi juurkaustas.
