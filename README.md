# Gul gul! 🦃

Przeglądarkowa gra, w której chudy biegacz ucieka przez pole przed indykiem.

## Uruchomienie

Otwórz `index.html` w przeglądarce. Gra nie wymaga instalacji, bibliotek ani serwera.

## Sterowanie

- **← → naprzemiennie** — bieganie. Przytrzymywanie klawisza nie wystarczy.
- **Spacja** — skok; na ekranie startowym lub po zakończeniu biegu uruchamia poziom.
- Na ekranie dostępne są także przyciski dotykowe.

Każdy bieg poprzedza odliczanie **3… 2… 1… GUL!**. Przeskakuj kałuże błota: wejście w kałużę spowalnia na 0,65 sekundy, tylko raz na kałużę.

## Poziomy

| Poziom | Trasa | Kałuże |
| --- | --- | --- |
| Rozgrzewka | 240 m | 3 |
| Obrażony indyk | 280 m | 5 |
| Dziób zemsty | 320 m | 8 |
| Indyk ostateczny | 360 m | 12 |

Wygrana pozwala przejść dalej, a przegrana — powtórzyć bieżący poziom. Dźwięk można włączyć przyciskiem w grze.

## Technologia

HTML, CSS i JavaScript, grafika rysowana na Canvas, dźwięki generowane przez Web Audio. Cała gra mieści się w `index.html`.
