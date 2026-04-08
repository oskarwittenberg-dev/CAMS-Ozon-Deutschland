# CAMS Luftqualitätsvorhersage – Analyse der Ozonkonzentration über Deutschland

Dieses Repository enthält ein Jupyter Notebook zur Analyse von Luftqualitätsvorhersagen des Copernicus Atmosphere Monitoring Service (CAMS) für Deutschland.

Das Notebook bietet einen praxisnahen Einstieg in die Nutzung von CAMS-Daten und zeigt, wie modellbasierte Luftqualitätsinformationen heruntergeladen, verarbeitet und visualisiert werden können.

---

## Inhalt des Notebooks

Am Beispiel der bodennahen Ozonkonzentration (O₃) werden folgende Schritte durchgeführt:

- Download von CAMS-Vorhersagedaten über die ADS API  
- Verarbeitung von NetCDF-Daten mit Python  
- Berechnung von täglichen Mittelwerten und Maximalwerten  
- Erstellung von Karten zur räumlichen Darstellung der Ozonkonzentration  
- Analyse einer Zeitreihe für einen Beispielstandort (Berlin)  

---

## Ziel

Ziel ist es, einen verständlichen und anwendungsnahen Einstieg in die Analyse von Luftqualitätsvorhersagen zu bieten und den Umgang mit Copernicus-Daten zu vermitteln.

---

## Zielgruppe

Das Notebook richtet sich an:

- Studierende und Forschende im Bereich Umwelt, Geographie, Meteorologie oder Datenanalyse  
- Mitarbeitende in Behörden und Institutionen (z. B. Umwelt- oder Gesundheitsbereich)  
- alle Interessierten, die mit Luftqualitätsdaten arbeiten möchten  

---

## Daten

Verwendet wird der Datensatz:

CAMS European Air Quality Forecast  
https://ads.atmosphere.copernicus.eu/datasets/cams-europe-air-quality-forecasts

Die dargestellten Werte basieren auf modellierten Vorhersagen und stellen keine direkten Messungen dar.

---

## Nutzung

Das Notebook kann lokal (z. B. mit Jupyter Notebook) oder online (z. B. mit Google Colab) ausgeführt werden.

Für den Datenzugriff wird ein persönlicher API-Schlüssel für den Atmosphere Data Store (ADS) benötigt.

---

## Erweiterungsmöglichkeiten

Die gezeigte Methodik kann auf weitere Luftschadstoffe übertragen werden, z. B.:

- NO₂ (Stickstoffdioxid)  
- PM10 (Feinstaub)  
- PM2.5  
- SO₂  

---

## Weiterführende Materialien

Auf europäischer Ebene stehen zusätzliche Trainingsmaterialien zur Nutzung von CAMS-Daten zur Verfügung.  
Ein Beispiel ist der ECMWF-Trainingskurs zur regionalen Luftqualitätsvorhersage  
([ECMWF CAMS Training Notebook](https://github.com/ecmwf-training/cams-training/blob/main/cams-regional-forecast.ipynb)).

---

## Hinweis

Dieses Notebook dient als Einführung und Demonstration grundlegender Methoden zur Analyse von CAMS-Daten.
