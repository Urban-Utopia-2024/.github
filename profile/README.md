# __Urban Utopia 2024__ 🌆
https://urban-utopia-2024.webtm.ru/

Ваш самый дружелюбный и красивый web-сервис по взаимодейтсвию с муниципальными службами*

<sup>_\* по версии нашей команды_</sup>

___

### ВВЕДЕНИЕ

Urban Utopia 2024 - это результат двухдневного хакатона "Урбатон 2023: навигатор чистоты" - веб-приложение, которое поможет гражданм Екатеринбурга и других городов легко узнавать все важные новости города, а также в реальном времени отслеживать результаты деятельности комунальных служб. Пользователям предлагается современный и практичный интерфейс для просмотра новостейи участия в развитии города, управления заявками муниципальным учредениям.

___

### ТЕХНОЛОГИИ

Cleanpro разработан с использованием следующих технологий:

- [Python] (v.3.11) - целевой язык программирования backend
- [Django] (v.4.2) - высокоуровневый веб-фреймворк
- [Django REST framework] (v.3.14) - инструмент для создания Web API
- [PostgreSQL] (v.13.10) - объектно-реляционная база данных
- [Celery] (v.5.3) - распределенная очередь задач
- [Redis] (v.5.0) - резидентная система управления NoSQL базами данных, брокер сообщений Celery
- [PyJWT] (v.2.8) - плагин, предоставляющий JSON Web Token аутентификацию для Django REST Framework, разработанную в соответствии со стандартом RFC 7519
- [Gunicorn] (v.21.2) - Python WSGI HTTP-сервер для UNIX
- [Nginx] - HTTP-сервер и обратный прокси-сервер
- [Docker] (v.24.0) - инструмент для автоматизирования процессов разработки, доставки и запуска приложений в контейнерах

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Celery](https://a11ybadges.com/badge?logo=celery)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![PyJWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

- [JavaScript] (v.1.8) - целевой язык программирования frontend
- [React] (v.18.2) - библиотека JavaScript для разработки пользовательских интерфейсов (UI) веб-приложений
- [Redux] (v.8.1) - библиотека  управления состоянием JavaScript приложений
- [TypeScript] - язык программирования для веб-разработки, основанный на JavaScript

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

___

### РАЗВЕРТКА

✅ Создать корневую папку с проектом (предлагается "urban_utopia_2024") и перейти в неё

```
mkdir urban_utopia_2024
cd urban_utopia_2024
```

✅ Загрузить актуальные версии frontend и backend

```
git clone git@github.com:Urban-Utopia-2024/backend.git
git clone git@github.com:Urban-Utopia-2024/frontend.git
```

✅ Перейти в папку backend

```
cd backend/backend
```

✅ Создать файл переменных окружения из примера

```
cp .env.example .env
```

✅ Изменить переменные окружения (если необходимо)
```
(на примере редактора Nano)
nano .env
```

✅ Перейти в корневую папку backend
```
cd ..
```

✅ Запустить Docker (убедитесь, что `docker daemon` запущен в системе!)

```
docker-compose up --build
```

✅ Проверить доступность проекта на `localhost:8000`

```
http://localhost:8000/
http://localhost:8000/api/v1/docs/swagger/
```

___

### ЛИЦЕНЗИЯ

MIT

**Ура, халява!**

___

### КОМАНДА BACKEND

🦸🏻‍♂️ [Кирилл](<https://github.com/TheSuncatcher222/>)

### КОМАНДА FRONTEND

🧝‍♀️[Виктория](<https://github.com/ElPastel/>)

👩‍🚀[Грегорий](<https://github.com/grinmorg/>)

### КОМАНДА UX/UI

👩‍🎨 [Анна](<https://www.behance.net/annadoronina1/>)

👩‍🎤 [Евгения](<https://www.behance.net/dyomina/>)

[Python]: <https://www.python.org/>
[Django]: <https://www.djangoproject.com/>
[Django REST framework]: <https://www.django-rest-framework.org/>
[PostgreSQL]: <https://www.postgresql.org/>
[Celery]: <https://docs.celeryq.dev/en/stable/>
[Redis]: <https://redis.io/>
[PyJWT]: <https://pyjwt.readthedocs.io/en/latest/>
[Gunicorn]: <https://gunicorn.org/>
[Nginx]: <https://nginx.org/en/>
[Docker]: <https://www.docker.com/>

[JavaScript]: <https://www.javascript.com/>
[React]: <https://react.dev/>
[React Router]: <https://reactrouter.com/en/main/>
[Vite]: <https://vitejs.dev/>
[Redux]: <https://redux.js.org/>
[TypeScript]: <https://www.typescriptlang.org/>
