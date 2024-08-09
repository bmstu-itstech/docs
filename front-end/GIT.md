# `Git`
____
### Нейминг коммитов / веток
____
##### Важно:
____
•	Универсального нейминга коммитов и веток нет, не было и вряд ли будет
•	Придя на новое рабочее место, вы скорее всего увидите что-то новое

На данный момент в нашей организации правильный нейминг такой:

 - __Ветки:__
 ____
__НАЗВАНИЕ_ПРОЕКТА-номер_задачи_которую_решает_ветка__
>Номер задачи можно найти в календарике задач

##### Важно:
____
> Каждая ветка – отдельная задача

###### *Пример:*
____
	__RS-5678__ 
	__REG-322__

- __Коммиты:__

###### *Пример:*
____
__handlers feat: implement ActionHandler__
###### Здесь:
	__handlers__ - это какой-то раздел проекта
	__feat__ - тип коммита, например fix, feat (новая фича), test, ref (refactoring), del и т.д.(все типы можно найти в статье раздела ‘Полезное’)
	__implement ActionHandler__ – что было сделано (кратко)


__Полезное__:
Angular Commit Format Reference Sheet (https://gist.github.com/brianclements/841ea7bffdb01346392c)