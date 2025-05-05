# 🚲 Analyse des Radverkehrs in Berlin

Dieses Projekt untersucht Fahrradzähldaten in Berlin mit dem Ziel, Nutzungsmuster, saisonale Schwankungen und Einflussfaktoren wie Wochentage oder Wetterbedingungen zu analysieren.

## 📊 Zielsetzung

- Entwicklung des Fahrradaufkommens über Monate und Jahre
- Vergleich stark und schwach frequentierter Zählstellen
- Identifikation von Einflussfaktoren (z. B. Wochentag, Uhrzeit)

## 🗂️ Datenquelle

➡️ [Fahrradzählstellen Berlin (daten.berlin.de)](https://daten.berlin.de/datensaetze/fahrradz%C3%A4hlstellen-berlin)

## ⚙️ Verwendete Technologien

- Python 3.x
- pandas
- matplotlib
- seaborn
- JupyterLab

## 📁 Projektstruktur

berlin-bike-analysis/ ├── data/ ├── notebooks/ ├── plots/ ├── README.md └── requirements.txt

## 📈 Beispielanalysen

- Monatsverlauf der Fahrradnutzung
- Vergleich Wochentage vs. Wochenende
- Top-Zählstellen

## 🚀 Lokale Ausführung

```bash
git clone https://github.com/dein-nutzername/berlin-bike-analysis.git
cd berlin-bike-analysis
pip install -r requirements.txt
jupyter lab
