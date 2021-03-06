
# Инструкция по работе с Markdown
Настоящий документ предназначен для ознакомления пользователя с функциональными возможностями языка разметки Markdown. Markdown – это облегченный язык разметки, который является инструментом преобразования кода в HTML.

## Форматирование текста

Markdown воспринимает звёздочки «*» и символы подчёркивания «_» как признаки смыслового выделения текста:

Текст, окруженный одинарными символами (*), выделяется *курсивным шрифтом*, а текст, окруженный двойными символами, выделяется **полужирным шрифтом**. Также, выделенный фрагмент может находиться в любой части слова. Текст, выделенный курсивом с использованием синтаксиса языка Markdown, выглядит следующим образом:

Текст, выделенный курсивным полужирным шрифтом с использованием синтаксиса языка Markdown выглядит следующим образом:
Также можно использовать нижнее подчеркивание

_Пример_

__Пример__

___Пример___  


## Заголовки

Заголовки первого, третьего и шестого уровней, выполненные с помощью символа («#»), выглядят следующим образом:

#  Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня


## Цитаты
Цитаты
Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.

## Список

Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки

Для формирования ненумерованных списков используются такие маркеры, как звездочки, плюсы и дефисы. Например:
* Проводник
* Полупроводник
* Диэлектрик

Маркеры списков обычно начинаются с начала строки, однако они могут быть сдвинуты, но не более чем на 3 пробела. За маркером должен следовать пробел, либо символ табуляции. При необходимости в список можно вставить цитату.

Нумерованные списки всегда следует начинать с единицы.

1.	Проводник
2.	Полупроводник
3.	Диэлектрик



## Ссылки
Markdown поддерживает два стиля оформления ссылок:

- Гиперссылка, с немедленным указанием адреса (внутритекстовая);
- Гиперссылка, подобная сноске.

Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным.

  [пример](http://example.com/ "Необязательная подсказка")

  ## Изображения

Чтобы вставить изображение в тексте, достаточно написать следующее:
![Изображение](orig.jpg)





  ## Таблицы


Таблицы формируются следующим образом: 

  |                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |


Для всего остального есть обычный HTML.
Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.



Тестовое сообщение
Это сообщение добавлено с github
