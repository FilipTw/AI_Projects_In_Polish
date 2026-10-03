<a id="top"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-01-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-01-light.svg">
  <img alt="Projekt 01 — Emisja CO₂ — modele klasyczne kontra sieć MLP" src="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-01-light.svg" width="100%">
</picture>

<br>

[**← Wszystkie projekty**](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;·&nbsp; [Notatnik](./Muzykant_Wowra_Twardawa_PSI_2.ipynb) &nbsp;·&nbsp; [Raport PDF](./Muzykant_Wowra_Twardawa_PSI_2.pdf) &nbsp;·&nbsp; [Dane](./CO2-Emissions_Canada.csv)

<br>

## Porównanie klasycznych modeli uczenia maszynowego i sztucznych sieci neuronowych (MLP)

### Cel

Celem projektu jest przewidywanie poziomu emisji dwutlenku węgla (CO₂) przez pojazdy w zależności od ich cech, z wykorzystaniem algorytmów uczenia maszynowego, wraz z analizą zbioru danych i porównaniem skuteczności zastosowanych technik predykcji.

### Zbiór danych

**CO₂ Emissions Canada** (`CO2-Emissions_Canada.csv`) — dane o pojazdach: m.in. klasa pojazdu, pojemność silnika, liczba cylindrów, skrzynia biegów, rodzaj paliwa, zużycie paliwa oraz emisja CO₂ w g/km.

### Metody

**A · Regresja liniowa**<br>
Model liniowy stanowiący punkt odniesienia dla bardziej złożonych metod. Pozwala szybko uzyskać wyniki przy zachowaniu interpretowalności. Jest prosty w implementacji, ale może być mniej skuteczny dla złożonych danych z zależnościami nieliniowymi.

**B · k najbliższych sąsiadów (kNN)**<br>
Algorytm oparty na najbliższych sąsiadach. Ze względu na prostotę często stosowany w zadaniach eksploracyjnych. Jego skuteczność zależy od właściwego doboru liczby sąsiadów (parametr k) i miary odległości, co czyni go wrażliwym na skalowanie danych.

**C · MLP — model bazowy**<br>
Podstawowy model sieci neuronowej z dwiema warstwami ukrytymi. Potrafi rozwiązywać problemy nieliniowe, ucząc się złożonych zależności w danych. Charakteryzuje się umiarkowaną złożonością obliczeniową i stanowi punkt wyjścia dla bardziej zaawansowanych implementacji.

**D · MLP — model zoptymalizowany**<br>
Zaawansowany model sieci neuronowej z wieloma warstwami ukrytymi, zoptymalizowany pod względem architektury (liczba neuronów i warstw), funkcji aktywacji oraz hiperparametrów, takich jak współczynnik uczenia i regularyzacja. Zapewnia wysoką wydajność i dokładność, szczególnie w zadaniach wymagających analizy dużych i złożonych zbiorów danych.

### Uruchomienie

```bash
git clone --branch Project_01 --single-branch https://github.com/FilipTw/AI_Projects_In_Polish.git
cd AI_Projects_In_Polish
jupyter notebook Muzykant_Wowra_Twardawa_PSI_2.ipynb
```

<br>

---

<sub>[← 06 · Klasteryzacja](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_06) &nbsp;&nbsp;|&nbsp;&nbsp; [Wszystkie projekty](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;&nbsp;|&nbsp;&nbsp; [02 · CIFAR-10 →](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_02)</sub>

<sub>Autorzy: Muzykant · Wowra · Twardawa &nbsp;·&nbsp; Licencja [MIT](LICENSE) &nbsp;·&nbsp; [Do góry ↑](#top)</sub>
