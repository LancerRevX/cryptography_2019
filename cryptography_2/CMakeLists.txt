cmake_minimum_required(VERSION 3.5)

project(cryptography_2 LANGUAGES C)

add_executable(cryptography_2 main.c)

target_link_libraries(cryptography_2 mpfr)
target_link_libraries(cryptography_2 gmp)
