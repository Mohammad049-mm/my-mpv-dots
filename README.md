# Meine mpv Konfiguration (input.conf)

Diese Repository enthält meine persönliche Tastaturbelegung (`input.conf`) für den **mpv Media Player**.

## 🚀 Installation

Kopiere die Datei `input.conf` in das Konfigurationsverzeichnis deines Betriebssystems:

| Betriebssystem / Installation | Speicherpfad |
| :--- | :--- |
| **Linux (Flatpak / Flathub)** | `~/.var/app/io.mpv.Mpv/config/mpv/input.conf` |
| **Linux (Standard z.B. Pacman, APT)** | `~/.config/mpv/input.conf` |
| **Windows** | `%APPDATA%\mpv\input.conf` *oder im Ordner `portable_config`* |
| **macOS** | `~/.config/mpv/input.conf` |

### Schnell-Installation über das Terminal (Linux Flatpak)
```bash
mkdir -p ~/.var/app/io.mpv.Mpv/config/mpv/
curl -o ~/.var/app/io.mpv.Mpv/config/mpv/input.conf https://githubusercontent.com
```
*(Ersetze `DEIN-GITHUB-NAME` und `REPOS-NAME` mit deinen echten GitHub-Daten).*

## ⌨️ Wichtigste Tastenkürzel

Hier sind die wichtigsten Änderungen, die ich vorgenommen habe:

| Taste | Aktion | Beschreibung |
| :--- | :--- | :--- |
| **SPACE** | `cycle pause` | Video pausieren / abspielen |
| **RECHTS** | `seek 5` | 5 Sekunden vorspringen |
| **LINKS** | `seek -5` | 5 Sekunden zurückspringen |
| **UP** | `add volume 2` | Lautstärke erhöhen |
| **DOWN** | `add volume -2` | Lautstärke verringern |

*Tipp: Du kannst diese Tabelle in GitHub beliebig erweitern, um all deine eigenen Kürzel aufzulisten.*
