> **РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ** **Факультет
> физико-математических и естественных наук** **Кафедра прикладной
> информатики и теории вероятностей**

**ОТЧЕТ**

**ПО ЛАБОРАТОРНОЙ РАБОТЕ № [2]{.underline}**

+-----------------------------------+-----------------------------------+
| *дисциплина:*                     | > *Архитектура компьютера*        |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

[Студент: Марцев Аркадий]{.underline}

Группа: НБИбд-01--23

> **МОСКВА**\
> 2023 г.

1

**Содержание**

> **1.**Цели работы -- стр. 3\
> **2.**Задание -- стр. 4\
> **3.**Выполнение лабораторной работы -- стр. 5--15 **4.**Выводы --
> стр. 16\
> **5.**Список литературы -- стр. 17

2

> **Цели работы**\
> Цель данной работы изучение контроля версий git и обучение работы с
> функциями платформы GitHub.

3

**Задание**

> •Настройка GitHub.
>
> •Базовая настройка Git.
>
> •Создание SSH-ключа.
>
> •Создание рабочего пространства и репозитория курса на основе шаблона.
>
> •Создание репозитория курса на основе шаблона.
>
> •Настройка каталога курса.
>
> •Выполнение заданий для самостоятельной работ.

4

> **Выполнение лабораторной работы Настройка GitHub**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image1.png){width="6.495832239720035in"
> height="3.945832239720035in"}
>
> Рис. 1\
> Для начала создаю учетную запись на платформе GitHub, вводя туда свои
> основные данные.
>
> **Базовая настройка Git**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image2.png){width="6.495832239720035in"
> height="3.033332239720035in"}

Рис. 2

5

> Сначала я захожу в терминал Ubuntu и с помощью команды sudo apt
> install git скачиваю пакет основных функций Linux для работы с git.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image3.png){width="6.495832239720035in"
> height="0.7611111111111111in"}
>
> Рис. 3\
> На рисунке №3 первыми двумя командами я задаю предварительную
> конфигурацию git используя команды git config --global. Первые две
> команды используются для ввода электронной почты и юзернейма
> пользователя.
>
> При помощи третьей команды настраиваю utf-8, который отвечает за
> корректное отображение сообщений git.
>
> Команда git config --global init.defaultBranch master задает имя
> начальной ветки "master"\
> Четвертая команда конвертирует CRLF в LF. CR и LF -- это символы
> которые можно использовать для обозначения разрыва строки в текстовых
> файлах.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image4.png){width="6.495832239720035in"
> height="0.24166666666666667in"}
>
> Рис. 4\
> Команда git config --global core.safecrlf warn прошу Git проверять
> преобразование на обратимость. При значении warn Git только выведет
> предупреждение, но будет принимать необратимые конвертации.

6

> **Создание SHH-ключа**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image5.png){width="6.495832239720035in"
> height="4.051388888888889in"}

Рис. 5

> Для идентификации пользователя на платформах git требуется создать
>
> SSH-ключ. Я делаю это при помощи команды srcev
>
> \<113223@pfur.ru\>" где aamarcev это юзернейм, а это электронная
> почта. Ключ сохранится в каталоге ".ssh
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image6.png){width="6.495832239720035in"
> height="3.1902777777777778in"}

Рис. 6

> Устанавливаю утилиту xclip, которая позволяет копировать содержимое
> любого файла, через команды терминала.

7

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image7.png){width="6.081944444444445in"
> height="0.225in"}
>
> Рис. 7\
> Копирую ключ из директории, в которой он сохранен.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image8.png){width="6.495832239720035in"
> height="2.011111111111111in"}
>
> Рис. 8\
> Регистрирую ключ на платформе GitHub и называю его "mySHH"
>
> **Созданиерабочегопространстваирепозиториякурсанаосновешаблона**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image9.png){width="6.495832239720035in"
> height="1.0791655730533682in"}
>
> Рис. 9\
> Командой mkdir -p \~/work/study/23-24/'Computer architecture'
> рекурсивно
>
> создаю каталог work и подкаталоги в ней. Далее командой ls проверяю
> результат работы.

8

> **Созданиерепозиториякурсанаосновешаблона**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image10.png){width="6.495832239720035in"
> height="4.137498906386702in"}
>
> Рис. 10\
> Для того чтобы создать свой репозиторий по предмету архитектура
> компьютеров и операцися по ссылке далее нажимаю use this template и
> create a new repository, чтобы овать этот шаблон.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image11.png){width="5.375in"
> height="3.1638877952755906in"}

Рис. 11

9

> На рисунке №11 я создаю свой репозиторий с названием pcacrch_NBI01-
>
> 23\. И нажимаю кнопку "Create repository" для того, чтобы завершить
> процесс создания.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image12.png){width="4.35in"
> height="4.408332239720035in"}

Рис. 12

> На странице своего репозитория перехожу во раздел code во вкладку ssh
> икопирую оттуда ссылку для клонирования.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image13.png){width="6.495832239720035in"
> height="2.661111111111111in"}

Рис. 13

> Далее копирую командой git clone --recursive и вставляю туда ссылку,
> которую скопировал со страницы своего репозитория.

10

> **Настройкакаталогакурса**
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image14.png){width="6.495832239720035in"
> height="0.19722112860892388in"}

Рис. 14

> Перехожу в каталог pcarch_NBI01-23 при помощи команды cd и удаляю
> лишние файлы командой rm.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image15.png){width="6.495832239720035in"
> height="0.5041666666666667in"}
>
> Рис. 15\
> Создаю необходимые каталоги при помощи команд echo и make.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image16.png){width="6.495832239720035in"
> height="2.4013877952755904in"}

Рис. 16

> Добавляю все созданные каталоги при помощи команды "git add ." и
>
> комментирую при помощи команды "git commit -- am 'feat (main) make
> course structure'".
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image17.png){width="6.495832239720035in"
> height="1.9347211286089239in"}

Рис. 17

> Отправляю все созданные файлы и изменения на сервер при помощи команды
> "git push".

11

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image18.png){width="6.495832239720035in"
> height="2.911111111111111in"}
>
> Рис. 18\
> Проверяю все сделанные изменения на сайте GitHub.

12

> **Выполнениезаданийдлясамостоятельнойработы**

Задание №1

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image19.png){width="6.495832239720035in"
> height="0.4in"}

Рис. 19

> Перехожу в подкаталог labs/lab02/report и создаю там файл для отчета
>
> называющийся LO2_Martsev_Report. Командой ls проверяю результат работы
> команд.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image20.png){width="6.495832239720035in"
> height="3.6958333333333333in"}

Рис. 20

> Отчет по лабораторной работе я могу оформить во встроенном в Ubuntu
> Linux текстовом редакторе LibreOffice Written Document.

Задание №2

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image21.png){width="5.891666666666667in"
> height="0.433332239720035in"}

Рис. 21

> Проверяю что файл L01_aamarcev_report.pdf сохранен в папке Downloads
> при помощи команды ls.

13

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image22.png){width="6.495832239720035in"
> height="4.069444444444445in"}

Рис. 22

> При помощи программы файлового менеджера графического дисплея
>
> дистрибутива Ubuntu переношу файл с лабораторной работой в подкаталог
> labs/lab01/report.
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image23.png){width="6.495832239720035in"
> height="0.4041666666666667in"}
>
> Рис. 23\
> Добавляю файл LO1_aamarcev_report.pdf при помощи команды git add.

14

> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image24.png){width="6.495832239720035in"
> height="3.5458333333333334in"}

Рис. 24

> Подгружаю и сохраняю изменения на сервер командой "git commit -m" и
> подтверждаю изменения при помощи команды "git push -f".
>
> ![](vertopal_9e19180039e54a0eb2358ff52cf15dab/media/image25.png){width="6.495832239720035in"
> height="3.2513877952755905in"}

Рис. 25

> На сайте GitHub проверяю все добавленные изменения и вижу, что файл с
> первой лабораторной работой добавился в правильное место.

15

> **Выводы**\
> В ходе выполнения лабораторной работы я научился работать с контролем
> версий Git, приобрел практические навыки работы с платформой GitHub и
> создания на ней свои проектов.

16

**Список литературы**

> 1.Архитектура ЭВМ -\
> \
> tattributes

17
