Система управления проектами с использованием Fast Api
   - Модели: Пользователи, Проекты, Задачи
   - Идея проекта: Создание системы для управления проектами с возможностью создания новых проектов, назначения задач, отслеживания прогресса и авторизации пользователей.


- запуск docker compose up
- прохождение flake8 + mypy в соответствии с конфигурациями проекта
- Кеширование всего, что возможно закешировать через redis
- Orm:  sqlalchemy2.0
- Migration: alembic
- Тесты - pytest + mock на redis и rollback транзакций фикстур вместо удаления.
- Минимальные данные при разворачивании проекта (фикстуры)
- Метрики: 
  - На кол-во полученных запросов в разрезе каждой ручки.
  - На кол-во ошибок по каждой ручке
  - На кол-во отправленных запросов
  - Время выполнения каждой ручки в среднем (гистограмма)
  -Время выполнения всех интеграционных методов (запросы в бд, редис и тп (гистограмма)
- Валидация входящих данных (pydantic)
- Настройки в env
- poetry как сборщик пакетов

 
