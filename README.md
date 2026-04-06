# LexiMemo

Веб-приложение для изучения и запоминания иностранных слов по карточкам с алгоритмом интервальных повторений.

## Что реализовано

- Регистрация, логин и logout через Auth.js Credentials
- Защищенные пользовательские страницы
- CRUD колод
- CRUD карточек внутри колод
- Учебная сессия с оценками `Сложно / Нормально / Легко`
- Алгоритм интервального повторения
- `ReviewHistory`, streak и пользовательская статистика
- Achievements с unlock-логикой на сервере
- AI-генерация карточек: `prompt -> preview -> confirm save`
- Browser TTS для озвучки слов
- Installable PWA: manifest, service worker, иконки, install prompt

## Стек

- Next.js 16, App Router, React 19
- TypeScript
- Tailwind CSS v4
- Prisma ORM
- PostgreSQL
- NextAuth / Auth.js
- Zod
