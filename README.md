# Проект: Путешествие по России (russian-travel)

*- это моя новая проектная работа по верстке на курсе "веб-разработчик" в Яндекс.Практикуме (3-ий спринт).*

### Особенности проекта:
* адаптивная верстка с использованием html, css;
* применена методология БЭМ;
* дизайн-макет в Figma;
* изображения нужно оптимизировать;
* с git работаем через терминал;
* github: коммитим часто, называем правильно, работаем с ветками;
* результаты работы (готовый сайт) нужно выложить на github pages -- [ссылка на сайт](https://#).

### Хронология:
**06.01.2022** -- приступил к выполнению работы:

* **проблема:** завершил по 3-му спринту теорию и тренажер (2 месяца с начала обучения). Прочитал вводные данные к заданию (проектной работе) и понял, что все, приплыли - где, тот подробный алгоритм действий, к которому я так привык на предыдущих заданиях? Что делать дальше не знаю! Волосы дыбом! Вспомнил мульт про Карлсона: "Спокойствие, только спокойствие". - ОК! Буду кушать слона по кусочкам (читал когда-то). Решил записывать свои действия и ощущения в readme.md (себе на будущее -- будет на чем ухмыльнуться), пробежался по конспектам, вспомнил свои действия по предыдущим заданиям. Бр-р-р, поехали!
* склонировал репозиторий себе на комп (терминал - git clone);
* зарегистрировал аккаунт в Figma, импортировал дизайн-проект, разобрался в функциях программы;
* создал файл .nojekyll (github игнорирует файлы, кот. начинаются с '_');
* переписал readme.md;
* добавил .editorconfig и .gitignore;
* normalize.css добавлять не стал (указаний не было, значит верстаю с самого нуля);
* создал приблизительную файловую структуру по БЭМ (на основе дизайн-макета);
* закачал картинки по ссылке (тратить время на оптимизацию картинок не хочу. Владею Photoshop и Pixelmator Pro).

**07.01.2022**

* подключил шрифты и определил общий стиль для страницы (body class="root");
* добавил footer;
* **проблемы:** не использую ветки в github, забываю часто коммитить;
* перечитал конспект про идеальный коммит о стандарте [Conventional Commits](https://www.conventionalcommits.org/ru/v1.0.0/);
* добавил header. Подчеркивание сделал через border-bottom в модификаторе.
* добавил в .page box-sizing:border-box; в header & footer изменил mardin на padding;
* добавил секцию lead.

**08.01.2022**

* в секции lead есть картинка с подписью. Использовал тег figure, он добавляет margin. Присвоил новый класс c margin: 0;
* **проблема:** в figure между картинкой и подписью Chrome и Safari показывают отступ. Все margin и padding по нулям. Img марджины не добавляет, figcaption по размеру шрифта и размеру строки проверил. Не понимаю откуда? Вожможно, проблема в браузерах или в самом теге figure. Поскольку это незначительно (около 5px), оставил, как есть. Мож, code reviewer подскажет?
* добавил секцию intro;
* добавил секцию photo-grid;
* добавил секцию places - контейнер секции (places) сверстал на флексах, а каждую карточку (article) - на гридах.
* добавил секцию cover - применил флексы и абсолютное позиционирование.
* добавил ссылкам при наведении opacity: 0.8 и transition-duration: 0.5s;

На сегодня все. Впереди - адаптивность и работа над ошибками.

**09.01.2022**

* подключил normalize.css - в чек-листе указано, что он нужен.



__.01.2022 -- отправил на code review;
__.01.2022 -- получил замечания;
__.01.2022 -- отправил на повторное code review;
