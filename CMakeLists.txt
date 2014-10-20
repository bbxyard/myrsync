project(myrsync)

add_executable(myrsync main.cpp)

install(TARGETS myrsync RUNTIME DESTINATION bin)
