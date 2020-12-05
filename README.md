# example-betting-api
Примеры работы с различными API зарубежных беттинговых контор

Пример, вы можете скопировать нужный файл к себе в проект и с помощью функции getLine заполучить нужную линию из конторы.

```

const lootbet = require('./lootbet.js')

lootbet.getLine()
.then(data => console.log(data))

```

Формат всех овтетов стандартный

```
{
    id,
    tournamentName,
    tournamentId,
    home,
    away,
    homeOdd,
    awayOdd
}
```
