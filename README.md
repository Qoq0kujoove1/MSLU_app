# MSLU App
Мобильное приложение для студентов Московского государственного лингвистического университета.


<img width="1920" height="1080" alt="D" src="https://github.com/user-attachments/assets/e76adb85-e3ab-4b86-a610-b1ea924c5e11" />

## Описание
### Основные возможности
- Расписание занятий (день/неделя/месяц)
- Успеваемость
- Профиль студента
- Локальное кэширование для быстрого доступа
### 1. Как работает авторизация клиента?
<img width="1920" height="1080" alt="D" src="https://github.com/user-attachments/assets/fe04fc1a-3785-44a6-bbf4-f59649d76861" />
### 2. Возможности домашнего экрана
### 3. Возможности профиля студента
### 4. Возможности расписания занятий
### 5. Возможности успеваемости

### Технологии

- **Frontend:** Flutter, BLoC, SQLite
- **Backend:** Python/Node.js, PostgreSQL, JWT
- **Infra:** Docker, Docker Compose, Nginx

## Быстрый старт

### Требования

- Docker & Docker Compose
- Flutter SDK (для клиента)

### Запуск backend

\`\`\`bash
cd infra
cp .env.example .env
docker-compose up -d
\`\`\`

### Запуск клиента

\`\`\`bash
cd client
flutter pub get
flutter run
\`\`\`

## Документация
- [API Reference](docs/api/)
- [Архитектура](docs/architecture/)
- 
## Лицензия

MIT License — см. [LICENSE](LICENSE)

## Команда

- Product Designer & Team Lead - a1qjv
- Backend Developer
- Frontend Developer
- DevOps & Security Engineer
