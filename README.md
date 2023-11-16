# DataScience2
16.11.2023 Zadanie z kursu CODE:ME

WCZYTANIE DANYCH
<br />1. Wczytano dane 'counties.csv'

PRZYGOTOWANIE DANYCH DO ALGORYTMU
<br />2. Segmentacja
<br />3. Usuwanie nulli
<br />4. Skalowanie danych (StandardScaler())

PIERWSZY PODZIAŁ
<br />5. 2 segmenty - label 0 i label 1 przy pomocy kMeans
<br />6. Zachowanie series z counties i label-level-0

DRUGI PODZIAŁ
<br />7. Podział ramki na dwie ramki (labels == 0  i labels == 1)
<br />8. Wytrenowanie KMeans wykorzystując dwie poprzednio stworzone ramki (n_clusters=2)
<br />9. Zapisanie wyników do dwóch szeregów z określonym drugim poziomem klasteryzacji label-level-1
<br />10. Złączenie tych szeregów metodą concat

ZŁĄCZENIE WYNIKÓW
<br />11. Dołączenie szeregu label-level-0 i label-level-1 do bazowej ramki danych
<br />12. Zapis ramki do pliku 'counties_labeled_csv'

PORÓWNANIE I WNIOSKI
<br />13. Porównanie ze sobą grupy 0 pierwszego poziomu z grupą 1 pierwszego poziomu
<br />14. Porównanie ze sobą grupy 0 drugiego poziomu otrzymaną z danych grupy 0 pierwszego poziomu z grupą 1 drugiego poziomu otrzymaną z danych grupy 0 pierwszego poziomu
<br />15. Użyto metod statystyki: mean, variance, count

BIBLIOTEKI
numpy
sklearn.cluster KMeans
sklearn.preprocessing StandardScaler

WNIOSKI
w notatniku
