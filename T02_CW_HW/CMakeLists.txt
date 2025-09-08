# Вказує мінімальну версію CMake, необхідну для цього проекту

cmake_minimum_required(VERSION 3.8)

# Визначає ім'я проекту, його версію та мови програмування

project(T02_CW_HW VERSION 1.0 LANGUAGES C)

# Додає виконуваний файл до проекту, використовуючи вихідний файл

add_executable(T02_CW_HW "main.c")