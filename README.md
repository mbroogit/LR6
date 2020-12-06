С помошью команды `git clone https://github.com/Kurtyanik/LR6` скопировал себе репозиторий.

![Клонирование](screenshots/cloned.png)


Создал дополнительную ветку. Внутри папки создал файл с произвольным содержанием и добавил его в новую ветку. С помощью команды `git remote set-url origin https://github.com/mbroogit/LR6` поменял адрес удаленного репозитория, после чего загрузил изменения.

![Загрузка](screenshots/push.png)


С помощью команды `git log` получил историю коммитов.

![История](screenshots/log.png)


С помощью команды `git show` получил подробную информацию по последнему коммиту.

![Последние изменения](screenshots/latest_commit.png)


Переключился на ветку `git commit master` и выполнил слияние ветки in_work, которое прошло без ошибок.

![Слияние](screenshots/merge.png)


Удалил побочную ветку.

![Удаление](screenshots/remove.png)


Выполнил хард-откат до версии "до изменений".

![Сброс](screenshots/reset.png)