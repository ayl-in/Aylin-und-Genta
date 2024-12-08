# Todesfälle bei Kindern aufgrund von Krankheiten, die durch invasive Pneumokokken verursacht werden, weltweit
Semesterprojekt Python

Gruppe: Aylin Ago, Genta Arifi

Fragen:

- Wie haben sich die Todesfälle durch Pneumokokken-bedingte Pneumonie, Meningitis und andere invasive Krankheiten weltweit zwischen 2000 und 2015 verändert?
- Welcher prozentuale Anteil der Todesfälle durch invasive Pneumokokken-Erkrankungen entfiel im Jahr 2000 und 2015 jeweils auf Pneumonie, Meningitis und andere Krankheiten?
- In welchem Jahr wurde der grösste Rückgang bei den Todesfällen durch Pneunokokken-bedingte Krankheiten weltweit beobachtet?

Quellen

- https://ourworldindata.org/pneumonia


# 1. Daten beschaffen und laden

import pandas as pd
from matplotlib import pyplot as plt

# loading the data
df = pd.read_csv('child-deaths-from-streptococcus-by-disease_data.csv', skiprows=1,['Jahr', 'Anzahl Betroffene', 'Krankheiten'])
df.head()


