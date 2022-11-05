# LR6
Лабораторная работа №6

В личное хранилище на github был скопирован репозиторий с помощью Fork.
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/0.1.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/0.PNG)
Был скачан Git и введены имя пользователя и почта.
После этого была сделана локальная копия репозитория с помощью `git clone`.
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/1.PNG)
В GitHub был добавлен файл New file
Совершается переход в скопированный репозиторий с помощью `cd`, а далее вызывается команда `git pull`, которая подгружает в локальный реапозиторий изменения, внесенные на GitHub.
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/2.PNG)

*Дальнейшая работа будет происходить локально :shipit:

`git log` позволяет посмотреть лог изменения.
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/3.PNG)
Использование `git log -p -2` позволяет увидеть два последних коммитов
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/5.PNG)
Далее переходим в ветку **branch1**. Для этого используется `git checkout`
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/6.PNG)
Теперь можно посмотреть лог в данной ветке
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/7.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/8.PNG)
Чтобы объединить ветки, используется команда `git merge`
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/9.PNG)
При попытке выполнить команду мы замечаем конфликт. 
Узнать состояние и увидеть возможные ошибки позволяет команда `git status`. Выполнив ее, мы понимаем причину проблемы - присутствуют несоединенные пути. Разрешить конфликт можно просто добавив файл mergefile.txt командой `git add`
После исправления конфликта еще раз проверяем статус проекта.
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/10.PNG)
Наконец, можно закоммитить изменения командой `git commit -m`, где -m используется для добавления комментария в консоли
Ненужную ветку удаляем командой `git branch -d`
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/11.PNG)

Вносим дальнейшие имзменения следующим образом: 
- `echo текст > файл` создает файл с текстом
- `git add файл` добавляет созданный файл
- `git commit -m "изменение n"` коммитит изменение с комментарием
Этот порядок действий мы применяем три раза (создаем 3 файла).
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/12.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/13.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/14.PNG)
>первый файл
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/15.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/16.PNG)
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/17.PNG)
>второй файл + проверка
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/19.PNG)
>третий файл
Выводим все изменения в логе
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/20.PNG)

`git reset HEAD~1` позволяет выполнить откат коммита на одно изменение.
Выполнив откат, еще раз проверим лог - остануться только _Изменение 2_ и _Изменение 1_
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/21.PNG)

Для выполнения отчета создается ветка record с помощью команды `git branch record`
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/22.PNG)

Далее для написания отчета открывается для работы файл README.md с помощью команды `notepad README.md`
![](https://github.com/la103221/LR6v2/blob/record/Screenshots/23.PNG)