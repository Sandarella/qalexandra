# 
<img src="img/banner.jpeg" alt="Banner about me">

project-root/структура репозитория
│
├── tests/
│   ├── ui/              # UI-тесты
│   ├── e2e/             # End-to-End тесты
│   ├── api/             # API-тесты 
│
├── pages/               # Реализация Page Object'ов (РОМ)
│   ├── LoginPage.js     # Пример страницы (страница логина)
│   ├── HomePage.js      # Главная страница
│   ├── ProductPage.js   # Страница продукта
│   └── ...              # Другие страницы
│
├── support/             # Вспомогательные функции
│   ├── commands.js      # Кастомные команды
│   ├── utils.js         # Общие утилиты (генерация данных)
│   └── interceptors.js  # Работа с перехватами (если нужно)
│
├── fixtures/            # Тестовые данные
│   ├── users.json       # JSON-файл с тестовыми пользователями
│   ├── products.json    # JSON-файл с товарами
│   └── ...              # Другие тестовые данные
│
├── config/              # Конфигурации
│   ├── cypress.config.js # Конфиг для Cypress (в папке Cypress)
│   ├── playwright.config.js # Конфиг для Playwright (в папке Playwright)
│   └── ...              # Другие конфигурационные файлы
│
├── reports/             # Отчеты о тестировании
│   ├── html/            # HTML-отчеты (Allure)
│   └── logs/            # Логи тестов
│
└── README.md            # Описание проекта
