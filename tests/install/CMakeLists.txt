cmake_minimum_required(VERSION 3.21)
project(asio-cmake-install)
find_package(asio)
add_executable(time_t_timer time_t_timer.cpp)
target_link_libraries(time_t_timer PRIVATE asio::asio)
