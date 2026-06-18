cmake_minimum_required(VERSION 4.1)
set(CMAKE_CXX_STANDARD 20) # C++20

project(Test_CPP_Module) #工程名

add_executable(${PROJECT_NAME} "") # 生成可执行文件，这里程序名即为功能名
target_sources(${PROJECT_NAME} PRIVATE
  main.cpp
  src/module_test.cpp) # 添加源文件，这里只有一个main.cpp


