# Workforce Analytics

Ein ausführbares Notebook von Simon Josef Cebula zur Klassifikation mit
asymmetrischen Fehlerkosten. Es baut auf einer Machine-Learning-Prüfungsarbeit
auf. Für diese Portfoliofassung wurde die Auswertung mit synthetischen Daten
neu umgesetzt.

Das Notebook vergleicht logistische Regression, Entscheidungsbaum und Gradient
Boosting. Es wählt auf dem Validierungssatz einen Schwellenwert und stellt ihn
auf dem zurückgehaltenen Testsatz der Standardregel gegenüber. Alle Daten
entstehen deterministisch im Notebook.

## Lokal ausführen

Mit Python 3.11 oder neuer:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab workforce-analytics.ipynb
```

In Jupyter alle Zellen in Reihenfolge ausführen.
