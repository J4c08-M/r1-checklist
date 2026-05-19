# 🚑 Torba Ratownicza R1 — Mobilna Checklista Wyposażenia

Mobilna aplikacja webowa do kontroli wyposażenia torby ratowniczej R1 zgodnie z modułowymi zestawami. Działa offline jako statyczna strona HTML — bez instalacji, bez backendu.

🔗 **[Otwórz aplikację](https://j4c08-m.github.io/r1-checklist/)**

---

## 📋 Funkcje

- ✅ Checkboxy dla każdej pozycji wyposażenia
- 🔢 Liczniki ilości ze strzałkami dla każdego elementu
- 📦 Podział na **9 modułów** zgodnych z zestawem torby R1
- 📊 Pasek postępu i podsumowanie stanu na żywo
- 📝 Nagłówek kontroli: numer torby, data, osoba sprawdzająca, jednostka
- ✍️ Pole podpisu rysowane palcem (canvas)
- 📄 **Generowanie raportu PDF** z pełnym protokołem
- 📱 W pełni responsywna — zoptymalizowana pod mobile

---

## 🗂️ Moduły torby R1

| Moduł | Zawartość |
|-------|-----------|
| **A** | Drogi oddechowe (rurki, BVM, tlen) |
| **B** | Oddychanie (dekompresja, opatrunki okluzyjne, pulsoksymetr) |
| **C** | Krążenie / tamowanie krwawień (opaski CAT, Gaza hemostatyczna, bandaże) |
| **D** | Niedomoga neurologiczna (kołnierze, glukometr, GCS) |
| **E** | Ekspozycja / ochrona (koce NRC, termometr) |
| **F** | Płyny i dostęp naczyniowy (kaniule, dreny, płyny) |
| **M** | Leki podstawowe (adrenalina, midazolam, ketamina...) |
| **DEF** | Defibrylator / monitor EKG |
| **O** | Wyposażenie dodatkowe i dokumentacja |

---

## 🚀 Uruchomienie (GitHub Pages — darmowy plan)

Zgodnie z [oficjalnym quickstart GitHub Pages](https://docs.github.com/en/pages/quickstart), na darmowym koncie GitHub strona użytkownika musi znajdować się w repozytorium o nazwie `TWOJA-NAZWA.github.io`.

### Krok po kroku

1. Zaloguj się na [github.com](https://github.com) i kliknij **New repository**
2. Jako nazwę repozytorium wpisz dowolnie, np. `r1-checklist`
   czyli wpisz: `r1-checklist`)
3. Ustaw widoczność na **Public**
4. Zaznacz **Add a README file** i kliknij **Create repository**
5. Wgraj pliki `index.html`, `_config.yml` i `README.md` do repozytorium
6. Przejdź do **Settings → Pages → Build and deployment**
7. Ustaw Source: **Deploy from a branch**, Branch: **main**, folder: **/ (root)**
8. Po kilku minutach aplikacja będzie dostępna pod adresem:
   ```
   https://j4c08-m.github.io/r1-checklist/r1-checklistr1-checklist
   ```

> ℹ️ Na darmowym planie GitHub Pages działa tylko dla repozytoriów **publicznych**.

---

## 🛠️ Struktura projektu

```
j4c08-m.github.io/r1-checklist/r1-checklist
├── index.html        # Cała aplikacja (single-file)
├── _config.yml       # Konfiguracja Jekyll / GitHub Pages
└── README.md         # Ten plik
```

---

## 📄 Raport PDF — co zawiera

- Nagłówek z numerem torby, datą, osobą sprawdzającą, jednostką
- Procent kompletności zestawu
- Lista wszystkich pozycji z zaznaczeniem ☑/☐ i ilościami
- Uwagi dodatkowe
- Podpis cyfrowy (jeśli narysowany)
- Stopka z datą wygenerowania i numerami stron

---

## ⚠️ Uwaga prawna

Aplikacja jest narzędziem pomocniczym do kontroli wyposażenia. Nie zastępuje oficjalnych protokołów jednostki, szkoleń ani nadzoru medycznego. Zawsze postępuj zgodnie z obowiązującymi procedurami i wytycznymi właściwego organu (PRM, ZRM, KSRG).

---

## 📝 Licencja

MIT — używaj, modyfikuj, dziel się.
