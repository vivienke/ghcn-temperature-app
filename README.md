# Installationsanleitung

Dieses Projekt besteht aus einem Backend (API) und einem Frontend. Beide werden mit Docker ausgeführt.

## Voraussetzungen
- Docker muss installiert sein. Falls nicht, lade es von [docker.com](https://www.docker.com/) herunter und installiere es.

## Installation und Start
1. Öffne ein Terminal (PowerShell oder Command Prompt).
2. Navigiere zum Projektordner
3. Führe den Befehl aus: `docker-compose up --build`

Das baut die Images und startet die Services. Die API läuft auf http://localhost:8000 und das Frontend auf http://localhost:8080.

## Stoppen
Drücke Ctrl+C im Terminal, um die Services zu stoppen.

## Hinweise
- Beim ersten Start kann es etwas dauern, da die Images gebaut werden.
- Stelle sicher, dass die Ports 8000 und 8080 frei sind.