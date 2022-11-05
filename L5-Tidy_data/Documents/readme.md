Analiza i bazy danych - Laboratorium 5 - TIER protocol i Tidy data.

Najpierw wybrałem swój zbiór danych do analizy:
- Numer swojego datasetu to 4 - o nazwie "drinks.csv". 
- Uzyskany został ze wzoru: (N mod 5) +1, gdzie N to liczba liter w nazwisku (Walawski: N=8).

Następnie utworzyłem 4 foldery o nazwach: AnalysisData, CommandFiles, Documents, OriginalData.

---------------
/OriginalData/
- Do tego folderu pobrałem oryginalny plik ze zbiorem danych o nazwie "drinks.csv".
- Link do jego pobrania z Githuba znajduje się pod koniec artykułu na stronie: https://fivethirtyeight.com/features/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/
- Dane przedstawione w tym pliku dotyczą badań WHO odnośnie spożycia trzech rodzajów alkoholi oraz całkowitego spożycia czystego alkoholu w 193 krajach.
- W tym folderze znajduje się też przewodnik po metadanych "Metadata_guide" z dokładnym opisem pliku "drinks.csv".
- Plik z tymi danymi jest w formacie o rozszerzeniu ".csv", więc jest on już importowalny i nie trzeba zmieniać jego rozszerzenia.

---------------
/CommandFiles/
- W tym folderze znajduje się notebook (plik Jupytera) o nazwie "raport_Kajetan_Walawski.ipynb" z kodem programu, który pokazuje ogólne informacje o plikach, a także z oryginalnego zbioru danych usuwa wiersze z krajami, w których spożycie alkoholu jest równe 0.
- Znajdują się tam także wykresy przedstawiające średnie spożycie badanych rodzajów alkoholi oraz wykresy przedstawiające największe spożycie poszczególnych rodzajów alkoholi.
- Nowy zbiór danych został zapisany w folderze /AnalysisData/ pod nazwą "drinks_no_zeros.csv".

---------------
/AnalysisData/
- W tym folderze znajduje się plik po analizie o nazwie "drinks_no_zeros.csv".
- Plik ten powstał z oryginalnego pliku "drinks.csv" poprzez usunięcie z niego wierszy z krajami o zerowym spożyciu alkoholu.
- Dokładny opis tego pliku znajduje się pod lokalizacją: **/Documents/dataAppendix.md

---------------
/Documents/
- Folder ten zawiera plik "dataAppendix.md" z opisem pliku po analizie (o nazwie "drinks_no_zeros.csv").
- Drugim plikiem jest ten ten plik "readme.md" z opisem wszystkich folderów oraz kolejnością wykonywanych działań podczas analizy danych.




