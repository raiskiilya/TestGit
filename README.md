ООП.
Домашнее задание
Реализация консольного приложения с набором методов CRUD-операций.

Начальные данные
Имеется файл с начальными данными
disney-princesses.txt
Содержащий следующие строки:

1 | Snow White | 14 | Black | Brown
2 | Cinderella | 19 | Blonde | Blue
3 | Aurora | 16 | Blonde | Violet
4 | Ariel | 16 | Red | Blue
6 | Jasmine | 16 | Black | Brown

Формат строки:
NUMBER | NAME | AGE | HAIRCOLOR | EYECOLOR

Необходимо
1.	Создать, заполнить и сохранить файл disney-princesses.txt рядом с исходным кодом приложения (как файл ресурсов)
2.	При старте приложения прочитать содержимое файла, распарсить и хранить как начальную коллекцию данных со сформированными объектами.
3.	Предоставить пользователю сообщение об успешном запуске и ожидании ввода команд.
4.	Ввод команд, обработка ввода, вывод результата
5.	Повтор шага 4, если не  введена команда exit. Иначе - шаг 6
6.	Завершение приложения.

(!) После завершение приложение содержимое файла disney-princesses.txt должно остаться прежним. Сам файл служит только начальным набором данных.

Описание команд

●	list - вывод всех сохраненных данных в удобно-читаемом формате
Пример:
<	list
>	1. Snow White
   Age: 14
   Hair: Black
   Eyes: Brown

2. Cinderella
   Age: 19
   Hair: Blonde
   Eyes: Blue

●	add - добавление новой записи.

Формат: add NUMBER NAME AGE HAIRCOLOR EYECOLOR

Пример
<	add 5 Belle 17 Brown Hazel
>	Princess “Belle” has been added.

●	get - получение записи для отображения по ее номеру

Формат: get NUMBER

Пример:
<	get 4
>	Ariel
Age: 16
Hair: Red
Eyes: Blue
>
●	update - обновление записи.

Формат: update NUMBER NAME AGE HAIRCOLOR EYECOLOR

Поиск записи для обновления идет по ее номеру, поэтому номер не должен меняться
<	update 6 Jasmine 16 Black Blue
>	Princess “Jasmine” has been updated.
>
●	delete - удаление записи.

Формат: delete NUMBER

Пример:
<	delete 2
>	Princess “Cinderella” has been removed.

●	exit - выход из приложения

* Примечание:
символы “>” и “<” не являются символами, которые необходимо вводить/выводить.
Они служат лишь указателями на то, что является “вводом”, а что “выводом”

Описание данных

●	NUMBER - целочисленное значение больше 0. Служит уникальным идентификатором записи.

●	NAME - Строковое значение от 1 до 30 символов включительно. Может содержать пробелы.

●	AGE - целочисленное значение в диапазоне от 0 до 99 включительно.

●	HAIRCOLOR - строковое значение.

Может принимать только одно из перечисленных значений:
○	Black
○	Blonde
○	Platinum-blonde
○	Strawberry-blonde
○	Red
○	Brown
●	EYECOLOR - строковое значение.

Может принимать только одно из перечисленных значений:
○	Brown
○	Blue
○	Violet
○	Hazel





git add -A
git commit -m "commit"
git push
git pull 
