# Платформа онлайн обучения
## Использование
Клонируйте репозиторий
```bash
git clone https://github.com/Sleepless-Artery/online-learning-platform-infra
```
Убедитесь, что соблюдены все требования и выполнены все шаги, описанные по следующим ссылкам:
- [online-learning-platform-auth-service](https://github.com/Sleepless-Artery/online-learning-platform-auth-service)
- [online-learning-platform-user-service](https://github.com/Sleepless-Artery/online-learning-platform-user-service)
- [online-learning-platform-course-service](https://github.com/Sleepless-Artery/online-learning-platform-course-service)
- [online-learning-platform-lesson-service](https://github.com/Sleepless-Artery/online-learning-platform-lesson-service)
- [online-learning-platform-enrollment-service](https://github.com/Sleepless-Artery/online-learning-platform-enrollment-service)
- [online-learning-platform-notification-service](https://github.com/Sleepless-Artery/online-learning-platform-notification-service)
- [online-learning-platform-gateway-service](https://github.com/Sleepless-Artery/online-learning-platform-gateway-service)
- [online-learning-platform-config-server](https://github.com/Sleepless-Artery/online-learning-platform-config-server)
- [online-learning-platform-configs](https://github.com/Sleepless-Artery/online-learning-platform-configs)
- [online-learning-platform-frontend](https://github.com/Sleepless-Artery/online-learning-platform-frontend)

Перейдите в каталог, в который склонировали настоящий репозиторий, и создайте файл .env и скопируйте в него код из .env.example. Замените значения переменных окружения на нужные, при необходимости измените пути к каталогам для сборки образов

В Docker CLI перейдите в каталог, в который склонировали настоящий репозиторий, и выполните одну из следующих команд:
```bash
docker-compose -f docker-compose.dev.yml up -d      # для запуска приложения в dev-среде
```
```bash
docker-compose -f docker-compose.prod.yml up -d     # для запуска приложения в prod-среде
```
Для остановки приложения воспользуйтесь одной из следующих команд:
```bash
docker-compose -f docker-compose.dev.yml down       # для отстановки приложения,запущенного в dev-среде
```
```bash
docker-compose -f docker-compose.prod.yml down      # для отстановки приложения,запущенного в prod-среде
```
## Требования
- Docker CLI
- аккаунт GitHub
## Технологии
- Docker
- Git
