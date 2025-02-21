# HIV AIDS Project

**Autor:** Miraslau Alkhovik, 248655, Politechnika Łódzka

## Opis projektu

Projekt stanowi analizę epidemiologiczną HIV/AIDS w Polsce, ze szczególnym uwzględnieniem różnic regionalnych między województwami kujawsko-pomorskim i zachodniopomorskim. Celem analizy jest:

- Zbadanie dynamiki transmisji HIV/AIDS w wybranych regionach.
- Identyfikacja głównych dróg zakażenia (np. wstrzykiwanie narkotyków, kontakty heteroseksualne, kontakty homoseksualne).
- Porównanie liczby przypadków HIV i AIDS oraz analizy progresji choroby.
- Wizualizacja danych za pomocą wykresów (m.in. wykres radarowy, mapy, trendy czasowe) oraz analizy statystycznej.

## Struktura projektu

- **HIV_AIDS_PROJECT.ipynb** – Notebook Jupyter z kodem źródłowym, który realizuje:
  - Import i czyszczenie danych
  - Grupowanie i analizę statystyczną
  - Generowanie wizualizacji (m.in. wykres radarowy, mapa znormalizowana, analiza trendów i porównanie według płci)
  - Wnioski
- **Dane źródłowe:**
  - **EpiBaza PZH** – Zestawienia przypadków HIV i AIDS.
  - **GIS Support** – Dane granic administracyjnych województw Polski.

## Wymagania

Aby uruchomić projekt lokalnie, potrzebujesz:
- Python 3.x
- Jupyter Notebook lub JupyterLab

Biblioteki użyte w projekcie:
- `pandas`
- `numpy`
- `geopandas`
- `matplotlib`
- `plotly`
- `Pillow` (PIL)

## Instalacja i uruchomienie

1. **Sklonuj repozytorium:**

   ```bash
   git clone https://github.com/miraslauuu/HIV_AIDS_PROJECT.git
   
