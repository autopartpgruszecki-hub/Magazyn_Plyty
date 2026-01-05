# Magazyn_Plyty
# 📦 Warehouse Map Generator & Inventory Tracker

Prosty, lekki i niezwykle funkcjonalny generator map magazynowych stworzony w czystym JavaScript. Idealny dla małych i średnich magazynów, które potrzebują wizualnego zarządzania lokalizacjami bez wdrażania drogich systemów WMS.

## 🚀 Główne Funkcje

- **Interaktywny Generator:** Twórz siatkę magazynu o dowolnych wymiarach (kolumny x wiersze).
- **Inteligentna Numeracja Pionowa:** System automatycznie nadaje adresy (np. `P-1-1`, `P-1-2`) w układzie pionowym, ignorując wyłączone pola (ścieżki komunikacyjne).
- **Zarządzanie Pozycjami:** Każda lokalizacja obsługuje do 5 niezależnych slotów na produkty.
- **Eksport do Excel (CSV):** Generuj gotowe arkusze inwentaryzacyjne jednym kliknięciem. Puste pola są automatycznie uzupełniane jako "0".
- **Bezpieczeństwo Danych:** Stany magazynowe są zapisywane w `LocalStorage` przeglądarki – nie potrzebujesz serwera ani bazy danych.
- **Zapis Projektu:** Możliwość zapisu wygenerowanej mapy do fizycznego pliku HTML za pomocą File System Access API.

## 🛠️ Technologia

- **HTML5 / CSS3** (Grid & Flexbox)
- **Vanilla JavaScript** (ES6+)
- **File System Access API** (do zapisu plików lokalnie)
- **LocalStorage** (do przechowywania danych produktów)

## 📖 Instrukcja Obsługi

1. **Uruchom generator:** Otwórz `index.html` w przeglądarce.
2. **Skonfiguruj siatkę:** Ustaw liczbę kolumn i wierszy.
3. **Zdefiniuj alejki:** Kliknij `X` na polach, które mają być wyłączone z użytku (np. korytarze). Numeracja reszty pól zaktualizuje się automatycznie.
4. **Zapisz mapę:** Kliknij "Zapisz Mapę", aby wygenerować plik operacyjny `mapa.html` w wybranym folderze.
5. **Zarządzaj stanem:** Otwórz `mapa.html`, klikaj w regały i wpisuj towary. 

## 📂 Struktura Projektu

- `index.html` - Główny generator i edytor mapy.
- `README.md` - Dokumentacja projektu.

## 🌐 GitHub Pages

Aby korzystać z narzędzia online:
1. Wrzuć pliki na swoje repozytorium GitHub.
2. Wejdź w `Settings` -> `Pages`.
3. Wybierz branch `main` i kliknij `Save`.
4. Projekt będzie dostępny pod Twoim adresem `.github.io`.

---
*Created by [Twoje Imię/Nick]*
