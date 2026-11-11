# Daengs-Updates

Hier liegen nur die Update-Dateien für Daengs: `latest.json` und das Update-Setup ohne Modelle.
Daengs prüft höchstens einmal am Tag über sein eigenes Update-Programm, ob es eine neue Fassung gibt,
und installiert sie nur nach einem Klick.

- `latest.json` ist mit Ed25519 signiert; das Update-Programm nimmt nur Dateien an, deren Signatur zu einem
  in Daengs eingebauten Schlüssel passt, deren SHA-256 stimmt und deren Version höher ist als die installierte.
- Hier liegen keine Kundendaten und keine Projekte.
