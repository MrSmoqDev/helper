# 🎓 Interaktywna Platforma Edukacyjna: Python & C++

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Nowoczesna, responsywna strona edukacyjna stworzona w czystym HTML/CSS**, oferująca kompleksowe kursy programowania w językach **Python** i **C++**. Projekt hostowany na GitHub Pages, zaprojektowany z myślą o czytelności, nawigacji i praktycznych przykładach.

---

## 🚀 Demo

Odwiedź żywą stronę tutaj: **[🔗 LINK_DO_TWOJEJ_STRONY.github.io](https://twoj-nick.github.io/twoje-repo/)**

*(Zastąp powyższy link swoim adresem GitHub Pages)*

---

## ✨ Funkcje

*   🎨 **Nowoczesny Design** – Czysty interfejs z kolorami nawiązującymi do danego języka (Python: żółty/niebieski, C++: niebieski).
*   📱 **Responsywność** – Strona dostosowuje się do komputerów, tabletów i telefonów.
*   🧭 **Podwójna Nawigacja** – Lewy sidebar (moduły) + Prawy sidebar (spis treści w lekcji).
*   🖥️ **Podświetlanie Kodu** – Własne style CSS imitujące edytor kodu (VS Code style).
*   🛠️ **Praktyczne Projekty** – Każda ścieżka kończy się gotowym projektem (np. Gra, Kalkulator, Logger).
*   ⚡ **Szybkość** – Strona statyczna, błyskawiczne ładowanie, brak baz danych.

---

## 📚 Program Kursu

### 🐍 Ścieżka Python
Kompleksowy wstęp do języka Python, od podstaw po zaawansowane struktury danych.

| Moduł | Tematyka | Projekt |
|-------|----------|---------|
| **General** | Wstęp, instalacja, środowiska | - |
| **Math** | Operacje, stałe, trygonometria | Kalkulator naukowy |
| **Time** | Czas, sleep, formatowanie | Odliczanie |
| **Files** | Zapis/odczyt, JSON, path | Menedżer ustawień |
| **Random** | Losowość, wagi, seed | Generator haseł |
| **String** | Manipulacja tekstem, f-strings | Walidator Emaila |
| **Lists** | Listy, słowniki, slicing | Ekwipunek gracza |
| **Datetime** | Daty, timedelta, timezone | System cooldownów |
| **Game** | Pętle, input, logika | Gra "Zgadnij Liczbę" |

### ⚡ Ścieżka C++
Wydajne programowanie strukturalne i obiektowe.

| Moduł | Tematyka | Projekt |
|-------|----------|---------|
| **General** | Kompilacja, Hello World, IDE | - |
| **Syntax** | Operatory, cin/cout, składnia | - |
| **Variables** | Typy danych, const, auto | Kalkulator BMI |
| **Control** | If, switch, pętle for/while | Gra w zgadywanie |
| **Functions** | Deklaracja, przeciążanie, rekurencja | Kalkulator naukowy |
| **Arrays** | Tablice, wektory, stringi | Lista zakupów |
| **OOP** | Klasy, obiekty, dziedziczenie | System Bohaterów |
| **Files** | fstream, zapis/odczyt | Dziennik (Logger) |
| **Game** | Tablice 2D, logika gry | Kółko i Krzyżyk |

---

## 📂 Struktura Projektu

```bash
.
├── index.html              # Strona główna (Menu wyboru języka)
├── README.md               # Dokumentacja
├── python/                 # 🐍 Sekcja Python
│   ├── style.css           # Arkusz stylów Python
│   ├── general.html        # Wstęp do Pythona
│   └── modules/            # Lekcje Pythona
│       ├── math.html
│       ├── time.html
│       ├── files.html
│       ├── random.html
│       ├── string.html
│       ├── lists.html
│       ├── json.html
│       ├── datetime.html
│       └── game.html
└── cpp/                    # ⚡ Sekcja C++
    ├── style.css           # Arkusz stylów C++
    ├── general.html        # Wstęp do C++
    └── modules/            # Lekcje C++
        ├── syntax.html
        ├── variables.html
        ├── control.html
        ├── functions.html
        ├── arrays.html
        ├── oop.html
        ├── files.html
        └── game.html
