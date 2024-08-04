project(test01)

add_library(${PROJECT_NAME}
SHARED
say.cpp
)
target_include_directories(${PROJECT_NAME}
PUBLIC
${Test02_Dir}
)

target_link_libraries(${PROJECT_NAME}
test02
)