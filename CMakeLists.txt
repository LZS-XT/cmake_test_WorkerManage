cmake_minimum_required (VERSION 3.10)

project (WorkerManager LANGUAGES CXX)

# bin目录下生成可执行文件
set (EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

# 将源码文件 .cpp的目录保存至 SRC_LIST 变量中
aux_source_directory (${PROJECT_SOURCE_DIR}/src SRC_LIST)

# 指定头文件路径
include_directories(${PROJECT_SOURCE_DIR}/include)

add_executable (WorkerManager ${SRC_LIST})
