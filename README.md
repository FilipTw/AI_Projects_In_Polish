<a id="top"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-03-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-03-light.svg">
  <img alt="Projekt 03 — Skalowanie cech — standaryzacja i min-max" src="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-03-light.svg" width="100%">
</picture>

<br>

[**← Wszystkie projekty**](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;·&nbsp; [Notatnik](./Twardawa_Filip_ML.ipynb) &nbsp;·&nbsp; [Raport PDF](./Twardawa_Filip_ML.pdf)

<br>

## Skalowanie danych

### Cel

Celem ćwiczenia jest dobór odpowiedniej metody skalowania i jej zastosowanie dla różnych zbiorów danych.

### Zbiór danych

**iris.csv** — zbiór dotyczy trzech gatunków irysów. Każdy irys jest opisany czterema cechami oraz informacją o gatunku:

| | Cecha | Opis |
|:--:|:--|:--|
| 1 | `sepal_length` | długość działki kielicha |
| 2 | `sepal_width` | szerokość działki kielicha |
| 3 | `petal_length` | długość płatka |
| 4 | `petal_width` | szerokość płatka |
| 5 | `species` | gatunek: *Setosa, Versicolor, Virginica* |

Ćwiczenie obejmuje również dwa zbiory pomiarów spektroskopowych — widma Ramana i widma FTIR.

### Metody

**A · Normalizacja do zakresu [0, 1]**<br>
Przekształca każdą cechę tak, aby jej wartości mieściły się w przedziale od 0 do 1.

**B · Normalizacja do zakresu [−1, 1]**<br>
Przekształca każdą cechę do przedziału od −1 do 1.

**C · Standaryzacja**<br>
Sprowadza każdą cechę do średniej równej 0 i odchylenia standardowego równego 1.

### Uruchomienie

```bash
git clone --branch Project_03 --single-branch https://github.com/FilipTw/AI_Projects_In_Polish.git
cd AI_Projects_In_Polish
jupyter notebook Twardawa_Filip_ML.ipynb
```

<br>

---

<sub>[← 02 · CIFAR-10](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_02) &nbsp;&nbsp;|&nbsp;&nbsp; [Wszystkie projekty](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;&nbsp;|&nbsp;&nbsp; [04 · Boston Housing →](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_04)</sub>

<sub>Autor: Filip Twardawa &nbsp;·&nbsp; Licencja [MIT](LICENSE) &nbsp;·&nbsp; [Do góry ↑](#top)</sub>
