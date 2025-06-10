# React + TypeScript + Vite

# React + TypeScript + Vite

# 🛍 Online Store Frontend

Це фронтенд-частина командного проєкту Online Store, створеного з використанням React, Vite, TypeScript та Tailwind CSS.

---

## 🚀 Стек технологій

- React — бібліотека для побудови UI
- Vite — сучасний збирач (bundler)
- TypeScript — типізація
- Tailwind CSS — утилітарний CSS-фреймворк
- HTML — базова розмітка

---

## 🧩 Структура гілок

| Гілка         | Призначення                            |
|---------------|----------------------------------------|
| main        | Стабільна версія (деплой/реліз)        |
| dev         | Основна для поточної розробки          |
| feature/*   | Для реалізації нових компонентів/фіч   |
| bugfix/*    | Для виправлення помилок                |
| hotfix/*    | Для термінових виправлень у main     |

---

## 👥 Як приєднатись до проєкту

### 🔹 1. Склонуй репозиторій:

```bash
git clone https://github.com/Halyna79/online-store.git
cd online-store
npm install

GitHub (https://github.com/Halyna79/online-store.git)
GitHub - Halyna79/online-store: Frontend for team project - online store
Frontend for team project - online store. Contribute to Halyna79/online-store development by creating an account on GitHub.

⸻

🔹 2. Створи нову гілку для своєї задачі:

git checkout -b feature/назва


⸻

🔹 3. Додай, закоміть і запуш зміни:

git add .
git commit -m "Додано компонент ..."
git push -u origin feature/назва


⸻

🔹 4. Створи Pull Request у GitHub:
 • PR має бути в гілку dev
 • Назви: feature: Назва компонента
 • Додай опис, що саме зроблено


⸻

📦 Команди для запуску

npm install        # Встановити залежності
npm run dev        # Запуск проєкту
npm run build      # Збірка


⸻

📝 Правила коду
 • Назви гілок: feature/назва, bugfix/назва
 • Один PR = одна задача
 • Зміни тільки в своїй гілці
 • Pull Request тільки в dev, не в main

⸻

📁 Структура проєкту

online-store/
│
├── public/         # Статичні файли
├── src/            # Компоненти, стилі, логіка
│   ├── components/ # UI-компоненти
│   ├── pages/      # Сторінки
│   └── styles/     # Tailwind CSS / глобальні стилі
├── index.html
├── package.json
└── tailwind.config.js