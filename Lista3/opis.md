Plik lista3.ipynb skupia się na analizie modeli regresji liniowej oraz konstrukcji przedziałów ufności. Oto szczegółowy opis tematów poruszonych w pliku:
1. Model regresji liniowej:
- Konstrukcja przedziałów ufności dla parametrów β _0 i β_1 na poziomie ufności α.
- Analiza przedziałów ufności przy różnych długościach prób n, poziomach ufności α∈{0.01, 0.05} oraz wariancjach σ∈{0.01, 0.5,1}.
- Sprawdzenie prawdopodobieństwa, że teoretyczne wartości parametrów należą do wyznaczonych przedziałów ufności za pomocą symulacji Monte Carlo.
- W symulacjach przyjęto, że x_i = i dla każdego i=1,2,…,n.
2. Konstrukcja przedziałów ufności przy nieznanej wariancji σ:
- Powtórzenie zadania 1 przy założeniu, że σ jest nieznana.
- Porównanie skonstruowanych przedziałów ufności z wynikami z zadania 1.
- Analiza różnic w przedziałach ufności w zależności od długości próby, poziomu ufności α oraz wariancji σ.
3. Symulacja wektora dwuwymiarowego (x, y):
- Wyznaczenie przedziałów ufności dla wartości średniej zmiennej Y(x_0) dla x_0=x+γ przy różnych wielkościach n.
- Założenie, że σ jest znana i nieznana.
- Analiza wyników w zależności od n, σ oraz γ.
- Przyjęcie poziomu ufności α=0.05.
4. Konstrukcja prostej regresji i przedziałów ufności dla prognozy:
- Symulacja dwuwymiarowego wektora (x, y) o długości n=1000 opisany modelem regresji liniowej.
- Konstrukcja prostej regresji na podstawie 990 najmniejszych obserwacji x.
- Konstrukcja przedziału ufności dla prognozy w modelu dla ostatnich 10 największych obserwacji.
- Porównanie wyników z danymi przy założeniu, że σ jest znana i nieznana.

Zadania te koncentrują się na praktycznych aspektach konstrukcji przedziałów ufności oraz analizie modeli regresji liniowej, z wykorzystaniem symulacji Monte Carlo do weryfikacji teoretycznych wyników.
