cmake_minimum_required(VERSION 3.5)

PROJECT(hellocfc)

ADD_EXECUTABLE(hellocfc hellocfc.c)

install (TARGETS ${PROJECT_NAME} DESTINATION ${CMAKE_INSTALL_BINDIR})
