# API Sequence Diagrams

Ниже представлены последовательные диаграммы взаимодействия для каждого эндпоинта.

## 1. Получение списка пользователей

**Эндпоинт:** `GET /api/users?page=2`

![get-users](./get_users.png)

## 2. Получение пользователя по ID

**Эндпоинт:** `GET /api/users/{id}`

![get-users](./get_users{id}.png)

## 3. Создание пользователя (POST)

**Эндпоинт:** `POST /api/users`

![get-users](./create_user.png)

## 4. Обновление пользователя (PUT)

**Эндпоинт:** `PUT /api/users/{id}`

![get-users](./replace_user.png)

## 5. Частичное обновление пользователя (PATCH)

**Эндпоинт:** `PATCH /api/users/{id}`

![get-users](./update_user.png)

## 6. Удаление пользователя (DELETE)

**Эндпоинт:** `DELETE /api/users/{id}`

![get-users](./delete_user.png)
