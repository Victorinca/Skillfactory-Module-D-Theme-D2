# Skillfactory Module D. Theme D2

Completed homework for Skillfactory Course: 'Python Web Developer'. Module D - 'Backend-development in Python and Django'. Theme D2 - 'Models for Django'.

## Репозиторий учебного проекта NewsPaper для курсов "Веб-разработчик на Python" и "Fullstack-разработчик на Python"
### [Модуль D. Тема D2 "Модели"](https://victorinca.github.io/Skillfactory-Module-D-Theme-D2/)

Приложение новостного портала NewsPaper, созданное с помощью Python и Django, чтобы можно было: 1) смотреть новости 2) читать статьи.

Итоговое задание по теме D2 "Модели" заключается в создании каркаса и базы этого приложения (пока что только моделей).

База данных: sqlite.

Состоит из приложений news и accounts.

#### Приложение news включает в себя модели:
1) Author - авторы статей, новостей (далее - постов).
2) Category - категории постов - темы, которые они отражают (бизнес и экономика, наука и технологии, образование и вакансии, стиль жизни и здоровье и т.д.).
3) Post - посты (статьи и новости), которые создают пользователи. Каждый объект может иметь одну или несколько категорий.
4) PostCategory - промежуточная модель (явная) для связи "многие ко многим".
5) Comment - хранение комментариев к постам, оставляемых под каждой новостью/статьёй.

Все модели собраны в единый скрипт (код) в приложении news в файл models.py.

#### В качестве результата задания подготовлен файл command_for_django shell.txt, где написан список всех команд, запускаемых в Django Shell.
Файл [command_for_django shell.txt](https://github.com/Victorinca/Skillfactory-Module-D-Theme-D2/blob/main/command_for_django%20shell.txt) содержится в корневой директории.

## Поддержать, отблагодарить автора
Если представленная работа Вам понравилась, принесла пользу, сэкономила время, то Вы можете поддержать автора, воспользовавшись различными платежными системами.
- [Поддержать автора через ЮMoney](https://yoomoney.ru/to/4100117804016773)
- [Выразить признательность через Qiwi](https://qiwi.com/n/VICTORINCA)
- [Поблагодарить автора через WebMoney](https://donate.webmoney.com/w/MmKxolmn8LgqxXjZ9azFqd)
#### Благодарю Вас за щедрость!
#### Ваша поддержка и признательность очень приятны и важны!

## Ссылки

- [Ссылка на сайт проекта](https://victorinca.github.io/Skillfactory-Module-D-Theme-D2/)
- [Ссылка на GitHub](https://github.com/Victorinca/Skillfactory-Module-D-Theme-D2)
  

По всем вопросам, которые касаются выполненного задания, можно писать на почту victoriavladimirskaya@gmail.com.
