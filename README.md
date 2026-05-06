# MICRO – Analyse- und Filesystem

## Überblick
Im Rahmen eines Hochschulprojekts wurde für die Lernplattform MICRO ein skalierbares Analyse- und Filesystem entwickelt.

MICRO ermöglicht es Studierenden, eigenen Code direkt auf realer Hardware (Mikrocontrollern) auszuführen, ohne physisch Zugriff auf die Geräte zu benötigen. Die Hardware ist über eine zentralisierte Infrastruktur nahezu rund um die Uhr verfügbar.

Ziel des Projekts war es, sowohl die Verwaltung von Nutzerdateien als auch die Analyse von System- und Nutzungsdaten effizient und skalierbar umzusetzen.

## Features

### Filesystem
- Benutzerbezogener Datei-Explorer (Upload, Download, Ordnerstruktur)
- Versionierung von Dateien (Historie bleibt erhalten, aktive Version sichtbar)
- Prototypische File-Sharing-Funktionalität
- Trennung von Metadaten und Dateiinhalt zur besseren Skalierbarkeit

### Analyse-Dashboard (Admin)
- Visualisierung von Nutzungs- und Systemdaten
- Analysebereiche:
  - Nutzeraktivität
  - Hardware-Stationen
  - Dateinutzung
  - Fehleranalyse
- Dynamische Diagramme mit Zeitraumauswahl
- Unterstützung bei Monitoring und frühzeitiger Fehlererkennung

## Architektur
Die Anwendung wurde mit Fokus auf Skalierbarkeit, Wartbarkeit und klare Systemtrennung entwickelt.

### Technologien
- Frontend: Vue.js
- Backend: Kotlin mit Spring Boot
- Containerisierung: Docker

### Datenhaltung
- PostgreSQL: Speicherung von Datei-Metadaten
- ClickHouse: Analyse großer Mengen an Nutzungsdaten
- Garage S3: Skalierbarer Objektspeicher für Dateien

Durch die Kombination unterschiedlicher Speichersysteme wird eine effiziente Verarbeitung sowohl transaktionaler als auch analytischer Daten ermöglicht.

## Technische Schwerpunkte
- Entwicklung und Design von REST-APIs
- Integration mehrerer spezialisierter Datenbanksysteme
- Verarbeitung und Analyse großer Datenmengen
- Skalierbare Storage-Architektur
- Containerisierte Entwicklungs- und Laufzeitumgebung

## Projektkontext
Dieses Projekt entstand im Rahmen des Moduls Softwaretechnikprojekt an der Technischen Hochschule Mittelhessen.

Die Umsetzung erfolgte durch ein Team von sieben Personen, aufgeteilt in Frontend- und Backend-Entwicklung.

Die entwickelten Funktionen wurden in einer experimentellen Umgebung integriert und evaluiert. Eine mögliche produktive Übernahme in die Plattform liegt in der Entscheidung der Projektverantwortlichen.

## Status
Funktionaler Prototyp mit Fokus auf Architektur, Datenanalyse und Systemdesign.