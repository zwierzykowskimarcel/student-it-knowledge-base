

<h1>| Komenda | Przykład użycia | Do czego służy | </h1>
| :--- | :--- | :--- |
| pwd | pwd | Pokazuje, w jakim folderze teraz jesteś. |
| ls | ls -la | Wypisuje wszystkie pliki (te ukryte też) ze szczegółami. |
| cd | cd docs/ukos, cd .. | Wchodzi do folderu albo cofa o jeden poziom wyżej. |
| mkdir | mkdir -p docs/ukos | Tworzy nowy folder (i te po drodze, jeśli ich brakuje). |
| touch | touch bash.md | Tworzy pusty plik (albo odświeża jego datę). |
| cp | cp bash.md bash-backup.md | Kopiuje plik (z flagą -r kopiuje całe foldery). |
| mv | mv bash-backup.md archive.md | Przenosi plik albo zmienia mu nazwę. |
| rm | rm archive.md | Usuwa plik na stałe (uwaga: omija kosz!). |
| cat | cat bash.md | Wyświetla zawartość pliku w terminalu. |
| clear | clear | Czyści ekran terminala (historia komend zostaje). |

---

<h2> pwd </h2>- Gdy zgubisz się w terminalu, ta komenda pokaże pełną ścieżkę do folderu, w którym aktualnie siedzisz.</h2>
Przykład użycia:
```bash
pwd
```

<h2> ls </h2>- Pokazuje, co masz w bieżącym folderze. Dorzucenie -la sprawia, że widzisz też pliki ukryte (z kropką na początku) oraz dodatkowe informacje, takie jak rozmiar, uprawnienia czy data modyfikacji.
Przykład użycia:
```bash
ls -la
```

<h2> cd </h2> - Służy do chodzenia po folderach. Wpisujesz ścieżkę, żeby gdzieś wejść, a dwie kropki (..) cofają Cię o jeden folder wyżej.
Przykład użycia:
```bash
cd docs/ukos
cd ..
```

<h2> mkdir </h2> - Tworzy nowy folder. Flaga -p jest mega przydatna, bo jeśli chcesz stworzyć folder w folderze, którego jeszcze nie ma, system sam utworzy całą ścieżkę za jednym zamachem.
Przykład użycia:
```bash
mkdir -p docs/ukos
```

<h2> touch </h2> - Najszybszy sposób na stworzenie nowego, pustego pliku. Jeśli plik o tej nazwie już istnieje, komenda nic w nim nie zmieni, a jedynie zaktualizuje czas jego ostatniej modyfikacji.
Przykład użycia:
```bash
touch bash.md
```

<h2> cp </h2> - Kopiuje plik w inne miejsce lub pod inną nazwą. Jeśli chcesz skopiować cały folder razem z zawartością, musisz dopisać flagę -r (np. cp -r stary_folder nowy_folder).
Przykład użycia:
```bash
cp bash.md bash-backup.md
```

<h2> mv </h2> - Przenosi plik do innego folderu. Jeśli zostawiasz go w tym samym miejscu, ale podajesz inną nazwę – po prostu zmieniasz mu nazwę.
Przykład użycia:
```bash
mv bash-backup.md archive.md
```

<h2> rm </h2> - Kasuje plik. W terminalu nie ma kosza, więc usunięty plik znika od razu i bezpowrotnie.
Przykład użycia:
```bash
rm archive.md
```

<h2> cat </h2> - Wyrzuca całą zawartość pliku tekstowego bezpośrednio na ekran terminala. Dobre do szybkiego podglądu małych plików bez otwierania edytora.
Przykład użycia:
```bash
cat bash.md
```

<h2> clear </h2> - Sprząta bałagan na ekranie terminala, przesuwając widok na czystą stronę. Spokojnie, historia wpisanych wcześniej komend nie znika – nadal możesz do nich wrócić strzałką w górę.
Przykład użycia:
```bash
clear
```
