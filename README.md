# Remote Manager dla NVDA

Publiczna strona projektu, miejsce pobierania gotowych wydań oraz zgłaszania problemów.
Repozytorium rozwojowe i historia robocza dodatku nie są publikowane na GitHubie.

## Najnowsza wersja

**Remote Manager 1.46** dla NVDA 2025.1 lub nowszego.

- [Pobierz z oficjalnej strony autora](https://proszczok.pl/remotemenager/remoteManager-1.46.nvda-addon)
- [Strona dodatku i instrukcja](https://proszczok.pl/remotemenager/)
- SHA-256: `01cf8930aab22b4f19362624b505115a22ca64622f783ff5cf5c73b050a87ceb`

Paczka obsługuje 32-bitowe NVDA 2025.x oraz 64-bitowe NVDA 2026.1–2026.3.

Gdy ktoś steruje Twoim komputerem przez „Pomoc do tego komputera”, wybierz w menu dodatku `Schowek > Wyślij do komputera kontrolującego`, aby odesłać pomocnikowi tekst ze schowka. To samo polecenie jest w podmenu „Pomoc do tego komputera”.

## Co potrafi dodatek?

- utrzymuje do pięciu niezależnych stanowisk NVDA Remote Access;
- automatycznie ponawia połączenia po przerwie sieciowej;
- pozwala szybko wybierać komputer i przełączać sterowanie klawiszem F11;
- obsługuje mowę, dźwięki, brajl, klawiaturę i schowek;
- przesyła pliki do 20 MB w obu kierunkach;
- udostępnia osobne połączenie „Pomoc do tego komputera”;
- sprawdza aktualizacje przez HTTPS i weryfikuje paczki za pomocą SHA-256.

## Instalacja

1. Pobierz plik `.nvda-addon`.
2. Otwórz go i potwierdź instalację w NVDA.
3. Po ponownym uruchomieniu NVDA wybierz `NVDA > Narzędzia > Remote Manager`.

## Aktualizacje

GitHub pełni rolę strony informacyjnej, miejsca pobierania wydań i obsługi zgłoszeń.
Wbudowany aktualizator nadal korzysta wyłącznie z metadanych i paczek publikowanych na
`https://proszczok.pl/remotemenager/`. Wydanie na GitHubie nie zmienia kanału aktualizacji.

## Zgłaszanie problemów i pomysłów

Użyj zakładki **Issues** i wybierz formularz błędu albo propozycji funkcji. Przed dodaniem
logu usuń z niego klucze połączeń, adresy prywatnych serwerów i inne dane, których nie
chcesz publikować.

## Prywatność i bezpieczeństwo

- [Polityka prywatności](https://proszczok.pl/privacy.html)
- Dodatek nie wysyła danych diagnostycznych na GitHub.
- Serwer Remote Access przekazuje ruch sesji; szczegóły bezpieczeństwa są opisane w
  instrukcji dostępnej na stronie dodatku.

## Kod i licencja

To repozytorium nie zawiera osobnego drzewa rozwojowego ani historii źródeł. Paczka
`.nvda-addon` jest jednak archiwum z plikami Pythona i po pobraniu można ją rozpakować
oraz przeczytać jej zawartość. Dodatek jest rozpowszechniany na warunkach GNU GPL w
wersji 2 lub późniejszej. Nie jest to zaciemniony ani technicznie zamknięty plik binarny.

## Wsparcie autora

- [PayPal](https://paypal.me/proszczok)
- [Revolut](https://revolut.me/r_rosiejka)
- [Strona autora](https://proszczok.pl/)

