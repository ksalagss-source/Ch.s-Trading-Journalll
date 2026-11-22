CH.S Trading Journal — AlgoBrothers

WERSJA 0.1: działająca aplikacja PWA (prototyp lokalny).

Uruchomienie: umieść pliki z tego folderu na hostingu HTTPS (np. Netlify, Cloudflare Pages, GitHub Pages) i otwórz adres na telefonie. W przeglądarce wybierz "Dodaj do ekranu głównego" / "Zainstaluj aplikację".

Do testów na komputerze: python3 -m http.server 8000 w folderze, następnie otwórz http://localhost:8000.

Funkcje: dodawanie/edycja/usuwanie transakcji, statystyki, krzywa P&L, analiza strategii, emocje i dyscyplina, CSV, kopie JSON.

WAŻNE: Nie ma logowania Discord ani weryfikacji członkostwa. Link może otworzyć każdy, kto go zna. Dane zapisywane są lokalnie w przeglądarce (localStorage), bez synchronizacji między urządzeniami. Nie używaj do przechowywania poufnych informacji. Nie ma automatycznego pobierania transakcji z brokera. Aby wdrożyć dostęp tylko dla AlgoBrothers, potrzebne są backend, baza danych i OAuth2 Discord z serwerową kontrolą ról.
