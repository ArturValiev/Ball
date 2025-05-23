# 🎮 Ball — Pet-проект на Unity

Прототип игры, разработанный в рамках изучения архитектурных подходов и современных инструментов Unity.

## 🚀 Описание проекта

Игрок управляет мячом, который перемещается по уровню, взаимодействует с врагами и собирает монеты. После сбора всех монет активируется выход на следующий уровень.

Проект разработан с упором на:
- Чистую архитектуру
- Слабую связность компонентов
- Простоту расширения и поддержки

## ⚙️ Технологии и инструменты

- **Unity** (2022.3+)
- **Zenject** — внедрение зависимостей
- **UniTask** — асинхронность без лишних аллокаций
- **UniRx (Reactive Extensions)** — реактивный подход, основа MVVM-структуры
- **JSON** — для конфигурации игровых объектов
- **Object Pooling** — переиспользование объектов для оптимизации
- **Custom Signals** — сигнальная архитектура без EventBus

## 📦 Основной функционал

- Управление мячом с ограничением скорости
- Враги двух типов: патрулирующий "ёж" и неподвижные "шипы"
- Система сбора монет
- Условия завершения уровня
- Загрузка параметров уровня из JSON
- Гибкое подключение уровней как префабы
- Минимальные зависимости между модулями (через интерфейсы)
