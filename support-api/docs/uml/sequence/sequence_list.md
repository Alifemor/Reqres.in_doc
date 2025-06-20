# API Activity Diagrams

![activity_api](./activity_API.png)

# API Usecase Diagrams

![usecase_diagram](./usecase_diagram.png)

# API Sequence Diagrams

## 1. Получение списка пользователей

**Эндпоинт:** `GET /api/users?page=2`

![get_users](./get_users.png)

## 2. Получение пользователя по ID

**Эндпоинт:** `GET /api/users/{id}`

![get_users](./get_users{id}.png)

## 3. Создание пользователя (POST)

**Эндпоинт:** `POST /api/users`

![create_user](./create_user.png)

## 4. Обновление пользователя (PUT)

**Эндпоинт:** `PUT /api/users/{id}`

![replace_user](./replace_user.png)

## 5. Частичное обновление пользователя (PATCH)

**Эндпоинт:** `PATCH /api/users/{id}`

![update_user](./update_user.png)

## 6. Удаление пользователя (DELETE)

**Эндпоинт:** `DELETE /api/users/{id}`

![delete_user](./delete_user.png)
