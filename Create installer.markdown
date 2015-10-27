# (in English) Create installer for Mogenerator 

If missing utility **PackageMaker**:

1. Download the necessary resources from [link](http://adcdownload.apple.com/Developer_Tools/auxiliary_tools_for_xcode__late_july_2012/xcode44auxtools6938114a.dmg);
2. Unpack and copy all the files in subfolders "/Applications/Utilities". 

Create installation file for ** MOGenerator **:

1. Clone project from the [repository](https://github.com/fs/mogenerator);
2. Open the application ```Terminal```;
3. Go to the folder with the cloned repository, ```cd path / to / mogenerator```;
4. Execute the script to generate the setup files using the command ```sh install / make_installer.command```;
5. Enter the password and wait for the inscription ```[Process completed]```;
6. If the script has been completed successfully, then in the same folder must create a new folder called "build", which contains the files "mogenerator-v.dmg" and "mogenerator-v.pkg" for install.


# (на Русском) Создание установочника для Mogenerator

Если отсутствует утулита **PackageMaker**:

1. Скачиваем необходимые ресурсы по [ссылке](http://adcdownload.apple.com/Developer_Tools/auxiliary_tools_for_xcode__late_july_2012/xcode44auxtools6938114a.dmg);
2. Распаковываем и копируем все вложенные файлы в "/Applications/Utilities". 

Создание установочного файла для **MOGenerator**:

1. Клонируем проект из [репозитория](https://github.com/fs/mogenerator);
2. Открываем приложение ```Терминал```;
3. Переходим в папку с клонированным репозиторием ```cd path/to/mogenerator```;
4. Выполняем скрипт для генерации установочных файлов через команду ```sh installer/make_installer.command```;
5. Вводим пароль и ждем надписи ```[Процесс завершен]```;
6. Если скрипт выполнился успешно, то в этой же папке должна создаться новая папка с названием "build", в которой находятся файлы "mogenerator-v.dmg" и "mogenerator-v.pkg" для установки. 
