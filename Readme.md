# Инструкция по работе с git и ветками

## Создание репозитариф

Для того чтобы создать версионность к созданной папке, и создать в ней локальнй репозиторий, для этого необходимо открыть окно терминала в этой папке и написать команду *git ini*. Тогда ваша папка станет репозиторием и в ней появится скрытая папка .git
## Добавление файлов в репозитарий

Добавить версионность к файлу, находящемуся в папке-репозитории, можно с помощью команды *git add*. Пишется она следующим образом *git add <название файла>*.
## Создание фиксаций

##  Просмотр истори коммитов

## Переключение между сохранениями

Для того, чтобы переклюаться между коммитами, необходимо использовать команду *git checkout*. Используется она следующим образом: *git checkout <номер коммита>*. Номер коммита можно взять, посмотрев список всех коммитов.
## Созданние ветки

Для того чтобы создать ветку используется команда *git branch*  в паке с репозиторем напишите команду *git branch <название ветки>*. Проверить то, что ветка создалась можно с помощью команды *git branch*  в папке с репозиторием.
## Переключение между ветками

Для того, чтобы переключиться между ветками используется команда *git checkouy*. Применяется она следующим образом: в папке с репозитарием необходимо написать *git checkout <назавние созданной ветки>*

## Слияние веток

Слияение веток происходит по команде *git merge*. Работает она следующим образом,в папке с репозитарием надо написать командк *git merge <назавание сливаемой ветки>*. Сделать это необхадимо сделать это находясь в ветки куда сливаеются. Могут возникнуть конфликты, в случае конфликта необходимо выбрать применяемые изменения и осбавить *commit*.
## Удаление веток

Удаление слитой ветки можно произвести с помощью команды *git branch -d*. Используется она в папке с репозиторем пишем команду *git branch -d <название удаляемой ветки>*. Удаляемая ветка обязательно должна быть слита с какой-нибудь из существующих веток.