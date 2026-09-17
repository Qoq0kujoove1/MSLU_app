# МГЛУ.Мобайл

Мобильное приложение для студентов Московского государственного лингвистического университета.

## Возможности

- Расписание занятий (день/неделя/месяц)
- Успеваемость и средний балл
- Профиль студента
- Локальное кэширование для быстрого доступа

## Технологии

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

## Лицензия

MIT License — см. [LICENSE](LICENSE)

## Команда

- Product Designer & Team Lead - a1qjv
- Backend Developer
- Frontend Developer
- DevOps & Security Engineer
