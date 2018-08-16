message(WARNING "This is libs_test CMakeLists!")

set(LIB_SRC test.c)
add_library(lt SHARED ${LIB_SRC})
target_link_libraries(lt -lstdc++)

#set_target_properties(lt PROPERTIES OUTPUT_NAME "wtf")  # remap lt -> wtf


