# Task 3.1 Работа с директориями. Класс File
Лекция «Потоки ввода-вывода. Работа с файлами. Сериализация».  
Задача 1 - "Уставнока". 

## Описание
В данной задаче Вы потренируетесь работать с файлами и каталогами в файловой системе, используя язык Java и класс `File`, и смоделируете процесс установки игры на жесткий диск комьютера.

Предварительно вручную создайте папку `Games` в удобном для Вас месте. Имейте ввиду, что у папки `Games` должны быть права на запись и чтение. Например, в операционной системе macOS можно создать папку по следующему пути `/Users/admin/Games`. В ОС Windows можете создать папку на одном из доступных жестких дисков, например `D://Games`.

Установку программы необходимо производить из Java кода с использованием класса `File`. Процесс будет состоять из следующих этапов:
1. В папке `Games` создайте несколько директорий: `src`, `res`, `savegames`, `temp`. 
2. В каталоге `src` создайте две директории: `main`, `test`. 
3. В подкаталоге `main` создайте два файла: `Main.java`, `Utils.java`. 
4. В каталог `res` создайте три директории: `drawables`, `vectors`, `icons`.
5. В директории `temp` создайте файл `temp.txt`.

Файл `temp.txt` будет использован для записиси в него информации об успешноном или неуспешном создании файлов и директорий.  
