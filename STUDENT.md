# Moje wykonanie Lab00

- Login GitHub / pseudonim: michalsuchorski
- System i terminal (np. Windows + WSL Ubuntu): MacOS + iTerm
- Edytor / IDE: Visual Studio Code
- Wersja Git: 2.52.0
- Wersja kompilatora C++: clang-1700.6.3.2
- Wersje java i javac: 17.0.20
- Link do pierwszego PR (uzupełnij w zadaniu 5): [Link](https://github.com/michalsuchorski/oop-lab00-michalsuchorski/commit/1249f78654c902d91027bfa17ef490be2220dd74)

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! Author: msuchorski
```
Wynik programu Java:
```text
Hello from Java! Author: msuchorski
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: 5: error: expected ‘;’ before ‘return’
- Przyczyna oraz sposób naprawy: Brak ";" na końcu linii
- Commit z błędem (SHA lub link): [Link](https://github.com/michalsuchorski/oop-lab00-michalsuchorski/commit/58a1be0e718c40d6272bfa7811a4dcd62f175e26)
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push? 
- Commit zapisuje tylko zmiany w lokalnej historii, a push wysyła commit do repozytorium zdalnego.

2. Dlaczego po scaleniu PR wykonuję lokalnie pull? 
- Bo zazwyczaj przechodzi się na główną gałęź po scaleniu, to trzeba wtedy pobrać te zmiany z głównej gałęzi, zeby nie było błędów przy następnych commitach.

3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza?
- Potwierdza skompilowanie się kodu i uruchomienie go w środkowisku CI, ale nie sprawdza konfiguracji komputera i reszty zadań.


## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...
