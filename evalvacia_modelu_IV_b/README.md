# Evalvácia modelu IV b)

Porovnajte pravdepodobnosti pre zamestnancov pomocou Wilcoxonovho párového testu.

Pomocou STATISTICA: Statistics -> Nonparametrics -> Comparing two dependent variables -> Wilcoxon matched pairs test

Príkazy v Pythone vhodné pre riešenie tohto zadania:

```
import pandas as pd
pd.read_csv() - načítanie log súboru
from scipy import stats - statistika
stats.wilcoxon() - Wilcoxonov parovy test
```
