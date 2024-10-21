# goit-js-hw-06

## Struktura projektu
Projekt składa się z następujących plików i folderów:
- `/js`
  - `task-1.js` - Rozwiązanie zadania 1: User Account
  - `task-2.js` - Rozwiązanie zadania 2: Warehouse
  - `task-3.js` - Rozwiązanie zadania 3: String Constructor
- `.gitignore` - Plik ignorujący niepotrzebne pliki w repozytorium
- `.prettierrc` - Plik konfiguracyjny dla Prettier
- `index.html` - Strona główna projektu, wyświetlająca wyniki zadań w przeglądarce
- `README.md` - Dokumentacja projektu

## Opis zadań

### Task 1: User Account
Celem tego zadania jest zrefaktoryzowanie metod obiektu `customer`, aby korzystały z właściwości obiektu przy użyciu `this`. Wyniki są wyświetlane w sekcji "Task 1 Results" w pliku `index.html`.

### Task 2: Warehouse
Zadanie polega na stworzeniu klasy `Storage`, która przechowuje tablicę towarów. Klasa posiada metody do dodawania, usuwania oraz pobierania towarów. Wyniki są wyświetlane w sekcji "Task 2 Results" w pliku `index.html`.

### Task 3: String Constructor
Zadanie polega na stworzeniu klasy `StringBuilder`, która posiada prywatną właściwość `value`. Klasa posiada metody do modyfikacji tej wartości: dodawanie tekstu na początku, na końcu oraz na obu końcach. Wyniki są wyświetlane w sekcji "Task 3 Results" w pliku `index.html`.

## Wymagania
- Kod musi być sformatowany za pomocą Prettier.
- Nie mogą występować żadne błędy ani ostrzeżenia w konsoli po uruchomieniu zadań.
- Taski 1, 2 i 3 muszą zostać wykonane i poprawnie wyświetlać wyniki w odpowiednich sekcjach strony `index.html`.

## Wyświetlanie wyników
Wyniki zadań są automatycznie wyświetlane w przeglądarce w odpowiednich sekcjach pliku `index.html`:
- Wyniki zadania 1 są wyświetlane w sekcji `#task-1-results`.
- Wyniki zadania 2 są wyświetlane w sekcji `#task-2-results`.
- Wyniki zadania 3 są wyświetlane w sekcji `#task-3-results`.

## Sformatowanie kodu za pomocą Prettier:

* Aby użyć Prettier, musisz zainstalować go w swoim projekcie. Można to zrobić, jeśli masz zainstalowany Node.js, za pomocą polecenia:
  
```bash
npm install --save-dev prettier
```

* Następnie możesz uruchomić Prettier na swoim kodzie za pomocą:

```bash
npx prettier --write .
```

To polecenie sformatuje wszystkie pliki w projekcie.
