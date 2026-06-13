
# Instrukcja uruchomienia projektu (z archiwum ZIP)

Poniżej znajduje się kompletny przewodnik, jak krok po kroku rozpakować, zainstalować zależności i uruchomić projekt na komputerze lokalnym.

---

### Krok 1. Rozpakowanie archiwum
1. Pobierz plik ZIP z projektem.
2. Rozpakuj zawartość archiwum do dowolnego folderu na swoim komputerze (np. na Pulpit).

### Krok 2. Otwarcie terminala w folderze projektu
Aby móc wykonywać polecenia, należy otworzyć wiersz poleceń (terminal) dokładnie w rozpakowanym folderze projektu (tam, gdzie znajduje się plik `package.json`):
* **System Windows:** Otwórz folder projektu, kliknij prawym przyciskiem myszy na pustą przestrzeń i wybierz **"Otwórz w terminalu"** (alternatywnie: kliknij w pasek adresu na samej górze eksploratora plików, wpisz `cmd` i naciśnij *Enter*).
* **System macOS:** Kliknij prawym przyciskiem myszy na folder projektu i wybierz **"Nowy terminal w folderze"**.

### Krok 3. Weryfikacja środowiska (Node.js)
Projekt do działania wymaga zainstalowanego środowiska **Node.js** (zalecana wersja LTS).
* Jeśli Node.js nie jest zainstalowany, należy go pobrać z oficjalnej strony: [nodejs.org](https://nodejs.org/) i zainstalować (wybierając standardowe ustawienia instalatora).

### Krok 4. Instalacja zależności
W otwartym terminalu wpisz następujące polecenie i naciśnij *Enter*, aby automatycznie pobrać wszystkie wymagane pakiety i biblioteki:
```bash
npm install


### Krok 5. npm run dev