# О Git
- - -
**Git Bash** — это приложение для сред Microsoft Windows, эмулирующее работу командной строки Git. Bash — аббревиатура от Bourne Again Shell. Оболочка (Shell) представляет собой приложение терминала для взаимодействия с операционной системой с помощью письменных команд. Bash — популярная оболочка, используемая по умолчанию в Linux и macOS.
- - -

## Основные команды:

**git add** - 
команда git add добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита <br>
**git status** - 
команда git status показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены <br>
**git diff** -
команда git diff используется для вычисления разницы между любыми двумя Git деревьями.<br>
**git commit** -
команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.<br>
**git rm** - 
команда git rm используется в Git для удаления файлов из индекса и рабочей копии. Она похожа на git add с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита. <br>

## Как зарегистрироваться на гитхаб?

Если у вас еще нет учетной записи GitHub, создайте ее. Откройте https://github.com в веб-браузере и нажмите кнопку " Зарегистрироваться ". Введите свой адрес электронной почты. Создайте пароль для новой учетной записи GitHub и введите имя пользователя. Затем выберите, хотите ли вы получать обновления и объявления по электронной почте, а затем нажмите кнопку "Продолжить ". <br>

## Что такое файл README.MD?
Чтобы другие пользователи, а также потенциальные клиенты или работодатели могли понять, что представляет собой проект, его нужно описать. Такое описание принято указывать в файле README.md (от англ. read — «прочитай» и me — «меня»). В этом уроке вы научитесь оформлять такие файлы. <br>
### Его необходимость:
1. Название проекта и его краткое описание: кем создан, для чего, какие решает задачи и какие закрывает проблемы. <br>
2. Технологии, которые применяются в проекте. В чём его отличие от аналогичных.<br>
3. Документация проекта — подробная инструкция о том, что представляет собой проект. <br>
4. Планы проекта, если они есть.

## Что такое SSH. Генерируем SSH-ключ

Представьте, что у вас есть ключ от двери, за которой хранится важный документ. Чтобы получить доступ к этому документу, вам нужно вставить ключ в замочную скважину и повернуть его. Поскольку ключ есть только у вас, ваш документ надёжно защищён от посторонних глаз.<br>
Чтобы получить доступ к репозиторию на GitHub, вам тоже нужно предоставить ключ, который подтверждает вашу личность и права на чтение или изменение данных. Без этого ключа доступ будет ограничен. Об этом и пойдёт речь в уроке. <br>

### Что такое SSH
Когда компьютеры обмениваются данными в сети, они следуют сетевым протоколам (англ. network protocols) — правилам обмена данными между компьютерами. <br.
Один из наиболее распространённых сетевых протоколов — SSH (от англ. Secure Shell Protocol). Он обеспечивает безопасный обмен данными в сети. С помощью этого протокола можно получать данные с удалённого компьютера или отправлять их на него. Трафик шифруется, поэтому протокол безопасен.