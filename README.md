# API для фронтенд-проектов

Этот репозиторий содержит `db.json`-файлы для симуляции серверной части (REST API) разных проектов.

## 🔧 Технология
- JSON Server
- Node.js

## 📁 Структура
```bash
API/
├── food/
│ └── db.json ← API для FOOD_JS
├── .gitignore
├── package.json
├── README.md
```


## 🚀 Быстрый старт

1. Установить зависимости:
```bash
npm install
```
2. Запустить нужное API:

```bash
npm run start:food   # http://localhost:3001/menu
```
---
🌍 Деплой на Render

Можно задеплоить на Render.com, выбрав нужную папку и start-скрипт (например, npm run start:food)

1. Перейди на Render, и создай Web Service
2. Подключи репозиторий food-api
3. Укажи:

    * **Build command:** `npm install`, 
    * **Start command:** `npm run start:food`

4. После запуска Render даст тебе URL — замени им fetch в своём фронтенд-проекте, например:
```bash
    https://food-api.onrender.com/menu
```
5. Используй этот URL в своём фронтенд-проекте (вместо http://localhost:3001/menu) 


## ✅ Что дальше

Сохрани изменения и залей на GitHub:
```bash
   git add .
   git commit -m "Инициализация: базовая структура API"
   git push origin main
```
Теперь ты можешь развивать API, добавлять новые db.json для других проектов — всё в одном месте
