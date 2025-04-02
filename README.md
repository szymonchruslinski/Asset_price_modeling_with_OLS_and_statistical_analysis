# Modelowanie cen aktywów z wykorzystaniem OLS i testów statystycznych

To repozytorium zawiera projekt analizy danych finansowych trzech wybranych aktywów (złoto, srebro, kawa), z wykorzystaniem danych historycznych pozyskanych z API Yahoo Finance.

Celem projektu jest zbadanie zależności między cenami wybranych aktywów poprzez obliczenie statystyk opisowych, budowę modeli regresyjnych metodą najmniejszych kwadratów (OLS), a także zastosowanie testów statystycznych w celu porównania rozkładów i średnich.  
Dane zostały przekształcone i zapisane lokalnie w celu zapewnienia stabilności działania analizy.  
Projekt został zrealizowany w języku Python. Raport końcowy przedstawia wyniki modelowania oraz wnioski statystyczne.

## Zakres projektu

- Pobranie danych z Yahoo Finance
- Obliczenie statystyk opisowych dla każdego z aktywów
- Budowa modeli regresyjnych OLS:
  - `Y ~ X1 + X2`
  - `Y ~ X1`
  - `Y ~ X2`
- Ocena dopasowania modeli regresyjnych
- Weryfikacja hipotez statystycznych:
- Test równości średnich
- Test porównania rozkładów (test Kołmogorowa-Smirnowa)

## Narzędzia

- **Python** – analiza danych i modelowanie
