# CMake最低版本要求
cmake_minimum_required (VERSION 2.8)
# 项目信息
project (queue_test)
# 制定生成目标
add_executable(queue_test main.c queue.c)
