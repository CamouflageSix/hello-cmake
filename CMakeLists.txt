# CMakeのバージョンを設定
cmake_minimum_required(VERSION 3.10.2)
# プロジェクト名とバージョンを設定
project(hello-cmake VERSION 0.1.0)

# a.outという実行ファイルをmain.cppとhello.cppから作成
add_executable(a.out main.cpp hello.cpp)
