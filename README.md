# Установка и запуск проекта
1. Установить Node JS <a href="">тут</a> скачать установочный файл Вашей системы. Проблем возникнуть не должно.
2. Задаем переменную среды
В поиске Windows вводите "изменение переменных среды" и добавляете: NODE_ENV = development
http://joxi.ru/krDgMojfEXZQqA
3. Форкаем текущий репозиторий
http://joxi.ru/l2ZKkoltwQNK4A
Тем самым репозиторий клониется в Ваш аккаунт
4. Клонируем репозиторий на рабочую машину
4.1. В любой удобно
5. Запускаем из корня npm i и скачиваем зависимости
6. Создаем в корне файл .env и добавляем туда `PORT = 3000`
7. Далее запускаем
- npm run start
- gulp watch
- gulp browser-sync