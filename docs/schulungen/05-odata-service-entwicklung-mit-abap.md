# Schulung 5: OData-Service-Entwicklung mit ABAP

## Ziel der Einheit
ABAP-Entwickler lernen die wesentlichen Schritte zur Entwicklung eines OData-Services kennen und verstehen, wie Backend-Daten für Konsumenten bereitgestellt werden.

## Dauer
Ca. 60 Minuten

## Zielgruppe
ABAP-Entwickler, die erste OData-Grundlagen kennen und selbst Services entwickeln oder erweitern sollen.

## Lernziele
- Die typischen Entwicklungsschritte eines OData-Services in ABAP benennen können
- Die Aufgaben von Modell- und Service-Implementierung unterscheiden können
- Datenbereitstellung für Lesezugriffe fachlich und technisch nachvollziehen können
- Typische Erweiterungspunkte in der Service-Implementierung kennen

## Voraussetzungen
- Inhalte aus Schulung 4
- Kenntnisse zu internen Tabellen, Strukturen und Selektionslogik in ABAP

## Agenda
### 1. Rückblick und Zielbild (5 Minuten)
- Wiederholung der OData-Grundbegriffe
- Einordnung der heutigen Entwicklungsaufgaben

### 2. Aufbau eines OData-Services (15 Minuten)
- Service-Modell und Entitäten
- Entity Sets und Assoziationen
- Service-Registrierung und Aktivierung
- Trennung zwischen Modell und Implementierung

### 3. Implementierung in ABAP (20 Minuten)
- Leselogik für eine Entitätsmenge
- Einzelzugriff auf eine Entität
- Mapping zwischen Backend-Struktur und Servicemodell
- Umgang mit Selektionsparametern

### 4. Test und erste Qualitätssicherung (10 Minuten)
- Service-Aufruf in Testwerkzeugen
- Prüfung der Metadaten
- Validierung von Filtern und Ergebnismengen

### 5. Abschluss und Fragen (10 Minuten)
- Typische Fehler in der Service-Entwicklung
- Hinweise zur sauberen Strukturierung der Implementierung

## Praktischer Teil
Geführtes Durchgehen eines Beispielservices:
- Entität definieren
- Lesemethode fachlich besprechen
- Ergebnisstruktur mit Backend-Daten verbinden
- Service registrieren und testen

## Ergebnis der Einheit
Die Teilnehmer verstehen den grundlegenden Entwicklungsablauf eines OData-Services in ABAP und können bestehende Implementierungen gezielt lesen oder vorbereiten.

## Hausaufgabe oder Transfer
- Für ein eigenes Geschäftsobjekt überlegen, welche Entitäten und Felder als OData-Service sinnvoll wären
- Die benötigten Backend-Datenquellen identifizieren
