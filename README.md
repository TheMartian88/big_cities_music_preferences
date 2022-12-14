# Музыка больших городов
## Описание
Существует много предрассудков вокруг музыкальных предпочтений Москвы и Санкт-Петербурга, двух крупнейших городов, совсем непохожих друг на друга. На реальных данных Яндекс.Музыки мы проверим гипотезы и сравним поведение пользователей двух столиц.
## Гипотезы
1. Активность пользователей в Москве и Санкт-Петербурге проявляется по-разному в зависимости от дней недели;
2. Утром в понедельник в Москве преобладают одни жанры музыки, а в Петербурге — другие. Это верно и для вечера пятницы;
3. Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.
## Данные
**Описания колонок:**
* `userID` — идентификатор пользователя;
* `Track` — название трека;  
* `artist` — имя исполнителя;
* `genre` — название жанра;
* `City` — город пользователя;
* `time` — время начала прослушивания;
* `Day` — день недели.
## Задачи
- Сравнить прослушивания в понедельник, среду и пятницу по Москве и Санкт-Петербургу;
- Сравнить жанры, которые слушают пользователи утром в понедельник и вечером в пятницу в Москве и Санкт-Петербурге;
- Сравнить музыкальные предпочтения пользователей Яндекс.Музыки, проживающих в Москве и Санкт-Петербурге.
## Используемые библиотеки
_pandas_
