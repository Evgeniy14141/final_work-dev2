# React + TypeScript + Vite

 # "SkyFitnessPro: приложение для фитнеса"

Проект для домашних тренировок, таких как йога, стетчинг, стэп-аэробика, бодифлекс, танцевальный фитнес

## Шаблон

Проект реализован на основе шаблона (https://www.figma.com/design/2Vhk2Zdii1eM7rA0fWQExv/SkyFitnessPro?node-id=0-1&node-type=canvas&t=N9gKTxcF3INdRGdu-0).

### Как запустить проект

- Установить зависимость командой `npm i`
- Команда для запуска проекта `npm run dev`
- Открыть проект в браузере

### Стек и инструменты

Проект сделан на React + TypeScript используя tsx шаблоны.
Для стилей в коде используются Tailwind CSS.
Все компоненты разбиты по отдельным папкам.

### Функционал

Реализована регистрация пользователя и авторизация. В случае утери пароля, пользователь может его восстановить, получив уведомление о полученном письме на электронную почту о новом пароле.
Реализована форма для смены пароля из страницы профиля. На странице профиля отображается текущий e-mail и пароль.
Реализована логика добавления и удаления курса со страницы.
Реализована логика сохранения прогресса тренировки.



### Чек лист

Страница курсов (главная).
   На странице отображены все курсы, имеющиеся в базе данных. Курсы отображаются вне зависимости от статуса авторизации. При нажатии на кнопку «Наверх» происходит скролл в самое начало страницы.
Страница авторизации/регистрации.
   На странице пользователь имеет возможность войти в приложение или зарегистрироваться. Если данные были введены некорректно, пользователю показываются ошибки ввода.
Страница отдельного курса.
   По клику на выбранный курс неавторизованный пользователь или пользователь, не приобретавший данный курс, попадает на страницу, где может ознакомиться с его описанием. Если пользователь авторизован, то ему будет предложено добавить курс, иначе будет выведено предложение авторизоваться.
Страница профиля.
   На странице «Мой профиль» пользователь может просматривать и редактировать свои данные (сменить пароль). Также у пользователя есть возможность ознакомиться с приобретенными курсами и начать тренировку.
Страница тренировки.
По клику на выбранную тренировку в своем профиле пользователь попадает на страницу, где может открывать материалы урока (видеоролики на ютубе). У каждого урока есть определенные задания и возможность заполнить свой прогресс.