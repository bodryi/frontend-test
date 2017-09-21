# Тестовое задание на позицию Frontend Developer в НТЦ Протей

Необходимо реализовать систему просмотра объектов на карте. 

Страница должна быть поделена на 2 области:

*	Список объектов.
*	Карта, на которой отображаются объекты.

# Дополнительные сведения
* Объекты подгружаются из JSON-файла
* При выделении объекта на карте маркер должен менять цвет на другой, а соответствующее поле в списке выделяться.Такое же поведение должно быть, когда выбор происходит из списка. При выделении маркера карта должна центрироваться на нем.
* Если был выделен объект на карте и выделяется другой объект, то выделение с предыдущего элемента должно сняться.
* Возможность во время работы добавить новый объект на карту(в json изменения сохранять не нужно).
* Возможность во время работы удалить объект на карте(в json изменения сохранять не нужно).
* Возможность фильтровать список объектов.

# Требования

* Реализовать с использованием Angular 2+.
* Не использовать препроцессоры css, но можно использовать postCSS.
* Для карт использовать библиотеку Leaflet.
* Не использовать ui-фреймворки(Bootstrap, Zurb Foundation и т.п.).
* Задание должно быть написанно на TypeScript.
* Использовать webpack

# Дополнительные требования (не обязательно, но будет плюсом)
* Написать тесты
* Сделать добавление объекта с помощью всплывающих окон
* Сделать окно с подтверждением удаления объекта

# Выполнение
Код должен быть выложен на github. После выполнения необходимо выслать ссылку на репозиторий.

# Полезные ссылки

* https://angular.io/styleguide
* https://learn.javascript.ru/screencast/webpack
* https://github.com/boykovdmitriy/angular2modal
* https://github.com/boykovdmitriy/angular2Leaflet
