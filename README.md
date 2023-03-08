**Лабораторная работа 3**

**Задание 1**

Установим cmake (sudo apt install cmake)

Проверим установился ли он (cmake --version)

Создадим для удобства отдельную папку (mkdir TIMP_lab3)

Скопируем туда репозиторий с гитхаба (git clone)

Перейдем в директорию formatter_lib и создадим файл CMake (> CMakeLists.txt)

С помощью редактора nano откроем файл (nano CMakeLists.txt) и произведем изменения

<img width="391" alt="image" src="https://user-images.githubusercontent.com/126329578/223843490-ef7c2865-d9d4-4857-90be-03b96516585a.png">

Сделаем отдельную папку для build

mkdir build
Генерируем: cmake ../lab03/formatter_lib
Билдим cmake --build . --config Release

**Задание 2**

Перейдем в директорию formatter_ex_lib (cd formatter_ex_lib)

Создадим файл Cmake (> CMakeLists.txt)

Откроем файл в редакторе nano (nano CMakeLists.txt) и произведем изменения

<img width="527" alt="image" src="https://user-images.githubusercontent.com/126329578/223844030-edca4d53-45a8-4e28-affd-5f56b82faa16.png">

mkdir build
Генерируем: cmake ../lab03/formatter_ex_lib
Билдим cmake --build . --config Release

**Задание 3**

**Для Hello World!**

Перейдем в директорию cd hello_world_application

Создадим файл CMakeLists.txt (> CMakeLists.txt)

Откроем файл CMakeLists и внесем изменения

<img width="643" alt="image" src="https://user-images.githubusercontent.com/126329578/223844121-45eecf8d-684d-448d-a2a8-a0d59cf1fed3.png">

mkdir build
Генерируем: cmake ../lab03/hello_world-application
Билдим cmake --build . --config Release


**Для Solver**

Перейдем в директорию cd solver_application

Создадим файл CMakeLists.txt (> CMakeLists.txt)

Откроем файл и внесем изменения


mkdir build
Генерируем: cmake ../lab03/solver_application
Билдим cmake --build . --config Release

