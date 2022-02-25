# Deer-of-Santa
Дядо Коледа много обича да пътешества, но за съжаление се случило, така че точно преди да замине на почивка три от елените му се разболяли и трябва да ги остави. Когато заминава, той трябва да съобрази колко храна да остави на всеки един от елените, за да не останат гладни. Напишете програма, която пресмята дали оставената от Дядо Коледа храна ще е достатъчна за времето, в което него няма да го има. Всеки елен изяжда определено количество храна на ден.

<br>Вход:
<br>От конзолата се четат пет реда:
<br>Първи ред – брой дни, в които Дядо Коледа отсъства – цяло число в интервала [1…5000]
<br>Втори ред – оставена храна в килограми – цяло число в интервала [0…100000]
<br>Трети ред – храна на ден за първия елен в килограми – реално число в интервала [0.00…100.00]
<br>Четвърти ред – храна на ден за втория елен в килограми– реално число в интервала [0.00…100.00]
<br>Пети ред – храна на ден за третия елен в килограми – реално число в интервала [0.00…100.00]

<br>Изход:
<br>На конзолата трябва да се отпечата на един ред:
<br>Ако оставената храна Е достатъчна:
<br>“{килограми, които остават} kilos of food left.”
<br>Резултатът трябва да е закръглен към ПО-МАЛКОТО цяло число
<br>Ако оставената храна НЕ Е достатъчна:
<br>“{килограми, които не  недостигат} more kilos of food are needed.”
<br>Резултатът трябва да е закръглен към ПО-ГОЛЯМОТО цяло число

<br>Примерен вход и изход:
| вход   | изход                 | Обяснения                                 |
|--------|-----------------------|-------------------------------------------|
| (["2", | 2 kilos of food left. | Нужна храна за:                           |
| "10",  |                       | първи елен => 2 дни * 1 кг = 2 кг         |
| "1",   |                       | втори елен => 2 дни * 1 кг = 2 кг         |
| "1",   |                       | трети елен => 2 дни * 2 кг = 4 кг         |
| "2"])  |                       | Общо нужна храна => 2 + 2 + 4 = 8 кг      |
|        |                       | 8 < 10 => количеството храна е достатъчно |
|        |                       | => 10 - 8 = 2 кг. храна остават           |

| вход   | изход                             |
|--------|-----------------------------------|
| (["5", | 60 more kilos of food are needed. |
| "10",  |                                   |
| "2.1", |                                   |
| "0.8", |                                   |
| "11"]) |                                   |
