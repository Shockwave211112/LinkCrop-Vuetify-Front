# LinkCrop
Frontend к API сервиса по сокращению ссылок.

Целью было попробовать создать какой-никакой фронт к завалявшемуся API и попробовать
сделать UI на современном стеке Vue 3 + TS + Vuetify с возможностью смены темы и
переключением языка, поиском и всем CRUD функционалом, а также рабочей OAuth Google
авторизацией.
>Vue.JS - 3.4.31
>
>Vuetify - 3.6.14
>
>Pinia - 2.2.8
>
>i18n - 11.0.1
>
>Vite - 5.4.10
>
>Vuelidate - 2.0.3
> 
>TypeScript
>
>Vue Router | ChartJS | MDIcons

## 💿 Запуск
Для запуска требуется API URL в .env.

* Вручную:
```bash
  npm install
```
```bash
  npm run dev
  vite
```
---
```bash
  npm run build
  vite build
```
```bash
  npm run preview
  vite preview
```
---
* Docker (preview):
```bash
cd docker
```
```bash
docker compose up -d
```

## 🖼️ Вид
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


