flowchart TD
    A[Пользователь] --> B[Web интерфейс]
    B --> C[Auth модуль]
    B --> D[Equipment модуль]
    B --> E[Requests модуль]
    B --> F[Reports модуль]
    C --> G[(SQLite база данных)]
    D --> G
    E --> G
    F --> G
