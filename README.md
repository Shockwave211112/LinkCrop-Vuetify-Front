# 🖼️ LinkCrop Frontend

[![Vue](https://img.shields.io/badge/Vue.js-3.4.31-42b883.svg)](https://vuejs.org/)
[![Vuetify](https://img.shields.io/badge/Vuetify-3.6.14-1867c0.svg)](https://vuetifyjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6.svg)](https://www.typescriptlang.org/)
[![Docker](https://img.shields.io/badge/Docker-Supported-blue.svg)](https://www.docker.com/)

Современный фронтенд для сервиса сокращения ссылок. Проект создан в рамках изучения Vue 3 + TypeScript + Vuetify.

## 📌 О проекте

Этот проект — фронтенд-часть [LinkCrop](https://github.com/Shockwave211112/LinkCrop-Laravel-API). Реализован на стеке Vue 3 Composition API с поддержкой TypeScript. Интерфейс построен на Vuetify с возможностью переключения темы (светлая/тёмная) и локализации.

### 🌟 Основные возможности
*   🔐 **OAuth аутентификация** через Google (&Facebook)
*   🔗 **Полный CRUD** для управления ссылками и группами
*   🎨 **Смена темы** (светлая/тёмная)
*   🌍 **Локализация** (i18n)
*   📊 **Графики статистики** переходов (Chart.js)
*   👑 **Панель администратора** для просмотра и редактирования всех данных

## 🛠️ Технологический стек

| Технология | Версия  | Назначение                    |
| :--------- | :------ | :---------------------------- |
| Vue        | 3.4.31  | Основной фреймворк            |
| Vuetify    | 3.6.14  | Material Design компоненты    |
| TypeScript | ~5.x    | Статическая типизация         |
| Pinia      | 2.2.8   | Менеджер состояния            |
| Vue Router | ^4      | Маршрутизация                 |
| Vuelidate  | 2.0.3   | Валидация форм                |
| i18n       | 11.0.1  | Интернационализация           |
| Chart.js   | ^4      | Графики статистики            |
| Vite       | 5.4.10  | Сборка и dev-сервер           |

## 🚀 Быстрый старт

### Предварительные требования
*   npm / yarn / pnpm
*   Docker (опционально)
*   Запущенный [бэкенд API](https://github.com/Shockwave211112/LinkCrop-Laravel-API)

### Локальный запуск вручную
Изначально нацелен на работу через Docker
1.  Склонировать репозиторий.
2.  Создать .env, указав URL API:
    ```
    VITE_API_URL=http://localhost:8000
    ```
3.  Запустить Docker:
    ```
    cd docker
    docker compose up -d
    ```

#### Либо запуск без Docker:
1.  Установить зависимости
    ```
    npm install
    ```
2.  Создать .env, указав URL API:
    ```
    VITE_API_URL=http://localhost:8000
    ```
3.  Запустить dev/собрать и запустить прод:
    ```
    npm run dev
    /
    npm run build
    npm run preview
    ```

## 🖼️ Интерфейс
### Стартовая страница
![Стартовая страница dark-eng](https://github.com/user-attachments/assets/5ebd96ff-36e2-444b-9bd0-a7c7352261db)
![Стартовая страница light-rus](https://github.com/user-attachments/assets/523c41a8-d87d-42b6-a4f3-7d8249ac84b9)
![Стартовая страница auth](https://github.com/user-attachments/assets/6f991d2d-925b-4855-bb49-368859586acc)

### Профиль
![Профиль, редактирование ссылки dark](https://github.com/user-attachments/assets/6a67448b-627d-4882-af13-9cb184ec5a68)
![Профиль, редактирование ссылки light](https://github.com/user-attachments/assets/7f4cf62d-3983-4aa1-9cbb-6c14b0ac7271)
![Профиль, статистика ссылки](https://github.com/user-attachments/assets/26d7e0d5-f5e5-44e2-ad1e-deb42908e1c9)


### Создание ссылки/группы
![Профиль, создание ссылки](https://github.com/user-attachments/assets/b4c1919f-ec23-4431-91a4-f6a5b92a8b80)
![Профиль, создание группы](https://github.com/user-attachments/assets/bfc47678-2664-4d2a-9d2b-86a1115c3491)

### Настройки пользователя
![Профиль, страница настроек юзера](https://github.com/user-attachments/assets/10b7f7fa-54f9-49cc-8a78-4952d06d8bb4)

### Панель администратора с просмотром всего и вся
![Админ панель, редактирование юзера](https://github.com/user-attachments/assets/0a00a16a-a036-4942-9f72-e7afcad9ab75)
![Админ панель, редактирование ссылки](https://github.com/user-attachments/assets/b3fb6f3a-b947-46d8-8252-b9e9c8e9b049)
![Админ панель, редактирование прав](https://github.com/user-attachments/assets/af0f29d2-113b-4aa2-8047-2a79feebb70e)

### Другие окна на стартовой странице
![Всплывающее меню регистрации](https://github.com/user-attachments/assets/55065eb8-507d-43e6-8b9c-4381e7e0a434)
![Всплывающее меню сброса пароля](https://github.com/user-attachments/assets/34b8b546-2325-4022-9755-c284d0c6a3f1)


