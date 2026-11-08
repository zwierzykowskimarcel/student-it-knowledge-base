## Opisy i przykłady

dotnet --version - Wyświetla numer wersji .NET SDK, z której aktualnie korzystasz. Przydaje się, żeby szybko upewnić się, czy środowisko jest dobrze zainstalowane.
Przykład użycia:
```bash
dotnet --version
```

dotnet new console - Tworzy podstawowy szkielet aplikacji konsolowej (plik Program.cs oraz plik projektu .csproj) bezpośrednio w folderze, w którym aktualnie jesteś.
Przykład użycia:
```bash
dotnet new console
```

dotnet new console -n - Robi to samo co wyżej, ale od razu tworzy dla projektu nowy folder o podanej nazwie (flaga -n to skrót od name) i wrzuca tam wszystkie pliki.
Przykład użycia:
```bash
dotnet new console -n MyApp
```

dotnet restore - Pobiera z internetu (z NuGeta) wszystkie pakiety i biblioteki, których projekt potrzebuje do działania. W nowszych wersjach .NET dzieje się to często automatycznie, ale warto znać tę komendę.
Przykład użycia:
```bash
dotnet restore
```

dotnet build - Kompiluje kod źródłowy do plików wykonywalnych (wrzuca je do folderów bin i obj). Świetne do szybkiego sprawdzenia, czy w kodzie nie ma błędów składniowych, bez odpalania programu.
Przykład użycia:
```bash
dotnet build
```

dotnet run - Kompiluje projekt (jeśli wprowadziłeś jakieś zmiany w kodzie) i od razu uruchamia aplikację w terminalu. Najczęściej używana komenda podczas pisania kodu.
Przykład użycia:
```bash
dotnet run
```

dotnet clean - Usuwa pliki wynikowe z poprzednich kompilacji (czyści zawartość folderów bin i obj). Przydaje się, gdy coś się przytnie przy budowaniu i chcesz przebudować projekt od zera.
Przykład użycia:
```bash
dotnet clean
```