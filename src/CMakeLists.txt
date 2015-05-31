cmake_minimum_required(VERSION 2.8.11)

project(QCustomPlotWithCMAKE)

set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTOUIC ON)
set(CMAKE_INCLUDE_CURRENT_DIR ON)

find_package(Qt5Widgets REQUIRED)
find_package(QT5PrintSupport REQUIRED)

add_executable(qcustomplotwithcmake main.cpp mainwindow.cpp qcustomplot.cpp)
target_link_libraries(qcustomplotwithcmake Qt5::Widgets Qt5::PrintSupport)