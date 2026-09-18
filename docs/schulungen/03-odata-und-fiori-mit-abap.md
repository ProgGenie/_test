# Schulung 3: OData und Fiori-Integration mit ABAP

## Ziel der Einheit
ABAP-Entwickler verstehen, wie SAPUI5-Anwendungen mit ABAP-Services verbunden werden, und können den Weg von Backend-Daten bis zur Anzeige in einer Fiori-App nachvollziehen.

## Dauer
Ca. 60 Minuten

## Zielgruppe
ABAP-Entwickler mit ersten SAPUI5-Grundlagen, die den Backend-Bezug vertiefen möchten.

## Lernziele
- Die Rolle eines OData-Services in einer Fiori-Anwendung erklären können
- Die Verbindung zwischen SAPUI5-Modell und ABAP-Service verstehen
- Typische Schritte bei der Bereitstellung von Daten aus ABAP benennen können
- Häufige Fehlerbilder bei der Integration einordnen können

## Voraussetzungen
- Inhalte aus Schulung 1 und 2
- Grundkenntnisse zu ABAP Dictionary, CDS oder klassischen Backend-Datenquellen

## Agenda
### 1. Rückblick und Einordnung (5 Minuten)
- Wiederholung von MVC und Datenbindung
- Warum OData für Fiori zentral ist

### 2. OData-Grundlagen für ABAP-Entwickler (15 Minuten)
- Entitäten und Entitätsmengen
- Lesen, Filtern und Navigieren
- Service-Metadaten
- Unterschied zwischen Test im Backend und Nutzung im Frontend

### 3. Einbindung in SAPUI5 (15 Minuten)
- ODataModel in der Anwendung
- Service-Definition in `manifest.json`
- Binding gegen Backend-Daten
- Laden und Aktualisieren von Daten

### 4. End-to-End-Betrachtung (15 Minuten)
- Datenquelle im Backend
- Bereitstellung als Service
- Konsum im Frontend
- Typische Verantwortlichkeiten zwischen ABAP- und UI-Entwicklung

### 5. Fehleranalyse und Best Practices (10 Minuten)
- Metadaten laden nicht
- Binding zeigt keine Daten
- Berechtigungen und Service-Aktivierung
- Saubere Trennung von Fachlogik und UI-Logik

## Praktischer Teil
Geführte Analyse einer Beispielanwendung:
- OData-Service in der Konfiguration finden
- Zuordnung zwischen UI-Feld und Backend-Attribut nachvollziehen
- Einen einfachen Listen- oder Detailscreen fachlich durchgehen

## Ergebnis der Einheit
Die Teilnehmer verstehen den Integrationspfad zwischen ABAP-Backend und Fiori-Oberfläche und können bei der Umsetzung oder Fehlersuche gezielter mitarbeiten.

## Hausaufgabe oder Transfer
- Einen bestehenden OData-Service aus dem eigenen Umfeld auswählen
- Beschreiben, welche Daten davon in einer Fiori-App sinnvoll dargestellt würden
