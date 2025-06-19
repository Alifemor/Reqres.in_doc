support-api/
│
├── README.md                # Описание проекта
├── openapi.yaml             # Swagger / OpenAPI спецификация API
│
├── docs/                    # Документация
│   ├── context.md           # Бизнес-контекст проекта
│   ├── requirements.md      # Требования: функциональные и нефункциональные
│   ├── use-cases.md         # Use Case сценарии
│   ├── uml/
│   │   ├── use-case.png     # UML Use Case диаграммы
│   │   ├── sequence.png     # UML Sequence диаграммы
│   │   └── component.png    # UML Component (если потребуется)
│   └── decisions.md         # Архитектурные/интеграционные решения (ADR)
│
├── examples/                # Примеры запросов/ответов
│   ├── create_ticket.json
│   ├── get_ticket.json
│   └── update_ticket.json
│
└──.gitignore
