cmake_minimum_required(VERSION 3.0.2)
project(concert_resources)

find_package(ament_cmake REQUIRED)

install(DIRECTORY json models yaml
        DESTINATION share/${PROJECT_NAME}
)

ament_package()
