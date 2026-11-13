# Enigma2-Plugins
Autorskie wtyczki dla Enigma2

# 📺 Moje Wtyczki dla Enigma2 (Python 3)

Zestaw autorskich wtyczek dla odbiorników z systemem Enigma2 (przetestowane na różnych obrazach z Pythonem 3).

---

## 🎬 1. RecommendedMovies (Polecane Filmy)

Wtyczka służy do szybkiego i wygodnego przeglądania polecanych filmów emitowanych w polskiej telewizji na najbliższe godziny. 

### ✨ Główne funkcje:
* **Przejrzysty interfejs:** Wyświetla tytuł filmu, plakat/screen, szczegółowy opis fabuły oraz kanał, na którym film będzie emitowany.
* **Oceny:** Informacja o ocenach filmu, co ułatwia wybór seansu.
* **Obsada:** Wyświetlanie listy aktorów grających w danej produkcji.
* **Uniwersalność:** Instalator automatycznie wykrywa i konfiguruje wymagane biblioteki (`bs4`, `soupsieve`) niezależnie od wersji Pythona w Twoim obrazie.

---

## ☀️ 2. OpenMeteoMonitor (Monitor Pogody)

Lekka wtyczka do automatycznego wyświetlania aktualnych informacji o pogodzie bezpośrednio na ekranie Twojego telewizora.

### ✨ Główne funkcje:
* **Harmonogram wyświetlania:** Możliwość ustawienia w konfiguracji określonego czasu/interwału, kiedy pogoda ma się pojawiać na ekranie.
* **Wybór lokalizacji:** Łatwy wybór Twojego miasta w menu ustawień.
* **Język polski:** Cała wtyczka oraz komunikaty pogodowe są w pełni w języku polskim.
* **Dyskretne działanie:** Wyświetla kluczowe parametry pogody i znika po wyznaczonym czasie, nie przeszkadzając w oglądaniu telewizji.

---

## 📥 Instrukcja Instalacji (.ipk)

1. Pobierz pliki instalacyjne `.ipk` z zakładki **[Releases / Wydania](../../releases)** po prawej stronie.
2. Prześlij plik `.ipk` za pomocą programu FTP (np. FileZilla / WinSCP) do katalogu `/tmp` w dekoderze.
3. Połącz się z dekoderem przez terminal (PuTTY / SSH / Telnet) i wpisz odpowiednią komendę:

**Dla wtyczki RecommendedMovies:**
```bash
opkg install /tmp/enigma2-plugin-extensions-recommendedmovies_1.0_all.ipk

**Dla wtyczki OpenMeteoMonitor:**
opkg install /tmp/enigma2-plugin-extensions-openmeteomonitor_1.0_all.ipk

4.Po instalacji interfejs Enigma2 zrestartuje się automatycznie, a nowa wtyczka pojawi się na liście rozszerzeń (Menu -> Wtyczki).
