
# Проект Kittygram - Яндекс.Практикум

![Логотип Kittygram](https://kittygran.hopto.org/favicon.ico) - Ссылка на проект

Добро пожаловать в репозиторий проекта Kittygram! Этот проект призван создать платформу социальных медиа, основанную на обмене очаровательными фотографиями кошек. Независимо от того, являетесь ли вы любителем кошек или ищете способ поднять себе настроение, Kittygram создан для вас.

## [Kittygram](https://github.com/RedC0mrade/kittygram_final)

## Оглавление

- [О проекте](#о-проекте)
- [Основные особенности](#основные-особенности)
- [Отличия между Продакшн и Разработческими версиями](#отличия-между-продакшн-и-разработческими-версиями)
- [Использование](#использование)
  - [Локальное развертывание](#локальное-развертывание)
  - [Удаленное развертывание](#удаленное-развертывание)
- [Описание проекта](#описание-проекта)
- [Автор](#автор)
- [Используемые технологии](#используемые-технологии)

## О проекте

Kittygram - это проект, разработанный в рамках курса на Яндекс.Практикум. Он призван продемонстрировать новые технологии в веб-разработке и предоставить практический опыт создания полноценного веб-приложения.

## Основные особенности

- Аутентификация пользователей: Создавайте аккаунты или входите, чтобы получить доступ к платформе.
- Загрузка изображений: Делитесь фотографиями кошек с сообществом.
- Социальное взаимодействие: Ставьте лайки и оставляйте комментарии к записям других пользователей.
- Поиск и исследование: Находите и открывайте новые фотографии кошек.
- Готовность к продакшну: Развертывайте приложение для публичного использования.

## Отличия между Продакшн и Разработческими версиями

Продакшн версия Kittygram оптимизирована для публичного использования и предназначена для развертывания на живом сервере. Она включает улучшения, такие как минификация кода, меры безопасности и оптимизации для масштабируемости. Разработческая версия, с другой стороны, используется для локального тестирования и отладки. Она может включать дополнительное логирование и функции для более удобной разработки.

Используйте продакшн версию, когда вы готовы сделать приложение доступным для пользователей. Используйте разработческую версию во время активной разработки и тестирования.

## Использование

### Локальное развертывание

Чтобы развернуть приложение Kittygram локально, следуйте этим шагам:

1. Клонируйте репозиторий на вашем локальном компьютере:

   ```bash
   git clone https://github.com/https://github.com/RedC0mrade/kittygram_final
   cd kittygram
   py manage.py migrate
   python manage.py runserver

2. Установите зависимости для бэкенда и запустите сервер разработки:
   ```bash
   cd ../frontend
   npm install
   npm start
Откройте веб-браузер и перейдите по адресу http://127.0.0.1, чтобы взаимодействовать с локальной версией Kittygram.


### Удаленное развертывание
1. Подключитесь по SSH к удаленному серверу и перейдите в директорию проекта.
2. Чтобы развернуть Kittygram на удаленном сервере, выполните следующие шаги:

   Подготовьте окружение на удаленном сервере с необходимым программным обеспечением (Docker, Docker Compose и т.д.).

3. Клонируйте репозиторий на удаленном сервере:

   ```bash
   git clone https://github.com/ваше-имя/kittygram.git
   cd kittygram
4. Выполните скачивание и развертывание продакшн версии:
```bash
   docker-compose -f docker-compose.production.yml pull
   docker-compose -f docker-compose.production.yml up -d
```
Или выполните команду:
   ```bash
git push
```

### Описание проекта
Kittygram - это платформа социальных медиа, где пользователи могут делиться и взаимодействовать с фотографиями кошек. Пользователи могут создавать аккаунты, загружать изображения, отмечать окрас и год рождения котиков.

### Автор
Проект Kittygram был создан [RedC0mrade](https://github.com/redc0mrade).

### Используемые технологии
Проект использует ряд технологий, включая, но не ограничиваясь:

- Фронтенд: HTML, CSS, JavaScript, React
- Бэкенд: Python, Django, PostgreSQL
### Примечание 
Развертывание: Docker, Docker Compose
Пожалуйста, обратите внимание, что приведенный выше список представляет общий обзор, и фактические использованные технологии и инструменты могут различаться. Для получения более подробной информации ознакомьтесь с исходным кодом проекта и документацией.
