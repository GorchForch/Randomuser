# Тестовое задание iOS-разработчик
### Необходимо реализовать онлайн записную книжку, состоящую из не реальных людей, используя ​https://randomuser.me/​.
```
При отсутствии интернета используем ранее сохраненные данные из БД.
```

### Первый экран:
* Список с подзагрузкой из кастомных ячеек, где отображается фотография пользователя и имя
* Если проскролили до момента, где записи кончились, то подзагружаем еще до бесконечности
* Загружаемые данные пишем в БД
* Фотографии должны грузится параллельно и сохраняться в кеше

### Второй экран:
* При нажатии на ячейку на первом экране открываем профиль человека
* В профиле человека должны быть следующие данные:
* Фотография (с возможностью открытия на полный экран)
* Имя Фамилия
* Пол (в виде иконки)
* Дата рождения в виде ДД.ММ.ГГГГ (в скобках число лет)
* Почта
* Местное время (текущее время + смещение по часовому поясу)

### Требуемый язык программирования: Swift
```
Api с пагинацией для загрузки: https://randomuser.me/documentation#pagination 
```

Вариант реализации ничем не ограничен, плюсом будет использование следующего стека:
* CoreData
* SimpleImageViewer (pod)
* EGOCache (pod)
* FontAwesome
