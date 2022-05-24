
# Find alcohols by url



## etapy



## 1. Zapytanie

Stworzenie request.py odpowiadającego za wysyłanie zapytań oraz zapisywanie wyników do pliku

## 2. Baza alkoholi

Znalezienie bazy alkoholi oraz opracowanie pre_process_data_1.py, a następnie pre_process_data_2.py odpowiedzialnych za obróbkę danych

## 3. Wyniki

Przeprowadzono 2 główne próby dla opracowanej bazy alkoholi

W 1 próbie w zapytaniu wysyłano:
 - 
- jako wymagany brand alkoholu,
- jako opcjonalne nazwę alkoholu i przypisaną mu kategorie.

Dla 1 próby otrzymano 43 marki alkoholi

W 2 próbie w zapytaniu wysłano:
 - 
- jako wymagany brand alkoholu,
- jako opcjonalne nazwę alkoholu
- jako opcjonalne kategorie alkoholi: beer, wine, cider, mead, sake, gin, brandy, whiskey, rum, tequila, vodka, absinthe

Dla 2 próby otrzymano 87 marek alkoholi.

Dla obydwu prób optionalThreshold wynosił 1, a wszystkie słowa wyszukiwane były w trybie "c".

Wyniki obydwu prób wydają się zawierać tylko prawidłowe wyniki.