# Schilfrohr Beratung – Homepage

Statische Ein-Seiten-Website für Schilfrohr Beratung, gehostet via GitHub Pages.

## Lokal ansehen

Einfach `index.html` im Browser öffnen, oder z.B.:

```bash
python3 -m http.server 8000
```

und dann `http://localhost:8000` öffnen.

## Deployment

Wird automatisch über GitHub Pages aus dem `main`-Branch veröffentlicht.

## TODO vor dem Live-Gang

- [ ] Markenname final klären (DPMA-Check, Domain-Verfügbarkeit)
- [ ] Echte Kontakt-E-Mail-Adresse in `index.html` eintragen
- [x] Impressum & Datenschutzerklärung als Template angelegt (`impressum.html`, `datenschutz.html`)
- [ ] **Alle `[PLATZHALTER]` in `impressum.html` und `datenschutz.html` ausfüllen**
      (Name, Anschrift, ggf. Berufsbezeichnung/Kammer, Berufshaftpflicht)
- [ ] Impressum & Datenschutz von einer Rechtsanwältin/einem Rechtsanwalt oder
      Steuerberatung prüfen lassen, insbesondere wegen späterer Verarbeitung
      von Gesundheitsdaten (Art. 9 DSGVO) in der Beratungstätigkeit
- [ ] Eigene Domain verbinden (optional, in GitHub Pages Settings → Custom domain)
- [ ] Favicon/Logo ergänzen
