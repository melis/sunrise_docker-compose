**ТЗ Pokemon Web App**

Здес только **docker-compose.yml** для запуска и настройки сервисов. 
**nginx.conf** для настройки прокси сервиса.
Исходники тут: https://github.com/melis/sun

По задачи надо было с фронта обращатся на базу, но я решил написат back(api) на node и обернуть все это на docker контейнеры и запускат через docker-compose. Создал proxy nginx:alpine и пробросил внутр настройки прокси. 

Frontend
**docker image: melishold/sun_front**

Backend Api
**docker image:meliszhold/sun_api**

Команда для запуска: **docker-compose up**

После запуска перейдите на: **http://localhost/**

Исходники тут: **https://github.com/melis/sun**


**Pokemon Web App**
Create web application with the stack of technologies: ➔ React
➔ Redux + redux-thunk
➔ Axios
➔ Firebase realtime database or MongoDB

Objective
Create UI for Pokemon cards with form to add new pokemons like this Example. You are free to use any library, CSS Framework etc.
Main goals:

1. Create database and fill with pokemon data
2. Fetch data from database and render in web app 3. Create list of favorite pokemons
3. Heart icon adds pokemon to favorite list
4. Trash icon removes pokemon from database
5. Create a form to add new pokemon to the database, then refresh data in the web application.(See example)
6. Record 1-minute video, where you present your work, then send it per email: hr.sunriseitcompany@gmail.com
