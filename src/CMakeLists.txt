add_library(dynamicarray INTERFACE)
install(TARGETS dynamicarray RUNTIME CONFIGURATIONS Release)
install(FILES ${PROJECT_SOURCE_DIR}/include/dynamic_array.h ${PROJECT_SOURCE_DIR}/include/dynamic_array_impl.h ${PROJECT_SOURCE_DIR}/include/_array_macros.h TYPE INCLUDE)
