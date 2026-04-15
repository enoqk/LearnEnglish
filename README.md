# <img width="541" height="59" alt="image" src="https://github.com/user-attachments/assets/3fb7fc56-1b97-440e-afc5-e0dd33690c63" />


Интерактивно уеб приложение за учене на английски език по всички нива на CEFR (A1–C2), създадено за турнира по Интернет приложения на ВТУ „Св. св. Кирил и Методий" 2025.

🔗 **Live Demo:** https://enoqk.github.io/LearnEnglish

---

## Функции

- 36 урока по 6 нива (A1, A2, B1, B2, C1, C2)
- Тестове с над 110 въпроса и таймер
- Проследяване на прогрес с localStorage
- Мултиезичност — BG / EN превключване
- Dark mode
- Responsive дизайн (работи на мобилно)
- История на резултатите

## Технологии

- HTML5, CSS3, Vanilla JavaScript (без фреймуърк)
- Module Pattern — `ThemeModule`, `LangModule`, `NavModule`, `QuizModule`, `ProgressModule`, `CacheModule`
- localStorage за прогрес и кеширане
- CSS Custom Properties за теми

## Design Patterns

| Pattern | Използване |
|---|---|
| Module Pattern | Всеки логически модул е IIFE с публичен API |
| Facade | `NavModule` скрива сложната логика за routing |
| Observer | `ThemeModule` и `LangModule` актуализират UI при промяна |

## Структура

```
LearnEnglish/
└── index.html   # Цялото приложение — single-file SPA
```

## Стартиране

```
Отвори index.html в браузър — не са нужни сървър или зависимости.
```

## Автор

Енес Мюмюн Азиз
