# 🚲 Berliner Fahrraddiebstahlanalyse

Dieses Projekt analysiert Fahrraddiebstähle in Berlin anhand eines bereitgestellten Diebstahldatensatzes (CSV) sowie eines LOR-Shapefiles (Gebietseinheiten Berlins). Ziel ist es, regionale Schwerpunkte sowie Schadenssummen zu visualisieren und zu kategorisieren.

## 📁 Projektstruktur

berlin-bike-theft-analysis/
├── data/
│   ├── bike_thefts.csv
│   └── shapefiles/
│       ├── BZR_*.shp
│       ├── PLR_*.shp
│       └── PGR_*.shp
├── notebooks/
│   └── 01_bike_theft_analysis.ipynb
├── outputs/
│   └── reports.pdf
├── venv/  # virtuelle Umgebung
├── .gitignore
├── README.md
└── requirements.txt



## 🧪 Funktionalität

- **Einlesen und Bereinigung** der LOR-IDs
- **Gruppierung nach LOR**: Anzahl Diebstähle, Gesamtschaden
- **Berechnung Schaden pro Diebstahl**
- **Kategorisierung** von LORs (hoch/geringes Risiko)
- **Visualisierung** auf Karte mit `geopandas` & `matplotlib`

## 📦 Abhängigkeiten

Siehe `requirements.txt`.

## ▶️ Verwendung

```bash
# 1. Klonen
git clone https://github.com/dein-nutzername/berlin-bike-theft-analysis.git
cd berlin-bike-theft-analysis

# 2. Virtuelle Umgebung (empfohlen)
python -m venv venv
source venv/bin/activate  # oder venv\Scripts\activate unter Windows

# 3. Installiere Pakete
pip install -r requirements.txt

# 4. Starte Notebook
jupyter notebook notebooks/01_bike_theft_analysis.ipynb

## 📍 Hinweis zu den Daten

Die verwendeten Daten unterliegen ggf. Datenschutzrichtlinien. Die Diebstahldaten basieren auf öffentlich zugänglichen Quellen (z. B. Polizeistatistik) und wurden für Analysezwecke aufbereitet.  
Die verwendeten Shapefiles stammen aus dem Berliner LOR-System *(Lebensweltlich orientierte Räume)* und ermöglichen eine räumliche Einordnung auf Stadtteilebene.

## 🧑‍💻 Autor

**Nils Gerdes**  
M.Sc. Biomedizin – Spezialisierung: Genetische Forensik 
