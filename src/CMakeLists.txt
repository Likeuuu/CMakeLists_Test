project(main_test)

add_subdirectory(test01)
add_subdirectory(test02)

add_executable(${PROJECT_NAME} main.cpp)
target_include_directories(${PROJECT_NAME} 
PUBLIC
${Test01_Dir}
)

target_link_libraries(${PROJECT_NAME} 
PUBLIC
test01
)
