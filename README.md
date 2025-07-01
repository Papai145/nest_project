<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

<h1 align="center">Hotel Booking API</h1>

## Описание проекта

API для управления бронированием номеров в отеле с:

- Аутентификацией (JWT)
- Ролевой моделью (user/admin)
- Telegram-уведомлениями
- Аналитикой бронирований

## 🛠 Технологии

- **NestJS** + TypeScript
- **MongoDB** (Mongoose)
- **Telegram Bot API**
- JWT-авторизация

## ⚙️ Настройка

1. Создайте `.env` файл:

```env
SALT=ваш_соль
JWT_SECRET=ваш_секретный_ключ
TELEGRAM_TOKEN=токен_бота
CHAT_ID=id_чата
```
