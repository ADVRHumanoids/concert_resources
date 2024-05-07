cmake_minimum_required(VERSION 3.5)
project(concert_resources)

find_package(ament_cmake REQUIRED)

install(DIRECTORY json models
        DESTINATION share/${PROJECT_NAME}
)

ament_package()
