# practika

Автор: Нестеренко ИПО-21.23

# Лекции

## Лекция №1

### Web

#### Базовый сценарий работы веб-приложения:

Пользователь вводит URL.

Браузер загружает HTML-документ.

Браузер парсит HTML и загружает дополнительные ресурсы.

Браузер рендерит страницу.


#### URL (Unified Resource Locator):

http — протокол.

mi-ami.ru — доменное имя.

8080 — TCP-порт.

/profile/account.html — путь к документу.

?gender=male&age=13 — query-параметры.

#comments — якорь.

#### Документы

Документ - тело ответа HTTP-запроса

MIME-типы: text/html, text/css, text/javascript, image/png, video/mp4 и др.

*Документы делятся на статистические и динамические*

Статические: Файлы на дисках сервера с постоянным адресом.

Динамические: Создаются при каждом запросе, зависят от внешних факторов (пользователь, время и т. д.), адресможет меняться.

### HTTP

Основные протоколы: TCP, UDP, HTTP, FTP, SSH.

Структура HTTP-запроса: Метод (GET, POST, PUT, DELETE и др.), URL, Заголовки, Тело (может отсутствовать

Структура HTTP-ответа: Тело, Заголовки.

*Статус ответа:*

1xx — информационные.

2xx — успешные.

3xx — перенаправления.

4xx — ошибки клиента.

5xx — ошибки сервера.

### HTML

*теги HTML:*

html - обёртка.

head - заголовок.

body - тело.

h1–h6 - Определяет HTML-заголовки (от первого до шестого уровня).

p - Определяет параграф.

br - Устанавливает перевод строки.

hr - Создаёт горизонтальную линию или определяет тематическое разделение контента на странице.

a - Используется для создания гиперссылок, позволяющих переходить с одной страницы на другую.

img - Используется для вставки изображений.

### CSS

*Стили:*

width, height — размеры.

margin, padding — отступы.

display — тип отображения.

color — цвет текста.

background — фон.

font — шрифт.

text-align — выравнивание текста.

*Селекторы:*

Универсальный: *.

По тегу: p.

По классу: .btn.

По ID: #userpic.

Контекстные: div.article a.

Дочерние: a > img.

Соседние: h2.sic + p.

Группировка: h1, h2.

*Стили наследуются от родительских элементов.*

Приоритеты: !important > ID > класс > тег.

### JavaScript

*Способы подключения:*

Внешний файл: <script src="./jquery.js"></script>.

В HTML: <script>...</script>.
