# Matryca wyświetlaczy 8x8 kontrolowanych przez Arduino ze sterowaniem Bluetooth

### Autor: Artur Bieniek

# Instrukcja użytkowania aplikacji na Androida

## Instalacja aplikacji
 - Pobierz plik "Matrix8x8.apk"
 - Uruchom plik na urządzeniu z systemem Android
 - Zezwól na instalację aplikacji z nieznanych źródeł

## Pierwsze połączenie
- Przejdź do ustawień Bluetooth
- Wyszukaj dostępne urządzenia
- Sparuj urządzenie "MODUL", kod parowania to 1234
 
## Łączenie z wyświetlaczem
 - Uruchom aplikację "Matrix 8x8"
 - Kliknij we flagę, aby zmienić język
 - Kliknij przycisk "Połącz z wyświetlaczem"

## Wysyłanie tekstu
Aby wysłać tekst, wpisz go w pole tekstowe i kliknij przycisk "WYŚLIJ"

## Pamięć
Aplikacja oferuje 3 sloty zapisu tekstu.

Tekst jest zapisywany trwale w pamięci urządzenia (nie zniknie po zamknięciu aplikacji).

Aby zachować tekst, wpisz go w pole tekstowe i kliknij "USTAW M1"/"USTAW M2"/"USTAW M3".

Aby przywołać zachowany wcześniej tekst, kliknij "M1"/"M2"/"M3"

## Inne komendy sterujące
"WOLNIEJ" - zmniejsza prędkość przewijania tekstu na wyświetlaczu

"SZYBCIEJ" - zwiększa prędkość przewijania tekstu na wyświetlaczu

"CIEMNIEJ" - zmniejsza jasność wyświetlacza

"JAŚNIEJ" - zwiększa jasność wyświetlacza

"CZYŚĆ" - czyści wyświetlacz (nic się nie wyświetla)

"PAUZA" - pauzuje/odpauzowuje przewijanie tekstu

# Kompilacja ze źródeł
Kod źródłowy znajduje się w pliku "kod_zrodlowy.ino".
Do jego kompikacji wymagane jest środowisko Arduino IDE oraz dwie zewnętrzne biblioteki (w tym jedna zmodyfikowana w celu poprawnego wyświetlania polskich znaków):
 - Adafruit GFX
 - Max72xxPanel

Zostały one dołączone do projektu. Oba foldery z bibliotekami należy umieścić w folderze **Dokumenty/Arduino/libraries/**.
Następnie należy uruchomić ponownie Arduino IDE.

# Użytkowanie
Wyświetlacza można używać w tych pozycjach:
![pionowo](img/pionowo.png)
![poziomo](img/poziomo.png)
