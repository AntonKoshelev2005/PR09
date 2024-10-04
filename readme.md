# Практическая работа 5
## ![pizza](https://kappa.lol/MCfLm)
Главная страница сайта
## Структура проекта
 Данный проект написан на языках **HTML**, **JavaScript**, **CSS**. *Изображения* имеют такие расширения как: ***.png***, ***.jpg***. :ambulance:

 | Название файла | Расширение|
 |--------------|:--------:|
 | index| .html |
 | main | .css  |
 | bootstrap.min| .css |
 | bootstrap.bundle.min| .js |
 | app| .js |


 index `html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Megasupersite</title>
    <link rel="stylesheet" href="lib/bootstrap.min.css">
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <!-- ПАНЕЛЬ НАВИГАЦИИ -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">
            <!-- TODO 3 -->
            <!-- <img src="img/logo.png" alt="" width="30" height="30"> -->
            Панель навигации
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Переключатель навигации">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
            <a class="nav-link active" aria-current="page" href="#">Меню</a>
            <a class="nav-link active" aria-current="page" href="#">Акции</a>
            <a class="nav-link active" aria-current="page" href="#">О нас</a>
            <a class="nav-link active" aria-current="page" href="#">Контакты</a>
        </div>
        </div>
    </div>
    </nav>

    <!-- ПИЦЦА -->
    <main class="container">
        <div class="row">
            <div class="col-md ss-pizza p-3 m-2 rounded">
                <article>
                    <header>Пеперони</header>
                    <img src="img/pizza1.jpg" class="img-thumbnail rounded float-start me-3">
                    <p>Острая разновидность салями итало-американского происхождения. Обычно делается из свинины.</p>
                    <button type="button" class="btn btn-outline-danger btn-lg">Заказать</button>
                </article>
            </div>
            <div class="col-md ss-pizza p-3 m-2 rounded">
                <article>
                    <header>Домашняя</header>
                    <img src="img/pizza6.jpg" class="img-thumbnail rounded float-start me-3">
                    <p>Домашняя пицца в духовке с колбасой классическая. Вкусная домашняя пицца с тонким воздушным тестом.</p>
                    <button type="button" class="btn btn-outline-danger btn-lg">Заказать</button>
                </article>
            </div>
        </div>
        <div class="row">
            <div class="col-md">
                <!-- TODO 1 -->
            </div>
            <div class="col-md">
                <!-- TODO 2 -->
            </div>
        </div>        

    </main>

    <script src="lib/bootstrap.bundle.min.js"></script>
    <script src="app.js"></script>
</body>
</html>
```
## Средства связи с разработчиком
~~[VK](https://vk.com/@parol.qwerty123)~~
