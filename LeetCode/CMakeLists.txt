cmake_minimum_required(VERSION 3.10)

# 设置项目名称
project(LeetCode)

# 设置C++标准
set(CMAKE_CXX_STANDARD 11)

# 添加头文件搜索路径
include_directories(include)

# 添加源文件
file(GLOB SOURCES "src/*.cpp")

# 生成可执行文件
add_executable(LeetCode ${SOURCES})
