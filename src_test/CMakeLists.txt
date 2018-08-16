message(WARNING "This is src_test CMakeLists!")

set(SRC main.c)
add_executable(hello ${SRC})
target_link_libraries(hello  -llt) #-lwtf)

