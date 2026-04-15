# CLAUDE.md — github_alexanderschoenfeld

## Was dieses Repo ist

Dies ist das **GitHub Profile README** für den Account `alexanderschoenfeld`.
Die einzige Datei ist `README.md` — sie wird automatisch als Profilseite auf
`https://github.com/alexanderschoenfeld` angezeigt.

## Git & SSH

Dieser Account verwendet einen SSH-Alias. Remote-URL muss immer so aussehen:

```
git@github-alex:alexanderschoenfeld/<repo-name>.git
```

**Nicht** `git@github.com:...` verwenden — der Alias `github-alex` ist nötig,
damit der richtige SSH-Key (`id_rsa_alex`) verwendet wird.

SSH-Config liegt unter: `C:/Users/AlexanderSchönfeld/.ssh/config`

Verbindung testen: `ssh -T git@github-alex` → sollte sagen: *Hi alexanderschoenfeld!*

## Pushen

```bash
git add README.md
git commit -m "..."
git push
```

Remote ist bereits gesetzt (`origin = git@github-alex:alexanderschoenfeld/alexanderschoenfeld.git`).

## README-Struktur

Die `README.md` ist auf Deutsch und enthält:
- Kurzbio & Standort
- Beratungsschwerpunkte (KI, Azure, Microsoft 365)
- Tabelle mit aktuellen Projekten (Branchen + Stack)
- Badge-Stack (Cloud & AI / Development / Plattform & Tools)
- Kundenliste
- Zertifizierungen
- Sprachkenntnisse
- GitHub Stats Cards
- Kontaktzeile

## GitHub Stats Cards

Alle drei Cards (Stats, Top Languages, Streak) verwenden `<picture>` mit
`prefers-color-scheme` für automatisches Dark/Light-Mode-Switching:

- **Dark:** `theme=dark&bg_color=0d1117`
- **Light:** `theme=default`

Dienste:
- Stats & Languages: `github-readme-stats.vercel.app`
- Streak: `streak-stats.demolab.com`

Bei Änderungen an den Cards immer beide Varianten (dark + light) anpassen.
