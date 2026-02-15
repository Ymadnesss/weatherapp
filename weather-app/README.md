### 54516 – Aplikacja pogodowa w React

Projekt aplikacji pogodowej wykonany w ramach zaliczenia przedmiotu **Programowanie Frontend**.  
Aplikacja umożliwia sprawdzenie aktualnych warunków atmosferycznych oraz 5-dniowej prognozy pogody dla dowolnie wybranego miasta na świecie.

Główne założenia projektu:

- Wykorzystanie biblioteki **React** oraz nowoczesnych hooków (`useState`, `useEffect`, `useMemo`, `useCallback`)
- Integracja z zewnętrznym API – **OpenWeatherMap**
- Zarządzanie stanem globalnym przy użyciu **Redux Toolkit**
- Implementacja nawigacji pomiędzy podstronami z użyciem **React Router**
- Zapisywanie wybranych danych (np. ulubionych miast) w `localStorage`

---

## ⚙️ Technologie wykorzystane w projekcie

| Technologia | Wersja | Zastosowanie |
|-------------|--------|--------------|
| React | 18.2.0 | Tworzenie interfejsu użytkownika |
| Redux Toolkit | 1.9.7 | Zarządzanie stanem globalnym aplikacji |
| React Router | 6.20.0 | Obsługa routingu i nawigacji |
| Axios | 1.6.2 | Komunikacja z API |
| OpenWeatherMap API | - | Źródło danych pogodowych |
| CSS3 | - | Stylowanie komponentów |

---

Projekt został zaprojektowany w sposób modułowy, z podziałem na reużywalne komponenty oraz czytelną strukturę folderów.