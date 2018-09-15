# Задание 2

```js
Задача:
С сервера приходит массив периодов, 
каждый период в этом массиве имеет дату начала (поле start) и дату конца этого периода (поле end), 
также есть идентификатор (id) периода, 
и признак, что период заблокирован или нет для редактирования (editable)

Необходимо:
а) Написать функцию, которая на выходе возвращает только те периоды, которые можно редактировать
function findEditablePeriods(periods) {
 // paste code
 return newPeriods;
}

Пример вызова
var periods = [ ... ]
var myEditablePeriods = findEditablePeriods(periods);
console.log(myEditablePeriods);


б) Написать функцию, которая будет удалять период по идентификатору
function removePeriodById(id, periods) {
 // paste code
 return newPeriods;
}

Пример вызова
var periods = [ ... ]
var myNewPeriods = removePeriodById(2, periods);
console.log(myNewPeriods);

в) Написать функцию, которая возвращает только те периоды, которые входят в диапазон АВГУСТ - ОКТЯБРЬ 
function findPeriodsInYearZone(periods, diapason) {
 // paste code
 return newPeriods;
}

Пример вызова
var periods = [ ... ]
var august = new Date(2018, 7, 1);
var october = new Date(2018, 9, 1);
var periodsInYearZone = findPeriodsInYearZone(periods, [august, october]);
console.log(periodsInYearZone);

г) Используя функцию findPeriodsInYearZone найти только те периоды, которые начинаются
 и заканчиваются в СЕНТЯБРЕ
```

```js
Входные параметры

var periods = [ 
  { 
    id: 1, 
    editable: true, 
    start: new Date(2018, 0, 1), 
    end: new Date(2018, 0, 15) 
  },
  { 
    id: 2, 
    editable: false, 
    start: new Date(2018, 4, 1), 
    end: new Date(2018, 4, 10) 
  },
  { 
    id: 3, 
    editable: false,
    start: new Date(2018, 9, 5),
    end: new Date(2018, 10, 10)
  },
  { 
    id: 4, 
    editable: false,
    start: new Date(2018, 8, 8),
    end: new Date(2018, 8, 20)
  },
  { 
    id: 5, 
    editable: false,
    start: new Date(2018, 11, 1),
    end: new Date(2018, 11, 12)
  },
  { 
    id: 6, 
    editable: true,
    start: new Date(2017, 8, 1),
    end: new Date(2018, 8, 15)
  }    
];
```
