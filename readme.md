# УБИЙЦА WINRAR
Простенький архиватор, который жмет все собственно разработанным алгоритмом, который подозрительно похож на учебные примеры реализации алгоритма Хаффмана
## Сборка
```
cd build
cmake .. -G "MinGW Makefiles"
cmake --build .
```
## А это поделие вообще работает?
Да.\
\
\
\
\
Примеры можно посмотреть в папке `example`\

## Пример запуска
Придумать файл с текстом. Поместить в папку с собранным проектом. Исполняемые файлы работают только при запуске с аргументами (\<inputfilename>, \<outputfilename>, \<key>).\
Если лень придумывать:\
Корпировать `example/example.txt` в папку с собранным проектом. Запустить.\
```
./zip "example.txt" "zipped_ex.txt" "key.txt"
./unzip  "zipped_ex.txt" "unzipped_ex.txt" "key.txt"
```