<a id="top"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-04-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-04-light.svg">
  <img alt="Projekt 04 — Boston Housing — Ridge, Lasso i ElasticNet" src="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-04-light.svg" width="100%">
</picture>

<br>

[**← Wszystkie projekty**](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;·&nbsp; [Notatnik](./Twardawa_Filip_ML.ipynb) &nbsp;·&nbsp; [Raport PDF](./Twardawa_Filip_ML.pdf)

<br>

## Regresja liniowa i regularyzacja

### Cel

Celem ćwiczenia było zastosowanie technik uczenia nadzorowanego do przewidywania mediany cen nieruchomości w Bostonie (kolumna MEDV) na podstawie dostępnych cech opisujących dane społeczno-ekonomiczne i demograficzne, w szczególności z użyciem regresji liniowej. Ćwiczenie obejmowało również wprowadzenie regularyzacji (regresja grzbietowa, Lasso i ElasticNet) w celu poprawy efektywności modelu.

### Zbiór danych

Zbiór opisuje ceny nieruchomości w Bostonie i składa się z 506 wierszy oraz 13 cech opisowych, m.in. CRIM (wskaźnik przestępczości), RM (średnia liczba pokoi) czy LSTAT (odsetek mieszkańców o niskim statusie). Przewidywaną cechą była MEDV — mediana wartości nieruchomości w tysiącach dolarów.

<details>
<summary><b>Opis cech</b></summary>
<br>

| Cecha | Opis |
|:--|:--|
| `CRIM` | wskaźnik przestępczości w mieście |
| `ZN` | odsetek dużych działek — powyżej 2500 m² |
| `INDUS` | odsetek terenów przemysłowych w mieście |
| `CHAS` | 1, jeśli teren leży przy rzece Charles, w przeciwnym razie 0 |
| `NOX` | stężenie tlenków azotu |
| `RM` | średnia liczba pokoi w budynku |
| `AGE` | odsetek starych budynków — sprzed 1940 roku |
| `DIS` | ważona odległość od centrów pracy w Bostonie |
| `RAD` | wskaźnik dostępności głównych dróg |
| `TAX` | podatek od nieruchomości liczony od 10 000 USD |
| `PTRATIO` | liczba uczniów na nauczyciela w mieście |
| `B` | wskaźnik demograficzny — zmienna historyczna |
| `LSTAT` | odsetek mieszkańców o niskim statusie |
| **`MEDV`** | **mediana wartości domów na danym obszarze, w tys. USD** |

</details>

### Metody

**A · Regresja liniowa**<br>
Podstawowy model regresji, punkt odniesienia dla modeli z regularyzacją.

**B · Regresja grzbietowa (Ridge)**<br>
Regresja liniowa z regularyzacją L2.

**C · Lasso**<br>
Regresja liniowa z regularyzacją L1.

**D · ElasticNet**<br>
Połączenie regularyzacji L1 i L2.

### Uruchomienie

```bash
git clone --branch Project_04 --single-branch https://github.com/FilipTw/AI_Projects_In_Polish.git
cd AI_Projects_In_Polish
jupyter notebook Twardawa_Filip_ML.ipynb
```

<br>

---

<sub>[← 03 · Skalowanie cech](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_03) &nbsp;&nbsp;|&nbsp;&nbsp; [Wszystkie projekty](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;&nbsp;|&nbsp;&nbsp; [05 · Regresja logistyczna →](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_05)</sub>

<sub>Autor: Filip Twardawa &nbsp;·&nbsp; Licencja [MIT](LICENSE) &nbsp;·&nbsp; [Do góry ↑](#top)</sub>
