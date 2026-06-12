# JobMatch ML Project

Projekt grupor ne Machine Learning — parashikimi i vendimeve te punesimit.

## Anetaret e grupit
- Ardian Asani
- Blend Fetahu

## Dataset
Predicting Hiring Decisions in Recruitment Data (Kaggle):
https://www.kaggle.com/datasets/rabieelkharoua/predicting-hiring-decisions-in-recruitment-data

## Struktura
- `data/` — dataseti (CSV)
- `notebooks/` — Jupyter notebook me gjithe analizen
- `report/` — raporti final

## Si te ekzekutohet
# JobMatch ML Project

Projekt grupor ne Machine Learning — parashikimi i vendimeve te punesimit.

## Anetaret e grupit
- Ardian Asani
- Blend Fetahu

## Dataset
Predicting Hiring Decisions in Recruitment Data (Kaggle):
https://www.kaggle.com/datasets/rabieelkharoua/predicting-hiring-decisions-in-recruitment-data

## Struktura
- `data/` — dataseti (CSV)
- `notebooks/` — Jupyter notebook me gjithe analizen
- `report/` — raporti final

## Si te ekzekutohet

**Parakushtet:** Python 3.11+ me Jupyter (rekomandohet [Anaconda](https://www.anaconda.com/download)) dhe Git.

1. Klononi repon dhe hyni ne te:
```bash
   git clone https://github.com/ArdianAsani/jobmatch-ml.git
   cd jobmatch-ml
```

2. Instaloni varesite:
```bash
   pip install -r requirements.txt
```

3. Hapni notebook-un:
```bash
   jupyter notebook notebooks/jobmatch_ml.ipynb
```
   (ose hapeni ne VS Code dhe zgjidhni kernel-in perkates te Python-it)

4. Ekzekutoni te gjitha qelizat me radhe: **Kernel → Restart & Run All**.

**Shenim:** Dataseti ndodhet ne `data/` dhe ngarkohet me rruge relative nga notebook-u, prandaj nuk nevojitet asnje konfigurim shtese — mjafton qe notebook-u te ekzekutohet nga vendndodhja e tij ne `notebooks/`. Ekzekutimi i plote mund të zgjas per shkak te kerkimit te hiperparametrave (GridSearchCV).