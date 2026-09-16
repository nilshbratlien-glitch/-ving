# Kornettjakt

Øvingsapp for kornett. Fire blokker: oppvarming, lange toner, fleksibilitet og øve på musikk. Stjerner, rekke, merker og 30 nivåer. Data ligger i nettleseren (`localStorage`).

## Kjør lokalt

Åpne mappa i en enkel server (PWA krever https eller localhost):

```bash
python3 -m http.server 8080
```

Gå til `http://localhost:8080`.

## GitHub Pages

1. Lag et nytt repo og last opp innholdet i denne mappa (ikke en undermappe over).
2. **Settings → Pages → Deploy from a branch → `main` / `/ (root)`**.
3. Appen ligger på `https://<bruker>.github.io/<repo>/`.
4. På telefon: åpne den adressen i Safari (iPhone) eller Chrome (Android) → **Del / Installer / Legg til på Hjem-skjerm**.

Hvis repoet heter noe annet enn rot-domenet, fungerer `start_url` og `scope` som `./` og tåler undermappa.

## Installere som app

- **iPhone:** Safari → Del → Legg til på Hjem-skjerm.
- **Android:** Chrome → meny → Installer app / Legg til på startskjermen.

Etter installasjon åpnes Kornettjakt uten nettleser-chrome. Øving virker også offline når den først er lastet.

## Personvern

Ingen konto. Ingen server. Økter, stjerner og nivå ligger bare på enheten.
