file(GLOB src_files "src/*.c")

idf_component_register(INCLUDE_DIRS "include" SRCS ${src_files})