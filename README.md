# Progressive Web App with Angular

This is sample PWA (Progressive Web App) application with Angular 6. \
Check out our blog if you want to learn more:

## Repo info
* ```enrollment-reporter-app``` - Angular 6 PWA application (service workers, push notifications enable/send, save photos in localStorage, save API request in cache)
* ```enrollment-reporter-server``` - Node.js + Express + in-memory-database (save/get enrollments, save push subscriber, send notifications to all subscribers)

## Run frontend 
In enrollment-reporter-app_:
```
npm install
npm run build
```
**Info:** \
With `ng serve` Service Workers doesn't work, so if you run this project first time, you must install mini HTTP server:
```
npm install -g http-server
```

## Run backend 
In enrollment-reporter-server_:
```
npm install
npm start
```