
Комманды для работы с гитом

стрека верх             -будут показаны предыдущие комманды
Tab                      -автозаполнение пути для "git add"
git --version                 -смотреть версию
git init                      -инициализзация 
git status                    -узнать статус коммитов
git add путь (путь TAB)       -добавить файл 
git commit -m "комментарий"  -создание коммита
git log                      -просмотр сохранений
git chekout 38fa             -восстановить сохраненную версию  (4 цифры от сохраненного файла)
git chekout master           -вернуться в актуальное состояние в последнюю сохраненную версию
Q                            -выйти  из режима   END 
git diff                      -сравнение двух версий
git branch                     - показать список веток
git branch -d name             - удалить ветку
git branch new_name            - создать новую ветку
git checkout branch_name       - переключится на ветку
git log --grapf                 -смотреть ветки
git merge branch_name         -слияние веток . слияние производить  из той ветке  куда хотим залить 
git puh -отправить локальный на наш удаленный репозитарий (возможно авторизоваться на удаленном репозитории)
git pull - выкачать (pull) актуальное состояние из нашего удаленного репозитария
git clone (адрес репозитария от куда скачиваем_)- делаем гит clone для нашей весии этого репозитория



Работа с репозитарием  на гит хабе

1 создали акк на гит хаб 
2 создали локальный репозиторий  создали файл создали коммит
3 Подружить локальный и удаленный репозиторий
4 git puh -отправить локальный на наш удаленный репозитарий (возможно авторизоваться на удаленном репозитории)
5 провести изменения с другого компьютера
6 git pull - выкачать (pull) актуальное состояние из нашего удаленного репозитария

как сделать pull reques

1 делаем  Fork интересующего аккаунта репозитория
2 git clone (адрес репозитария от куда скачиваем_)- делаем гит clone для нашей весии этого репозитория
3 создаем ветку с предлагаемыми изменениями 
4 Производим все изменения только в этой ветки 
5 отправляем изменения на свой аккаунт 
6 после этого в гитхаб появляется возможность отправить pull request
