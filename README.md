# Week-4

1. Какими способами можно подключать CSS-стили? Найдите сами еще один способ, не указанный в уроке
   С помощью атрибута style
   С помощью тега <style>
   С помощью тега <link>

2. Зачем нужен Normalize.css?
   Normalize.css — это небольшой CSS-файл, который обеспечивает для HTML-элементов лучшую кроссбраузерность (поддержку разных браузеров) в стилях по умолчанию.
   Цели normalize.css:
   • сохранять полезные настройки браузера, а не стирать их
   • нормализовать стили для широкого круга HTML-элементов
   • корректировать ошибки и основные несоответствия браузера
   • совершенствовать юзабилити незаметными улучшениями
   • объяснять код, используя комментарии и детальную документацию

3. Что такое CSS-директивы?
   Это специальные конструкции, которые начинаются с символа @. Директивы чаще всего влияют на весь документ, но сами по себе ничего не стилизуют. Например, директива @font-face позволяет подключать на страницу нестандартные шрифты, которые потом можно использовать в свойстве font-family. Или директива @media, которая при определённых условиях активирует или деактивирует какие-то CSS правила. С помощью @media делают адаптивную вёрстку.

4. В чем разница между margin и padding?
   Padding определяет отступы изнутри до краев блока. А margin - снаружи от края нашего блока до всех ближайших элементов в разные стороны.

5. Как в CSS определяются приоритеты?
   Насколько этот стиль или свойство уникально относительно этого элемента. Чем стиль более уникален, тем он приоритетней. Очередность важности:
   1.Style= самый важный. 2.Идентификатор id #. 3. Классы, псевдоклассы. 4. Теги, псевдоэлементы.  
   Не желательный способ, но иногда применяется: написать рядом со стилем !important
   Какое из свойств будет приоритетнее - #link .main или span #login? Приоритетней будет span #login

6. В чем разница между CSS1 и CSS3?
   Главное различие между CSS и CSS3 состоит в том, что CSS — это простой язык дизайна, который позволяет создавать привлекательные веб-страницы, тогда как CSS3 — это последняя третья версия языка каскадных таблиц стилей, имеющая новые функции, позволяющие работать с веб-дизайном намного более эффективно.

7. ПроЧто такое псевдоклассы? А псевдоэлементы?
   Псевдоклассы определяют динамическое состояние элементов, которое изменяется с помощью действий пользователя, а также положение в дереве документа: селектор:псевдокласс { ... }
   Псевдоэлементы создают "виртуальные теги" и позволяют стилизовать их. селектор::псевдоэлемент { ... }

8. Изучите статью про "плохие" теги https://msiter.ru/tutorials/html-srednego-urovnya/plokhie-tegi и пришлите список тегов, которые нежелательно использовать
   <b> отображает текст жирным шрифтом. Вместо него можно использовать тег <strong>
   <i> отображает текст курсивом. Использование тега <em> также добавляет дополнительную информацию (выделение), а для обычной визуализации подойдет соответствующее свойство CSS.
   <layer> аналогичен тегу <div>, однако работает он только в старых версиях браузера Netscape и потому совершенно бесполезен.

9. Как можно подключать шрифты локально?
   Правило @font-face src позволяет задать название локального шрифта, т.е. если у пользователя на компьютере уже установлен нужный шрифт, то будет использоваться именно он, при этом существенно увеличится скорость загрузки и отрисовки страницы.

10. Почему не стоит использовать сокращенную запись без необходимости? И если все же использовать, как это делать правильно?
    Можно запутаться и упустить какой стиль более актуальный для нас, если указан еще один стиль, противоречащий сокращенному стилю. Сокращенный стиль является приоритетным. Лучше использовать полный стиль.

Задание на развитие мягких навыков (soft skills)
На этой неделе я усиленно училась и практиковала CSS стили. Я горжусь собой, потому что у меня получилось создать сайт очень похожий на макет. (Очень маленькую часть сайта, но это уже что-то. Москва не сразу строилась.) Теперь я еще лучше понимаю чем занимается веб-разработчик. Заметила, что я делаю все очень медленно, это немного бесило, но наверно это нормально, ведь мы не роботы и невозможно делать что-то новое с ходу, нужна практика и опыт. Надеюсь когда-нибудь я буду писать код как электровеник :-)  В целом я рада, что у меня есть мотивация, и я понимаю, что мне нравится то что я делаю и очень надеюсь что это станет моим любимым делом в будущем, которое еще и будет приносить доход. 