# Инструкция для работы с Git и удалёнными репозиториями
## Что такое Git? 


**_Git_** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.


### Подготовка репозитория git


Для создание репозитория необходимо выполнить команду **_git init_** в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка ._git_)

### Создание коммитов


**_Git add_**
Для добавления измений в коммит используется команда _git add_. Чтобы использовать команду _git add_ напишите git add <имя файла>

### Просмотр состояния репозитория


Для того, чтобы посмотреть состояние репозитория используется команда **_git status_**. Для этого необходимо в папке с репозиторием написать git status, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов


Для того, чтобы создать коммит(сохранение) необходимо выполнить команду **_git commit_**. 
Выполняется она так: git commit -m "<сообщение к коммиту>. Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.
Команда git log --graph выводит список коммитов в виде дерева.

### Перемещение между сохранениями


Для того, чтобы перемещаться между коммитами, используется команда **_git checkout_**. Используется она в папке с пепозиторием следующим образом: git checkout <номер коммита>

### Журнал изменений


Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда **_git log_**. 
Для этого достаточно выполнить команду git log в папке с репозиторием


## Ветки в Git


_Создание ветки_.

Для того, чтобы создать ветку, используется команда **_git branch_**. Делается это следующим образом в папке с репозиторием: git branch <название новой ветки>

_Слияние веток_.

Для того чтобы дабавить ветку в текущую ветку используется команда **_git merge_**

_Удаление веток_.

Для удаления ветки ввести команду **_"git branch -d 'name branch'"cdq_**.

# Инструкция для работы с Markdown

            Выделение заголовка


Чтобы выделить текс курсивом, необходимо обрамить его звездочками или знаком нижнего подчеркивания (_)(*).

 Например *Вот так* или _вот так_.


Чтобы выделить текст полужирным,необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__) . 

Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмащать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.


                Списки


Чтобы добавить ненумерованные списки,необходимо пункты выделить звездочкой (*).

 Например, вот так:

* Элемент 1
* Элемент 2
* Элемент 3
* Элемент 4


Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.

Например, вот так:


1. Первый пункт
2. Второй пункт
3. Третий пункт


        Работа с изображениями


_Чтобы вставить изображение в текст, достаточно написать следующее:_

 восклицательный **!** знак;
квадратные скобки [ ] , в которых указывается альтернативный изображению текст (он станет содержимым атрибута в элементе img);
круглые скобки ( ) , содержащие URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённуе в двойные или одиночные кавычки.![Хурма созрела!](Хурма.jpg)


                  Ссылки 


_Markdown поддерживает упрощённый порядок автоматического создания ссылок для URL-адресов и адресов электронной почты._

 Для этого достаточно поместить URL-адрес или почтовый адрес в угловые скобки, и Markdown сделает его гиперссылкой. В отличие от вышеописанных стилей, в данном случае сам же URL-адрес или почтовый адрес становится и текстом гиперссылки. 


<http://git-scm.com/book/ru/v2/>

            
             Цитаты


Иногда какой-то абзац нужно выделить как цитату. В этом случае воспользуйтесь знаком >,обрамляя его двойными (*), знак > необходимо проставлять перед каждой строчкой цитаты. 
**>**
Например: 
> _Очень глубокомысленная цитата, прочтите её внимательно!_q
>
> Оскард Уайлд.


          Списки дел
          

 В Markdown есть даже своеобразные списки задач — аналог чекбоксов в OneNote или Evernote. Вот как они выглядят:

- [ ] Невыполненная задача
- [ ] Невыполненная задача
- [X] Выполненная задача         


         Горизонтальные линии


  Просто введите три раза (или больше) один из этих символов на клавиатуре: *, — или _, и в документ вставится горизонтальная линия. 
  
  Если строкой выше над ней стоит ещё какой-то текст, он станет заголовком первого уровня. 
  
  Линию можно использовать, чтобы разделять большие главы документа. 

***

           Зачеркнутый текст


Расширенный синтаксис Markdown GFM позволяет зачёркивать текст, заключая его в двойные тильды ~~.
~~Например~~







    

                    Эмодзи


В GFM есть ещё несколько мелочей, которые могут пригодиться вам при форматировании текста. 

Например, эмодзи. Чтобы добавить смайл, нужно напечатать соответствующий код и заключить его в двоеточия  

:kissing_heart:Добавили текс trash

:kissing_hear:

# Работа с удаленными репозиториями. 


При запуске команды _*git init*_ всё происходит только в локальном репозитории: в папке на компьютере пользователя, эту папку создавшего. Но для работы в команде программисты используют удаленные репозитории.


_**GITHUB**_


* Сервис компании Майкрософт для
организации работы удаленных
репозиториев

* Самый популярный сервис Git
* Много полезных функций
* Огромный архив различного кода.



## Как настроить совместную работу.


1. Создать аккаунт на _*GitHub*_.com

2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. _*GitHub*_ при создании нового репозитория подскажет, как это можно сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, 
вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с другого компьютера”
6. Выкачать (pull) актуальное состояние из удалённого репозитория.

## Команды





                  git clone
Копировать внешний репозиторий на свой ПК можно командой git clone.Команда git clone составная: она не только загружает все изменения, но и пытается слить все ветки на локальном компьютере и в удаленном репозитории.



                    git pull

Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией



                    gitn push 

Отправить свою версию репозитория во внешний репозиторий поможет команда git push. При первом её использовании нужна авторизация.Эта команда позволяет отправить нашу версию репозитория на внешний
репозиторий. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории.

                     pull request



 Команда для предложения изменений. Запрос на вливание изменений в репозиторий. В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду *pull request*. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала
пользователь копирует репозиторий на свой компьютер, делает *fork* репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду *pull request*. 


### Как сделать pull request


* Делаем   (ответвление) репозитория *fork*
* Делаем *git clone*   версии репозитория СВОЕЙ
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой _GitHub_
* На сайте *GitHub* нажимаем кнопку *pull request*

Продолжение следует!!!

До встречи!
С наступающим праздником!
Хорошего настроения!

 


