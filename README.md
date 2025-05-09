# MedAPI - Medical Services API

## Опис проєкту

MedAPI - це високопродуктивний API для медичного обслуговування, написаний на Elixir та Erlang. Система надає інтерфейс для інтеграції медичних послуг у сторонні додатки.

**Технічний стек:**
- Мова програмування: Elixir, Erlang
- База даних: PostgreSQL
- Ліцензія: Apache License 2.0

## Документація

Проєкт пропонує кілька видів документації:
1. **Technical Specifications** - технічні вимоги та специфікації
2. **Production API Documentation** - документація API для розробників
3. **Business processes and specifications** - бізнес-процеси та вимоги

## Інструкція зі встановлення

1. Встановіть Elixir та Erlang
2. Встановіть PostgreSQL
3. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/ваш-логін/medapi.git
   ```
4. Встановіть залежності:
   ```bash
   mix deps.get
   ```
5. Налаштуйте базу даних у `config/dev.exs`
6. Запустіть сервер:
   ```bash
   mix phx.server
   ```

## Використання

API надає такі основні ендпоінти:

- `GET /api/patients` - отримання списку пацієнтів
- `POST /api/appointments` - створення нової записи
- `GET /api/records/:id` - отримання медичного запису

## Розробники

**Станіслав Панасюк** - головний розробник

## Ліцензія

Проєкт поширюється під ліцензією [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).