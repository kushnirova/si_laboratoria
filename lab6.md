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
```Ten rozdział zostanie dodany trochę później```
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
```Ten rozdział zostanie dodany trochę później```
## RMSE <2.0
```Ten rozdział zostanie dodany trochę później```
## Najlepsza konfiguracja dla predykcji
```Ten rozdział zostanie dodany trochę później```
