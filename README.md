#
<image src="image/banner.jpg" alt="Banner about me">

## project-root/ логическая структура репозитория  
`│`  
`├#cypress/`  
`│`  
`├── tests/`  
`│   ├── ui/                   # UI-тесты`  
`│   ├── e2e/                  # End-to-End тесты`  
`│   ├── api/                  # API-тесты`   
`│`  
`├── pages/                    # Реализация Page Object'ов (РОМ)`  
`│   ├── LoginPage.js          # Пример страницы (страница логина)`  
`│   ├── HomePage.js           # Главная страница`  
`│   ├── ProductPage.js        # Страница продукта`  
`│   └── ...                   # Другие страницы`  
`│`  
`├── support/                  # Вспомогательные функции`  
`│   ├── commands.js           # Кастомные команды`  
`│   ├── utils.js              # Общие утилиты (генерация данных)`  
`│   └── interceptors.js       # Работа с перехватами API (если нужно)`  
`│`  
`├── fixtures/                 # Тестовые данные`  
`│   ├── users.json            # JSON-файл с тестовыми пользователями`  
`│   ├── products.json         # JSON-файл с товарами`  
`│   └── ...                   # Другие тестовые данные`  
`│`  
`├#playwright/`  
`│`  
`├── tests/`  
`│   ├── ui/                   # UI-тесты`  
`│   ├── e2e/                  # End-to-End тесты`  
`│   ├── api/                  # API-тесты`  
`│`  
`├── pages/                    # Реализация Page Object'ов (РОМ)`  
`│   ├── LoginPage.js          # Пример страницы (страница логина)`  
`│   ├── HomePage.js           # Главная страница`  
`│   ├── ProductPage.js        # Страница продукта`  
`│   └── ...                   # Другие страницы`  
`│`  
`├── support/                  # Вспомогательные функции`  
`│   ├── commands.js           # Кастомные команды`  
`│   ├── utils.js              # Общие утилиты (генерация данных)`  
`│   └── interceptors.js       # Работа с перехватами API (если нужно)`  
`│`  
`├── fixtures/                 # Тестовые данные`  
`│   ├── users.json            # JSON-файл с тестовыми пользователями`  
`│   ├── products.json         # JSON-файл с товарами`  
`│   └── ...                   # Другие тестовые данные`  
`│`   
`├#config/                     # Конфигурации`  
`│   ├── cypress.config.js     # Конфиг для Cypress`  
`│   ├── playwright.config.js  # Конфиг для Playwright`  
`│   └── jenkinsfile           # Jenkins pipeline файл`  
`│`  
`│#image/                      # Изображения`  
`│`  
`├#README.md                   # Описание проекта`  
`│`  