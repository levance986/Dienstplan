# Dienstplan Klinik

Statische HTML/JavaScript-App für GitHub Pages.

## Veröffentlichung mit GitHub Pages

1. Neues Repository auf GitHub erstellen, z. B. `dienstplan-klinik`.
2. Die Dateien `index.html` und `README.md` hochladen.
3. In GitHub öffnen:
   - Settings
   - Pages
   - Build and deployment: Deploy from a branch
   - Branch: `main`
   - Folder: `/root`
   - Save
4. Nach 1–2 Minuten ist die App erreichbar unter:
   `https://DEIN-GITHUB-NAME.github.io/dienstplan-klinik/`

## Wichtig

Die App speichert Daten aktuell lokal im Browser über `localStorage`.
Das bedeutet: Daten bleiben auf dem jeweiligen Gerät/Browser.
Für echte Mehrbenutzer-Synchronisation wäre später Firebase oder Supabase nötig.
