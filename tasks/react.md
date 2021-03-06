# Тестовое задание: react

Представим ситуацию: мы работаем над адаптивным веб-приложением и решили добавить в него функцию «новости» — что-то вроде stories в инстаграме, но ещё больше похоже на новости в мобильном клиенте тиньков-банка. Новости представляют из себя общий список:

<p>
  <img src="../Resources/news1.jpg" width="300">
</p>

При нажатии на одну из новостей на весь экран открывается просмотрщик:

<p>
  <img src="../Resources/news3.jpg" height="300">
  <img src="../Resources/news2.jpg" height="300">
</p>

Каждая новость может состоять из нескольких частей (от 1 до 10). Вверху экрана показывается «прогресс-бар», где видно сколько всего частей и прогресс по времени (см. скриншоты). Каждая часть показывается пользователю в течении 5 секунд и после этого времени автоматически переходит на следующую. По окончании последней части начинается следующая новость.

Оказалось, что backend разработчик в отпуске, но менеджер попросил вас сделать frontend-часть этой задачи, известно лишь то, что новости будут создаваться в некотором редакторе в админке, а клиент будет получать новости по АПИ.

Про новости известно следующее:

* Каждая новость состоит из частей (от 1 до 10)
* Каждая часть новости может содержать
  * изображение
  * любой цвет фона
  * неограниченное количество блоков текста с их размером и позицией (например, один текст в самом верху новости, один текст внизу и один, самый большой в середине)
  * Кнопку, при нажатии на которую открывается любой URL

Задание:

1. Придумайте, в каком формате сервер будет отдавать вам данные и задокументируйте API
2. Создайте mock для API - представьте, что сервер отдаёт вам реальные данные. Как только backend-разработчик выйдет из отпуска мы просто заменим этот moсk на вызов реального API и всё заработает!
3. Реализуйте отображение списка новостей.
4. Реализуйте просмотрщик.
