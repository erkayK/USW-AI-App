# USW-AI-App

**📈 Social Media Sentiment & Aktienkurse**
Analyse des Zusammenhangs zwischen Twitter-Stimmung und Aktienkursbewegungen

📌 Projektübersicht
Das Ziel dieses Projekts ist es zu untersuchen, ob und wie sich die Stimmung in sozialen Medien (insbesondere auf Twitter) auf die Aktienkurse großer Unternehmen auswirkt.
Dazu werden Tweets analysiert, Sentiment-Scores berechnet und mit Aktienkursen zwischen 2015-2020 verglichen.

-------------------------------------------------------------
Fragestellungen:
Gibt es eine Korrelation zwischen Sentiment und Aktienkurs?
Kann Sentiment zur Vorhersage von Kursen genutzt werden?

**Bibliotheken:**

- pandas, numpy → Datenaufbereitung
- matplotlib, seaborn → Visualisierung
- scikit-learn → Modellierung (Regression, GridSearch)
- nltk, vaderSentiment, afinn → Sentiment-Analyse

📊 Datenquellen
https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020
https://www.kaggle.com/datasets/omermetinn/values-of-top-nasdaq-copanies-from-2010-to-2020

**📑 Schritte der Analyse**
- ✅ 1. Data Understanding (Import der CSV-Dateien (Tweets, Unternehmen, Aktienkurse).
- ✅ 2. Data Preparation (Aggregation,Merge)
- ✅ 3. Analyse & Visualisierung (Histogramme, Scatterplots, Korrelationsmatrix )
- ✅ 4. Modellierung (Lineare Regression & RandomForest)
- ✅ 5. Hypothesenprüfung --> R²-Werte