LINK_DIRECTORIES(/tmp/t3/lib)
INCLUDE_DIRECTORIES(/tmp/t3/include/hello)
ADD_EXECUTABLE(main main.c)
TARGET_LINK_LIBRARIES(main hello)
