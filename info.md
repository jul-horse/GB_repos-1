# Работа с удаленным репозиторием.


## Разграничение понятий Git/GitHub. 

***

### Git
- git — одна из систем контроля версий 
- Cпособ организации и поддержания версионности 
- Cамая популярная система контроля версий
### GitHub
- Сервис компании Майкрософт для организации работы удаленных репозиториев 
- Самый популярный сервис Git 
- Много полезных функций 
- Огромный архив различного кода

***

## Работа с удаленными репозиториями. Скачивание из текущего репозитория и слияние со своей версией

***

Освоить работу с удаленными репозиториями, которые находятся не на локальной, а на удаленной машине, например, на сервере. Копировать внешний репозиторий на свой ПК можно командой __git clone__.

>Команда __git clone__ составная: она не только загружает все изменения, но и пытается слить   все ветки на локальном компьютере и в удаленном репозитории.


## __git pull__

Эта команда позволяет скачать все   из текущего репозитория и автоматически сделать merge с нашей версией

## __git push__

Отправить свою версию репозитория во внешний репозиторий поможет команда *git push*. При первом её использовании нужна авторизация.

***

# Как настроить совместную работу

1. Создать аккаунт на GitHub.com 
2. Создать локальный репозиторий 
3. “Подружить” ваш локальный и удалённый репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать 
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно,   вам нужно будет авторизоваться на удалённом репозитории 
5. Провести изменения “с другого компьютера” 
6. Выкачать (pull) актуальное состояние из удалённого репозитория

***

## Pull request

***

➜ команда для предложения изменений 

➜ запрос на вливание изменений в репозиторий

>В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду __pull request__. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала пользователь копирует репозиторий на свой компьютер, делает __fork__ репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой __push__ в свой аккаунт на GitHub и даёт команду __pull request__.

***

## Как сделать pull request

***

1. Делаем fork (ответвление) репозитория 
2. Делаем git clone СВОЕЙ версии репозитория  
3. Создаем новую ветку и в НЕЕ вносим свои изменения 
4. Фиксируем изменения (делаем коммиты) 
5. Отправляем свою версию в свой GitHub На сайте GitHub нажимаем кнопку pull request

>При запуске команды __git init__ всё происходит только в локальном репозитории: в папке на компьютере пользователя, эту папку создавшего. Но для работы в команде программисты используют удаленные репозитории.
