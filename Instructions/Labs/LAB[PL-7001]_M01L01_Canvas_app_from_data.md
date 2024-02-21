---
lab:
  title: 'Lab 1: Erstellen einer Canvas-App aus Daten'
  module: 'Module 1: Get started with Power Apps canvas apps'
---

# Übungslab 1: Erstellen einer Canvas-App aus Daten

In diesem Lab entwerfen und erstellen Sie eine Canvas-App aus einer vorhandenen Datenquelle.

## Lernziele

- Erstellen von Power Apps-Canvas-Apps aus Daten und mit Copilot
- Verknüpfen mit Excel als Datenquelle mithilfe von OneDrive for Business

## Weiterführende Schritte des Lab

- Erstellen einer Canvas-App mit drei Bildschirmen
- Testen der App
- Erstellen einer Canvas-App mit Copilot
  
## Voraussetzungen

- Sie müssen **Lab 0: Labumgebung überprüfen** abgeschlossen haben.

## Ausführliche Schritte

## Übung 1: Abrufen der Daten

### Aufgabe 1.1: Herunterladen des Excel-Arbeitsblatts

1. Navigieren Sie zu [CoffeeMachineData.xlsx](https://github.com/MicrosoftDocs/mslearn-developer-tools-power-platform/blob/master/power-apps/coffee-machine-data/CoffeeMachineData.xlsx).

1. Wählen Sie die Schaltfläche **Rohdatendatei** aus, um die Excel-Arbeitsmappe herunterzuladen.

    ![Screenshot des Downloadsymbols für Rohdatendateien in GitHub](../media/raw-download.png)

### Aufgabe 1.2: Hochladen in OneDrive for Business

1. Wählen Sie im [Power Apps Maker-Portal](https://make.powerapps.com) das **App-Startfeld** oben links im Browserfenster und dann **OneDrive** aus.

    ![Screenshot des OneDrive-Symbols](../media/select-onedrive.png)

1. Wählen Sie **Ihr OneDrive ist bereit** aus.

1. Wählen Sie **+ Neu hinzufügen** und dann **Dateien hochladen** aus.

    ![Screenshot des OneDrive-Dateiuploads](../media/select-onedrive-upload.png)

1. Navigieren Sie zu „Downloads“, und wählen Sie die Datei „CoffeeMachineData.xlsx“ und dann **Öffnen** aus.

1. Wählen Sie **Meine Dateien** aus, und überprüfen Sie, ob „CoffeeMachineData.xlsx“ hochgeladen wurde.

## Übung 2: Erstellen einer Canvas-App mit drei Bildschirmen

### Aufgabe 2.1: Erstellen der App

1. Navigieren Sie zum Power Apps Maker-Portal unter <https://make.powerapps.com>.

1. Vergewissern Sie sich, dass Sie sich in der Umgebung **Dev One** befinden.

1. Wählen Sie im linken Menü die Registerkarte **+ Erstellen** aus.

1. Wählen Sie die Kachel **Excel** unter **Starten mit** aus.

    ![Screenshot von „Mit Excel starten“](../media/start-from-excel.png)

1. Wählen Sie **+ Neue Verbindung** aus.

1. Wählen Sie **OneDrive for Business** und dann **Erstellen** aus, melden Sie sich mit Ihren Mandantenanmeldeinformationen an, und wählen Sie **Zugriff zulassen** aus.

1. Suchen Sie unter „Excel-Datei auswählen“ die Excel-Datei **CoffeeMachineData.xlsx**, und wählen Sie sie aus.

1. Wählen Sie unter „Tabelle auswählen“ den Eintrag **CoffeeMachines** aus.

1. Wählen Sie **Verbinden** aus.

1. Warten Sie, bis die App erstellt wurde.

    ![Screenshot des Bildschirms „Durchsuchen“ in einer App mit drei Bildschirmen](../media/three-screen-app-browse-screen.png)

1. Wählen Sie **Speichern** oben rechts in Power Apps Studio aus, geben Sie `Coffee Machines App` ein, und wählen Sie erneut **Speichern** aus.

### Aufgabe 2.2: Testen der App

1. Wählen Sie oben rechts in Power Apps Studio das Symbol **App-Vorschau** aus.

1. Wählen Sie eine beliebige Maschine im Katalog aus. Dadurch gelangen Sie zum Detailbildschirm.

1. Wählen Sie oben rechts in der App das Symbol **Bearbeiten** aus. Dadurch wird der Bildschirm „Bearbeiten“ geöffnet.

1. Ändern Sie den **Maschinenpreis**, und wählen Sie oben rechts in der App das Symbol **Übermitteln** aus.

1. Wählen Sie oben links in der App das Symbol **<** aus.

1. Wählen Sie oben rechts in der App das Symbol **+** aus.

1. Geben Sie `97` als **Maschinen-ID** ein.

1. Geben Sie `Demo Machine` als **Maschinenname** ein.

1. Geben Sie `999` als **Maschinenpreis** ein.

1. Wählen Sie oben rechts in der App das Symbol **Übermitteln** aus.

1. Geben Sie `Demo` unter **Elemente durchsuchen** ein.

1. Wählen Sie das **X** in der oberen rechten Ecke aus, um die Vorschau zu beenden.

1. Wählen Sie oben links in der Befehlsleiste die Schaltfläche **<- Zurück** und dann **Verlassen** aus, um die App zu beenden.

1. Wählen Sie im linken Menü des Power Apps Maker-Portals die Registerkarte **+ Erstellen** aus.

## Übung 3: Erstellen einer Canvas-App mit Copilot

### Aufgabe 3.1: Erstellen der App

1. Navigieren Sie zum Power Apps Maker-Portal unter <https://make.powerapps.com>.

1. Vergewissern Sie sich, dass Sie sich in der Umgebung **Dev One** befinden.

1. Wählen Sie im linken Menü die Registerkarte **Home** aus.

1. Geben Sie unter **App erstellen – Was soll sie können?** den Text `Track coffee machine repairs for customers and assign repairs to technicians` ein, und wählen Sie das Pfeilsymbol aus.

    ![Screenshot des Copilot-Prompts](../media/copilot-prompt.png)

1. Überprüfen der Tabelle

    ![Screenshot der Copilot-Tabelle](../media/copilot-table.png)

1. Wählen Sie **App erstellen** aus.

1. Warten Sie, bis die App erstellt wurde.

    ![Screenshot der App von Copilot](../media/copilot-app.png)

1. Wählen Sie **Speichern** oben rechts in Power Apps Studio aus, geben Sie `Coffee Repair App` ein, und wählen Sie erneut **Speichern** aus.

1. Wählen Sie oben links in der Befehlsleiste die Schaltfläche **<- Zurück** und dann **Verlassen** aus, um die App zu beenden.

1. Wählen Sie im linken Menü des Power Apps Maker-Portals die Registerkarte **Apps** aus.
