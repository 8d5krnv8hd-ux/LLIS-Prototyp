# LLIS Webseite v4 — Wireframe-Prototyp

Klickbarer Low-Fidelity-Prototyp aller 28 Seiten der neuen Sitemap (plus 4
Bereichs-Übersichten und 1 Platzhalter), zum gemeinsamen Durchklicken und
Testen der Struktur/Navigation. Inhalte sind bewusst nur als Platzhalter
("Wireframe") dargestellt — es geht um Aufbau, Navigation und
Seitenstruktur, nicht um Design oder Texte.

## Veröffentlichung mit GitHub Pages

1. Neues Repository auf GitHub anlegen (z. B. `llis-prototyp-v4`).
2. Den Inhalt dieses Ordners (alle `.html`-Dateien + `styles.css`) in das
   Repository hochladen (per Drag & Drop im Browser oder `git push`).
3. Im Repository unter **Settings → Pages**:
   - "Source" auf **Deploy from a branch** stellen
   - Branch **main**, Ordner **/ (root)** auswählen, speichern
4. Nach 1–2 Minuten ist der Prototyp unter
   `https://<benutzername>.github.io/<repository-name>/` erreichbar.

Die Startseite ist `index.html` — alle internen Links sind relative Pfade,
die Navigation funktioniert also direkt nach dem Upload.

## Struktur

- `index.html` — Homepage (4-Zonen Community-Hub)
- `schulangebot.html`, `schulleben.html`, `eltern.html`, `team.html`,
  `interessiert.html`, `schueler.html` — Bereichs-Übersichten (Hubs), über
  die Hauptnavigation erreichbar
- alle übrigen Dateien — die 27 weiteren Einzelseiten aus der Sitemap,
  benannt nach ihrem Pfad (z. B. `angebot-primary-nursery.html` =
  `llis.lu/angebot/primary/nursery`)
- `styles.css` — gemeinsames Stylesheet für alle Seiten

## Seitenübersicht (28 Sitemap-Seiten)

| Seite | Pfad | Datei |
|---|---|---|
| Homepage | llis.lu | index.html |
| Profil der Schule | llis.lu/ueber | ueber.html |
| Kontakt & Standort | llis.lu/kontakt | kontakt.html |
| Nursery | llis.lu/angebot/primary/nursery | angebot-primary-nursery.html |
| Primary | llis.lu/angebot/primary | angebot-primary.html |
| Maison Relais | llis.lu/angebot/primary/maison-relais | angebot-primary-maison-relais.html |
| ESE | llis.lu/angebot/ese | angebot-ese.html |
| VP – Voie de Préparation | llis.lu/angebot/vp | angebot-vp.html |
| FP – Formation Professionnelle | llis.lu/angebot/fp | angebot-fp.html |
| News & Ankündigungen | llis.lu/schulleben/news | schulleben-news.html |
| Veranstaltungen | llis.lu/schulleben/veranstaltungen | schulleben-veranstaltungen.html |
| Schulprojekte | llis.lu/schulleben/projekte | schulleben-projekte.html |
| Komitees & Gremien | llis.lu/schulleben/komitees | schulleben-komitees.html |
| Newsletter-Archiv | llis.lu/schulleben/newsletter | schulleben-newsletter.html |
| Activités Parascolaires | llis.lu/schulleben/parascolaire | schulleben-parascolaire.html |
| Schulkalender | llis.lu/eltern/kalender | eltern-kalender.html |
| Absenzen melden | llis.lu/eltern/absenzen | eltern-absenzen.html |
| Dokumente & Formulare | llis.lu/eltern/dokumente | eltern-dokumente.html |
| Praktisches | llis.lu/eltern/praktisches | eltern-praktisches.html |
| Publikationen | llis.lu/eltern/publikationen | eltern-publikationen.html |
| Neu bei LLIS? | llis.lu/interessiert | interessiert.html |
| Einschreibung | llis.lu/interessiert/einschreibung | interessiert-einschreibung.html |
| Tag der offenen Tür | llis.lu/interessiert/open-day | interessiert-open-day.html |
| Schulbesuch vereinbaren | llis.lu/interessiert/schulbesuch | interessiert-schulbesuch.html |
| Direction | llis.lu/team/direction | team-direction.html |
| Enseignants & Services | llis.lu/team/enseignants | team-enseignants.html |
| Arbeiten bei LLIS | llis.lu/team/arbeiten | team-arbeiten.html |
| Offene Stellen | llis.lu/team/stellen | team-stellen.html |

## Hinweise

- Jede Seite zeigt oben den Status (Vorhanden / Neu / Priorität) und die
  Zielgruppe — direkt aus der Sitemap übernommen.
- Unten auf jeder Seite verlinken "Weitere Seiten in diesem Bereich" zu den
  Schwester-Seiten desselben Sitemap-Abschnitts.
- "Für Schüler" ist als Platzhalter angelegt — Inhalte für diesen Bereich
  sind in der Sitemap noch offen.
- Der Prototyp ist bewusst generisch gehalten (Platzhalter-Blöcke statt
  echter Inhalte), damit der Fokus auf Struktur und Klickpfaden liegt.
