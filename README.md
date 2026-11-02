# Punch your Enemy – spielbare Versionen

Ein alberner Slapstick-Clicker: Fäuste statt Kekse, Beulen statt Blut.
Hau auf Generalissimo Bombastus von Größenwahn – oder auf ein eigenes Bild – und kauf immer absurdere Geräte, die für dich weiterhauen.

**Version 0.7.0** · Deutsch und Englisch · gebaut mit Godot 4.7.1 aus
[Arasax-Games/Punch-your-Enemy](https://github.com/Arasax-Games/Punch-your-Enemy) (Stand `0156886`).

## Herunterladen

| System | Datei | Größe |
|---|---|---|
| Windows 10/11 (64 Bit) | [PunchYourEnemy-0.7.0-Windows.zip](downloads/PunchYourEnemy-0.7.0-Windows.zip) | 39 MB |
| macOS 10.13+ (Intel und Apple Silicon) | [PunchYourEnemy-0.7.0-macOS.zip](downloads/PunchYourEnemy-0.7.0-macOS.zip) | 62 MB |
| Linux (64 Bit) | [PunchYourEnemy-0.7.0-Linux.tar.gz](downloads/PunchYourEnemy-0.7.0-Linux.tar.gz) | 29 MB |

Auf GitHub die Datei anklicken und dann **„Download raw file“** (Pfeil-Symbol rechts) wählen.

## Starten

### Windows
1. ZIP entpacken (Rechtsklick → **Alle extrahieren**).
2. `PunchYourEnemy.exe` doppelklicken.
3. Windows zeigt eventuell **„Der Computer wurde durch Windows geschützt“** – das Spiel ist (noch) nicht signiert.
   Auf **Weitere Informationen → Trotzdem ausführen** klicken.

### macOS
1. ZIP öffnen (Doppelklick) und **Punch your Enemy.app** in den Programme-Ordner ziehen.
2. Beim ersten Start: **Rechtsklick auf die App → Öffnen → Öffnen**.
   Die App ist nicht von Apple beglaubigt, deshalb fragt macOS einmal nach.
   Klappt das nicht: **Systemeinstellungen → Datenschutz & Sicherheit → „Dennoch öffnen“**, oder im Terminal:
   `xattr -dr com.apple.quarantine "/Applications/Punch your Enemy.app"`

### Linux
```bash
tar -xzf PunchYourEnemy-0.7.0-Linux.tar.gz
./PunchYourEnemy.x86_64
```
Benötigt OpenGL 3.3 (jede halbwegs aktuelle Grafikkarte).

## Steuerung

| Eingabe | Wirkung |
|---|---|
| Klick auf das Bild / Leertaste | Hauen |
| R | Wutmodus entfesseln (wenn die Wut-Leiste voll ist) |
| 1–9 | Gerät kaufen |
| Strg+V / Bild ins Fenster ziehen | Neues Opfer (mit Zuschneiden) |
| Goldener Schuh / Silberner Pantoffel | Anklicken für Bonus |

Sprache, Lautstärke und weitere Einstellungen: **Menü** oben rechts.

## Gut zu wissen

- **Spielstand** wird automatisch gespeichert (alle 30 Sekunden und beim Beenden):
  - Windows: `%APPDATA%\PunchYourEnemy`
  - macOS: `~/Library/Application Support/PunchYourEnemy`
  - Linux: `~/.local/share/PunchYourEnemy`
- **Eigene Bilder bleiben auf deinem Rechner** – es wird nichts hochgeladen. Bitte nur Bilder nehmen, bei denen alle Beteiligten Spaß verstehen.
- Diese Versionen laufen **ohne Steam** (keine Steam-Erfolge/Bestenlisten). Die Steam-Fassung folgt über Steamworks.

---

# Punch your Enemy – playable builds (English)

A silly slapstick clicker: fists instead of cookies, bumps instead of blood. Version 0.7.0, German and English (the game follows your system language; switch via **Menu → Sprache / Language**).

- **Windows:** unzip, run `PunchYourEnemy.exe`. If SmartScreen appears: *More info → Run anyway* (the build is not code-signed yet).
- **macOS:** unzip, move the app to Applications, then *right-click → Open → Open* the first time (not notarized).
- **Linux:** `tar -xzf PunchYourEnemy-0.7.0-Linux.tar.gz && ./PunchYourEnemy.x86_64` (OpenGL 3.3).

Your own images never leave your computer. These builds run without Steam.

## Lizenzen / Licenses

Godot Engine (MIT) und alle Bestandteile: [LICENSES.md](LICENSES.md) · Schrift Poppins (SIL OFL 1.1): [OFL-Poppins.txt](OFL-Poppins.txt).
Beide Dateien liegen auch jedem Download bei.
