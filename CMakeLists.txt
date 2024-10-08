cmake_minimum_required(VERSION 3.5)

project(systa)
set(CMAKE_CPP_STANDARD 17)

add_subdirectory(src)

# Define the executable
#add_executable(systa main.cpp systa.cpp SystaCompact_II.cpp udp.cpp mqtt.cpp)
#target_link_libraries(systa mosquitto)
