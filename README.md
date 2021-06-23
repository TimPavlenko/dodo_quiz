# dodo_quiz
en:
This project was written for the olimpiad for schoolchildren of St. Petersburg State University on technology entrepreneurship, I wrote the server logic, callback and work with the template engine. Maxim (https://github.com/Uknown-creator) developed the design, laid out templates and connected css to them.
This is a web application launched on localhost:8000 via uvicorn, on the start page you can set a condition that emulates the absence of pizza components in stock.
Questions are made in quiz format. Questions with missing products are not displayed. The results are written to config.ini, but are cleared when the application is restarted. This app is a prototype, so after completing the quiz, the Dodo Pizza website opens.

ru:
Этот проект был написан для олимпиады школьников СПбГУ по технологическому предпринимательству, я написал серверную логику, обратный вызов и работу с шаблонизатором. Максим (https://github.com/Uknown-creator) разработал дизайн, сверстал шаблоны и подключил к ним css.
Это вэб приложение запускаемое на localhost:8000 через uvicorn. На стартовой странице можно настроить условие, эмулирующее отсутствие компонентов для пиццы на складе.
Вопросы сделаны в формате квиза. Вопросы в которых есть отсутствующие(по условию) продукты не выводятся. Результаты записываются в config.ini, но стираются при перезапуске приложения. Так как это приложение - прототип, после завершения квиза открывается сайт Dodo Pizza.
