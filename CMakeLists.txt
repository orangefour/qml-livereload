find_package(Qt5 COMPONENTS Concurrent Quick REQUIRED)
add_executable(qmllive main.cpp)
target_link_libraries(qmllive Qt::Concurrent Qt::Quick)
