# TaskManager

**TaskManager** — это приложение на C# (WinForms), предназначенное для управления задачами между руководителями и подчинёнными. Проект реализован с акцентом на простоту интерфейса, безопасность авторизации и минимализм в управлении задачами.

## 🚀 Возможности

- Регистрация и авторизация с валидацией логина и пароля
- Разделение прав пользователей по ролям: **руководитель** / **подчинённый**
- Руководитель может:
  - создавать задачи с указанием исполнителя, приоритета и описания
  - просматривать все созданные задачи
  - фильтровать задачи по статусу, приоритету и исполнителю
  - удалять задачи
- Подчинённый может:
  - видеть только свои задачи
  - изменять их статус на «Выполнено», «Провалено» или «Отказано»
  - фильтровать задачи по приоритету и статусу
- Современный минималистичный интерфейс с использованием библиотеки **MaterialSkin**
- Работа с базой данных PostgreSQL
- Безопасное хранение паролей (SHA-256)
- Обработка ошибок с выводом понятных сообщений

## 🛠 Технологии

- **Язык:** C#
- **Платформа:** .NET / Windows Forms
- **Интерфейс:** MaterialSkin
- **База данных:** PostgreSQL
- **Хеширование:** SHA-256

## ⚙️ Требования

- Windows 10/11
- Visual Studio 2022 / 2019
- PostgreSQL (локально или удалённо)
- .NET Framework (версии для WinForms)

## 📦 Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-username/TaskManager.git
