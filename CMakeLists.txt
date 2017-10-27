find_package(Qt5 COMPONENTS Quick REQUIRED)
add_executable(qmllive main.cpp)
qt5_use_modules(qmllive Concurrent Quick)
