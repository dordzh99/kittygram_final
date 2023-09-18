Описание проекта: На сайте portal-dexerto.sytes.net пользователи могут:

    создавать задачи;
    менять задачу в зависимости от условий
    давать полное описание задаче;
    отмечать ее выполненной;
    удалять выполненные задачи.
 
kittygram-opiev.ddns.net представляет собой социальную сеть, предназначенную для обмена фотографиями любимых питомцев.

В проекте были использованы следующие технологии:

    ОС Linux Ubuntu;
    Docker Desktop;
    python;
    django;
    веб-сервер Nginx (выступает также в роли обратного прокси-сервера);
    WSGI-сервер Gunicorn;
    редактор nano.

Информация по установке:

    клонируем репозиторий: git clone https://github.com/dordzh99/kittygram_final.git
    переходим в директорию kittygram_final: cd kittygram_final;
    cоздайте файл .env в корневой директории проекта и заполните значениями POSTGRES_USER, POSTGRES_PASSWORD, POSTGRES_DB, PORT, HOST, SECRET_KEY
    запушить проект на гитхаб
