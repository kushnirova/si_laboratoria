# Laboratorium 6
## Porównanie wyników modeli LSTM i GRU
Przy użyciu modelu **LSTM** wykres danych predykcyjnych na ogół jest bardzo podobny do wykresu danych rzeczywistych, aczkolwiek
jest nieco "przesunięty" w sposób liniowy w górę i w prawo. Wykres jest przedstawiony poniżej.

<img width="647" height="491" alt="image" src="https://github.com/user-attachments/assets/9d57bafb-3183-4e53-99e1-ffbca80d41cd" />

*Wykres danych presykcyjnych oraz danych rzeczywistych dla modelu LSTM.*

Skuteczność modelu reprezentuje sie następująco:
- Błąd średniokwadratowy modelu: 4.73
- Średni błąd bezwzględny: 4.16
- Średni błąd względny: **2.64%**

Dla modelu **GRU** wykres wygląda na bardziej dopasowany pod tym właśnie względem "przeswunięcia", 
wykres przedstawiony jest poniżej.

<img width="647" height="491" alt="image" src="https://github.com/user-attachments/assets/51901922-7b08-4cdd-930e-1240bbb91d8f" />

*Wykres danych presykcyjnych oraz danych rzeczywistych dla modelu GRU.*

Skuteczność modelu reprezentuje sie następująco:
- Błąd średniokwadratowy modelu: 3.26
- Średni błąd bezwzględny: 2.24
- Średni błąd względny: **1.41%**

Porównując te wyniki można śmiało stwierdzić, że w tym przypadku GRU poradziło sobie lepiej względem LSTM, 
lecz dobrze widoczne jest, że wynika to z mniejszego "przesunięcia" wszystkich predykcji modelu.


## Eksperymenty z ilością jednostek LSTM
Przy 30 jednostkach LSTM wykres dopasowania danych ma mniejsze "przesunięcie" i wygląda być nieco bardziej dopasowany do naszych dancyh, ale w bardzo subtelny sposób.

<img width="647" height="491" alt="image" src="https://github.com/user-attachments/assets/0568263e-8094-4fe9-ab63-a91e676a83d6" />

*Wykres danych presykcyjnych oraz danych rzeczywistych dla modelu LSTM przy 30 jednostkach.*

Przy zmianie bardziej drastycznej (w moim przypadku obniżeniu do 10 jednostek LSTM) model już wyraźnie gorzej sobie poradził. Wykres jest zbyt gładki i mało dostosowany do danych rzeczywistych.

<img width="647" height="491" alt="image" src="https://github.com/user-attachments/assets/5d10bdfa-131f-49a8-98d2-ddaad4da88a2" />

*Wykres danych presykcyjnych oraz danych rzeczywistych dla modelu LSTM przy 10 jednostkach.*

W przypadku 70 jednostek na wykresie możemy zobaczyć, że dane predykcyjne zrobiły się bardziej "szpiczaste", lepiej dopasowują się do nagłych zmian na rynku,
przseunięcie natomiast jest wyraźnie mniejsze, niż w przypadku mniejszej ilości jednostek. Udało się również uzyskać RSE na poziomie 1.4%, co było jednym z zadań do wykonania podczas laboratorium.

<img width="647" height="491" alt="image" src="https://github.com/user-attachments/assets/0bafa5d3-7315-4c72-9c00-0d38bd774e17" />

*Wykres danych presykcyjnych oraz danych rzeczywistych dla modelu LSTM przy 70 jednostkach.*

## Testy innych optymalizatorów
### SGD
```Ten rozdział zostanie dodany trochę później```
### Adam
```Ten rozdział zostanie dodany trochę później```
### AdamW
```Ten rozdział zostanie dodany trochę później```
## Testy inncyh funkcji strat

### Mean Absolute Error
```Ten rozdział zostanie dodany trochę później```
### Huber
```Ten rozdział zostanie dodany trochę później```
### LogCosh
```Ten rozdział zostanie dodany trochę później```
## Zmiana atrybutu predykcji z "High" na "Close"
```Ten rozdział zostanie dodany trochę później```
## Test mechanizmu early stoppung
Dodanie early stopping do algorytmu znacznie skróciło średni czas dopasowania modelu, szczególne podczas wykorzystania modelu LSTM o większej ilości jednostek (>30)
## Najlepsza konfiguracja dla predykcji
```Ten rozdział zostanie dodany trochę później```
