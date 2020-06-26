# Vue-todo

## ОПИСАНИЕ
SPA Приложение сделано при помощи vue.js, vue-router, vuex, localstorage.

Работает без перезагрузки страницы. Позволяет создавать заметки с пунктами todo. 
Редактировать их, дополнять, удалять. Сохраняет свое состояние после перезагрузки. 
Кэширует действия пользователя, позволяет отменять операции, возвращать отмененные операции. 
Имеет адаптивный дизайн.

## СТРАНИЦЫ:
* HomePage - главная страница с перечнем всех заметок
* NotePage = страница открытой заметки

## КОМПОНЕНТЫ:
* AddNote - компонент для создания новых заметок. Открывается как модальное окно из homePage
* Confirmation - компонент для подтверждения действий (удаление заметки, отмены всех внесенных изменений)
* NoteAtMain - компонент, отвечающий за отображение заметки на главной странице
* TodoItem - компонент, отвечающий за отображение пунктов todo, как на главной, так и на странице заметки (вид зависит от пропсов)
* Для некоторых иконок использован fontawesome
![Скриншот приложения vue-todo](https://plsk.site/img/vue-todo.jpg)


