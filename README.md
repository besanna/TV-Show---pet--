# Проект: Информационная система для эффективной обработки заявок на участие в телешоу

## Описание проекта
Добро пожаловать в мой пет-проект — **Информационная система для эффективной обработки заявок на участие в телешоу**, разработанный как практическое решение для автоматизации процесса приема, проверки, классификации загадок и учета результатов игры. Эта работа демонстрирует мои навыки в проектировании сложных систем, включая REST API, асинхронное взаимодействие, модели данных и пользовательские интерфейсы. Система разработана с учетом реальных бизнес-требований и подходит для использования в телевизионной среде с прямым эфиром.

Цель проекта — создать удобный и надежный инструмент для телезрителей, операторов, специалистов по загадкам и ведущих, обеспечивающий плавную работу телешоу.

---

## Основные возможности
- **Регистрация телезрителей**: Простая форма с обязательным согласием на обработку персональных данных.
- **Прием и обработка заявок**: Автоматизированная система для подачи и проверки заявок с загадками.
- **Классификация загадок**: Оценка сложности (легкая, средняя, сложная, неизвестная) специалистами.
- **Отбор загадок для игры**: Автоматический выбор 13 загадок для еженедельного эфира.
- **Проведение игры**: Поддержка ведения счета и определение победителя в прямом эфире.
- **Асинхронные уведомления**: Рассылка статусов заявок и результатов раундов через RabbitMQ.
- **Безопасность данных**: Соответствие стандартам защиты персональных данных.

---

## Технологии и инструменты
- **API**: RESTful API (OpenAPI 3.0.0) для управления ресурсами.
- **Асинхронность**: RabbitMQ для уведомлений (AsyncAPI 2.3.0).
- **Дизайн и прототипирование**: Низкодетализированные макеты интерфейсов.
- **Инструменты моделирования**: UML (Use Case, State, Activity, Sequence диаграммы), BPMN.

---

## Документация
Проект сопровождается подробной документацией, которая охватывает все аспекты разработки:
- **Цели проекта**: Автоматизация процесса за 6 месяцев, стабильность в реальном времени, обучение сотрудников.
- **Концепция**: Интеграция с телевизионным эфиром, уникальная классификация загадок.
- **Требования**: Функциональные (Use Case) и нефункциональные (безопасность, производительность).
- **UML-диаграммы**: 
  - Use Case (взаимодействие ролей).
  - State Diagrams (состояния заявок и загадок).
  - Activity Diagram (выбор загадок для игры).
  - Sequence Diagram (процесс регистрации телезрителя).
- **BPMN-диаграммы**: Четыре бизнес-процесса (прием заявок, классификация, отбор, оповещение).
- **REST API**: Спецификация OpenAPI 3.0.0 с примерами JSON.
- **Асинхронное взаимодействие**: AsyncAPI 2.3.0 с RabbitMQ.
- **Модели данных**: Концептуальная и логическая ERD с описанием связей и ограничений.

Все диаграммы доступны в папке `/docs`.

---

## Контакты
- **Автор**: Беспалова Анна
- **Telegram**: https://t.me/bespasus
- **Email**: besanna114@gmail.com

Готова к сотрудничеству и стажировке!
