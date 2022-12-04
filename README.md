<!-- 
 *   https://github.com/andreysssr/Markdown-Cheatsheet
-->

# Шпаргалка по Markdown - Markdown синтаксис

---

##### Содержание
[Заголовки](#headers)  
[Блок в котором оформляется код](#blockCode)  
[Горизонтальные линии](#hr)  
[Выделение текста](#textSelecte)  
[Разрывы строк](#lineBreaks)  
[Списки и отступы](#listsAndMargins)  
[Ссылки и картинки](#linksAndPictures)  
[Вставка локальной картинки - из текущей папки](#localPictures)  
[Создание меню](#createMenu)  
[Цитаты](#quotes)  
[Вставка кода](#insertingCode)  
[Таблицы](#tables)  
[Чек-боксы](#checkboxes)  
[Экранирование](#screening)

---
<a name="headers"><h2>Заголовки</h2></a>

Заголовки H1–H6 выделяются в Markdown с помощью знаков решетки

# Это H1
## Это H2
### Это H3
#### Это H4
##### Это H5
###### Это H6

Ещё H1 и H2 можно выделять другим способом

Это H1 или Заголовок I
===
Это H2 или Заголовок II
---

[код] ↓
```
# Это H1
## Это H2 
### Это H3
#### Это H4 
##### Это H5 
###### Это H6

Ещё H1 и H2 можно выделять другим способом

Это H1 или Заголовок I
===

Это H2 или Заголовок II
---
```

---
<a name="blockCode"><h2>Блок в котором оформляется [код]</h2></a>
для оформления блока или выделения слов в тексте используются три обратные ковычки над блоком и три обратные ковычки под блоком текста

[код] ↓
```
    ```
        здесь блок который нужно оформить 
    ```
```

---
<a name="hr"><h2>Горизонтальные линии</h2></a>
---
или
***
или
<hr>

[код] ↓
```
---
    или
***
    или
<hr>
```

---
<a name="textSelecte"><h2>Выделение текста</h2></a>

Простой текст

__Жирный текст__

**Тоже жирный**

*Курсив текст*

_Тоже курсив_

~~Зачеркнутый~~

[код] ↓
```
Простой текст

__Жирный текст__

**Тоже жирный**

*Курсив текст*

_Тоже курсив_

~~Зачеркнутый~~
```

---
<a name="lineBreaks"><h2>Разрывы строк</h2></a>

Два пробела после строки.  
Вставлена новая строка.

Использование tag HTML для разрыва границы.<br>
Вставлена новая строка.

[код] ↓
```
Два пробела после строки.  
Вставлена новая строка.

Использование tag HTML для разрыва границы.<br>
Вставлена новая строка.
```

---
<a name="listsAndMargins"><h2>Списки и отступы</h2></a>

Чтобы оформить строку в элемент маркированного списка,
в начале нужно поставить плюс, минус или звездочку.
Звездочка не приведет к курсивному выделению, потому что
отделяется от слова пробелом.

- Пункт 1
- Пункт 2
- Пункт 3

или
+ Пункт 1
+ Пункт 2
+ Пункт 3

или
* Пункт 1
* Пункт 2
* Пункт 3

[код] ↓
```
- Пункт 1
- Пункт 2
- Пункт 3

или
+ Пункт 1
+ Пункт 2
+ Пункт 3

или
* Пункт 1
* Пункт 2
* Пункт 3
```
. . . . . . . . . . .


1. Пункт 1
2. Пункт 2
3. Пункт 3

или
1. Пункт 1
1. Пункт 2
1. Пункт 3

[код] ↓
```
1. Пункт 1
2. Пункт 2
3. Пункт 3

или
1. Пункт 1
1. Пункт 2
1. Пункт 3

```
. . . . . . . . . . .

- Пункт 1
    - Подпункт A
        - Подподпункт a

- Пункт 2
    + Подпункт A
        * Подподпункт a

<br>

1. Пункт 1
    + Подпункт A
        - Подподпункт a

2. Пункт 2
    1. Подпункт 2.1.
        1. Подподпункт 2.1.1

3. Пункт 3


[код] ↓
```
- Пункт 1
    - Подпункт A
        - Подподпункт a
        
- Пункт 2
    + Подпункт A
        * Подподпункт a



1. Пункт 1
    + Подпункт A
        - Подподпункт a

2. Пункт 2
    1. Подпункт 2.1.
        1. Подподпункт 2.1.1

3. Пункт 3
```

---
<a name="linksAndPictures"><h2>Ссылки и картинки</h2></a>

Это [ссылка](http://example.net/ "Агентство TexTerra") с тайтлом.

[Эта ссылка](http://example.net/) без заголовка.

<https://texterra.ru/> – а это безанкорная ссылка.

[код] ↓
```
Это [ссылка](http://example.net/ "Агентство TexTerra") с тайтлом.

[Эта ссылка](http://example.net/) без заголовка.

<https://texterra.ru/> – а это безанкорная ссылка.
```

Синтаксис Markdown для работы с картинками очень похожий на работу с сылками.
Разница в восклицательном знаке перед первыми квадратными скобками.
Ссылке на картинку тоже можно присвоить определенный ID. Примеры:


![Лого github](https://github.githubassets.com/favicons/favicon.svg)

![Лого github](https://github.githubassets.com/favicons/favicon.svg "Наш логотип")

```
![Лого github](https://github.githubassets.com/favicons/favicon.svg)

![Лого github](https://github.githubassets.com/favicons/favicon.svg "Наш логотип")
```

---
<!-- #### Вставка локальной картинки - из текущей папки -->
<a name="localPictures"><h2>Вставка локальной картинки - из текущей папки</h2></a>

<p align="center">
    <img alt="Git" src="img/git-logo.png" height="190" width="455">
</p>

[код] ↓

```
# расположение - left, center, right
<p align="center">
    <img alt="Git" src="img/git-logo.png" height="190" width="455">
</p>
```

---
<a name="createMenu"><h2>Создание меню</h2></a>

#### Создание меню на внешние страницы

[Пункт меню 1](http://example.net/url1)   
[Пункт меню 2](http://example.net/url2)
- [Пункт меню 3](http://example.net/url3)
- [Пункт меню 4](http://example.net/url4)  
  -- [Пункт меню 5](http://example.net/url5)  
  -- [Пункт меню 6](http://example.net/url6)

[Пункт меню 7](http://example.net/url7)  
[Пункт меню 8](http://example.net/url8)

[код] ↓

```
[Пункт меню 1](http://example.net/url1)   
[Пункт меню 2](http://example.net/url2)   
- [Пункт меню 3](http://example.net/url3)   
- [Пункт меню 4](http://example.net/url4)  
-- [Пункт меню 5](http://example.net/url5)  
-- [Пункт меню 6](http://example.net/url6)

[Пункт меню 7](http://example.net/url7)  
[Пункт меню 8](http://example.net/url8) 
```
. . . . . . . . . . . . . . . .
#### Создание меню на внутренние пункты страницы

[Заголовки](#headers)  
[Горизонтальные линии](#hr)  
[Выделение текста](#textSelecte)

[код] ↓

```
# оформление меню 
[Заголовки](#headers)  
[Горизонтальные линии](#hr)  
[Выделение текста](#textSelecte)

# оформление заголовков на которые ссылаются меню
<a name="headers"><h2>Заголовки</h2></a>
<a name="hr"><h2>Горизонтальные линии</h2></a>
<a name="textSelecte"><h2>Выделение текста</h2></a>
```

---
<a name="quotes"><h2>Цитаты и вставки кода</h2></a>

> Привет! Это цитата

>> Это тоже цитата

> Это еще одна цитата
Это ее продолжение (показываем отступом)

> Это тоже
> Будет
> Одна целая цитата

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.

[код] ↓
```
> Привет! Это цитата

>> Это тоже цитата

> Это еще одна цитата
Это ее продолжение (показываем отступом)

> Это тоже
> Будет
> Одна целая цитата

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

Цитаты вкладываются как в списки, так и в другие цитаты.
Цитаты также могут включать в себя заголовки, списки и код.

---
<a name="insertingCode"><h2>Вставка кода</h2></a>

Вставлять код можно как внутрь строк, так и отдельными блоками.
Для соответствующей разметки используют грависы или обратные тики - обратная ковычка на клавише ( ~ ) - ( Ё ).

Инлайн-код выделяют одиночными символами, а блоки – тройными.
При оформлении целого блока можно указать язык программирования,
чтобы подсветить соответствующий синтаксис.

Просто инлайн-код: `print("Hello, World!")`

[код] ↓

```
Просто инлайн-код: `print("Hello, World!")`
```
. . . . . . . . . . . . . . . .

Код на Python:

```python
x = int(input())
if x > 0:
    print(x)
else:
    print(-x)
```

. . . . . . . . . . . . . . . .

Код на JavaScript:
```javascript
let greeting1 = 'Father!';
console.log(greeting1);

let greeting2 = 'Mother!';
console.log(greeting2);
```

[код] ↓
```
# после обратных ковычек добавляем язык - для подстветки
```javascript
let greeting1 = 'Father!';
console.log(greeting1);

let greeting2 = 'Mother!';
console.log(greeting2);
`` `
```

. . . . . . . . . . . . . . . .

Код на lua

```lua
local Class = {
    new = function(self, Objict1, Object2, Config) 
        //...
        return self
    end
}
```
[код] ↓

```
    # после обратных ковычек добавляем язык - для подстветки
    ```lua
    local Class = {
        new = function(self, Objict1, Object2, Config) 
            //...
            return self
        end
    }
    ```
```

---
<a name="tables"><h2>Таблицы</h2></a>

| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

|                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |

| Язык | Метка |
| -----|------|
| Java Script | javascript |
| C++ |cpp|
| HTML|html|
|Markdown|md|
|JSON|json|
|Python|python|
|SQL|sql|

|   | table | header |
|---|-------|--------|
| a | table | row    |
| b | table | row    |


[код] ↓
```
| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

|                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |

| Язык | Метка |
| -----|------|
| Java Script | javascript |
| C++ |cpp|
| HTML|html|
|Markdown|md|
|JSON|json|
|Python|python|
|SQL|sql|

|   | table | header |
|---|-------|--------|
| a | table | row    |
| b | table | row    |

```

---
<a name="checkboxes"><h2>Чек-боксы</h2></a>

Для любителей чек-листов есть такая возможность.
Чек-бокс получится, если в начале строки вставить пробел,
заключенный с двух сторон в квадратные скобки.
Можно сразу задать выполненную задачу с помощью [X].
С оформлением ссылок по-другому – в квадратных скобках
или текст, или ничего.

- [X] Взять кошелёк
- [x] Пойти в магазин
- [x] Купить хлеб и молоко
- [ ] Принести продукты домой

[код] ↓
```
- [X] Взять кошелёк 
- [x] Пойти в магазин 
- [x] Купить хлеб и молоко
- [ ] Принести продукты домой
```

---
<a name="screening"><h2>Экранирование</h2></a>

Чтобы спецсимволы не исчезали и не влияли на оформление,
нужно использовать экранирование. Как и во многих других
языках программирования, этим целям служит обратная косая черта (бэкслеш).

\*Нет курсива\*
\*\*Нет жирного выделения\*\*
\# Ни каких заголовков H1 \#

[код] ↓
```
\*Нет курсива\*
\*\*Нет жирного выделения\*\*
\# Ни каких заголовков H1 \#
```