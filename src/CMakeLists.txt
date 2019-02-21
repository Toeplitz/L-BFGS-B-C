project(lbfgsb-root)
include_directories(.)
file(GLOB SOURCES "*.c")

add_library(lbfgsb STATIC ${SOURCES})

target_link_libraries(lbfgsb ${PROJECT_LINK_LIBS})
