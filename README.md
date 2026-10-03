<a id="top"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-06-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-06-light.svg">
  <img alt="Projekt 06 — Klasteryzacja — segmentacja obrazu i analiza skupień" src="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-06-light.svg" width="100%">
</picture>

<br>

[**← Wszystkie projekty**](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;·&nbsp; [Notatnik](./Twardawa_Filip_ML.ipynb) &nbsp;·&nbsp; [Raport PDF](./Twardawa_Filip_ML.pdf)

<br>

## Uczenie nienadzorowane i klasteryzacja

### Cel

Celem ćwiczenia jest segmentacja obrazu z użyciem algorytmu k-średnich oraz analiza zbioru danych z wykorzystaniem algorytmów klasteryzacji. Zadanie pierwsze polega na segmentacji obrazu według kolorów, a zadanie drugie — na analizie zbioru iris.csv różnymi metodami klasteryzacji w celu odkrycia ukrytych wzorców.

### Zbiór danych

**a) palm_tree.jpg** — obraz przedstawiający sylwetki palm na tle nieba i wybrzeża.

**b) iris.csv** — zbiór dotyczący trzech gatunków irysów, opisanych długością i szerokością płatków oraz działek kielicha.

### Metody

**A · Algorytm k-średnich**<br>
Grupuje dane w zadaną liczbę skupień, przypisując każdy punkt do najbliższego centroidu. W pierwszym zadaniu punktami są piksele obrazu w przestrzeni kolorów RGB.

**B · Klasteryzacja aglomeracyjna**<br>
Metoda hierarchiczna, która łączy najbliższe grupy punktów w coraz większe skupienia.

### Uruchomienie

```bash
git clone --branch Project_06 --single-branch https://github.com/FilipTw/AI_Projects_In_Polish.git
cd AI_Projects_In_Polish
jupyter notebook Twardawa_Filip_ML.ipynb
```

<br>

---

<sub>[← 05 · Regresja logistyczna](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_05) &nbsp;&nbsp;|&nbsp;&nbsp; [Wszystkie projekty](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;&nbsp;|&nbsp;&nbsp; [01 · Emisja CO₂ →](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_01)</sub>

<sub>Autor: Filip Twardawa &nbsp;·&nbsp; Licencja [MIT](LICENSE) &nbsp;·&nbsp; [Do góry ↑](#top)</sub>
