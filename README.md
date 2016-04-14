# PhotoService

This is a Flask project of service for photography schools. It's aim is to help them to teach students of photography.

#Установка

Предупреждение: должен быть установлен Git (требуется как для серверной, так и для клиентской части).

Серверная часть

1. Git Bash: клонируем репозиторий в нужную папку: git clone <ссылка на репозиторий>
2. В командной строке системы заходим в папку созданного проекта.
3. Если еще не установлена python-библиотека virtualenv, то устанавливаем ее: pip install virtualenv
4. Набираем команду virtualenv flask. Она инициализирует нам нашу виртуальную среду.
5. Активируем виртуальную среду командой flask\Scripts\activate
6. Устанавливаем необходимые для работы приложения зависимости: pip install -r requirements.txt

Клиентская часть

8. Скачиваем и устанавливаем NodeJS по ссылке (если он еще не установлен): https://nodejs.org
9. Чтобы убедиться в корректной установке, в командной строке прописываем node -v, затем npm -v
10. Устанавливаем Bower (если он еще не установлен): npm install -g bower
11. В командной строке заходим в папку app/static
12. Устанавливаем AngularJS: bower install angular
13. Устанавливаем Bootstrap: bower install bootstrap
14. Возвращаемся в корневую директорию проекта и запускаем сервер: python run.py
15. Открываем браузер и переходим на localhost:5000/index
