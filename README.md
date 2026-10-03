<a id="top"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-02-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-02-light.svg">
  <img alt="Projekt 02 — CIFAR-10 — sieci konwolucyjne" src="https://raw.githubusercontent.com/FilipTw/AI_Projects_In_Polish/main/assets/header-02-light.svg" width="100%">
</picture>

<br>

[**← Wszystkie projekty**](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;·&nbsp; [Notatnik](./Muzykant_Wowra_Twardawa_PSI_3.ipynb) &nbsp;·&nbsp; [Raport PDF](./Muzykant_Wowra_Twardawa_PSI_3.pdf)

<br>

## Zastosowanie sieci neuronowych i głębokiego uczenia

### Cel

Celem projektu jest zbudowanie skutecznych modeli głębokiego uczenia, które będą w stanie klasyfikować obrazy ze zbioru CIFAR-10.

### Zbiór danych

**CIFAR-10** — kolorowe obrazy o rozmiarze 32 × 32 piksele, podzielone na 10 klas, m.in. samolot, samochód, ptak, kot i statek.

### Metody

**A · Bazowy model CNN**<br>
Podstawowy model oparty na konwolucyjnych sieciach neuronowych (CNN). Zawiera kilka warstw konwolucyjnych i poolingowych, które pozwalają wyodrębnić kluczowe cechy obrazów. Stosunkowo prosta architektura umożliwia szybki trening i uzyskanie wstępnych wyników. Ze względu na ograniczoną liczbę warstw model może mieć trudności z uchwyceniem bardziej złożonych wzorców w danych.

**B · Pośredni model CNN**<br>
Rozszerzenie modelu bazowego. Zawiera więcej warstw konwolucyjnych i większą liczbę neuronów w warstwie gęstej, co pozwala dokładniej wyodrębniać cechy obrazów i poprawić trafność klasyfikacji.

**C · Zoptymalizowany model CNN**<br>
Najbardziej zaawansowany model w projekcie. Wykorzystuje techniki takie jak normalizacja wsadowa (Batch Normalization) i dropout, które poprawiają generalizację i ograniczają przeuczenie. Model zoptymalizowano również pod względem liczby warstw, liczby neuronów i funkcji aktywacji, dzięki czemu osiąga wysoką skuteczność w klasyfikacji obrazów.

### Uruchomienie

```bash
git clone --branch Project_02 --single-branch https://github.com/FilipTw/AI_Projects_In_Polish.git
cd AI_Projects_In_Polish
jupyter notebook Muzykant_Wowra_Twardawa_PSI_3.ipynb
```

<br>

---

<sub>[← 01 · Emisja CO₂](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_01) &nbsp;&nbsp;|&nbsp;&nbsp; [Wszystkie projekty](https://github.com/FilipTw/AI_Projects_In_Polish) &nbsp;&nbsp;|&nbsp;&nbsp; [03 · Skalowanie cech →](https://github.com/FilipTw/AI_Projects_In_Polish/tree/Project_03)</sub>

<sub>Autorzy: Muzykant · Wowra · Twardawa &nbsp;·&nbsp; Licencja [MIT](LICENSE) &nbsp;·&nbsp; [Do góry ↑](#top)</sub>
