idf_component_register(SRCS src/gif.c
                       INCLUDE_DIRS "src"
                       PRIV_INCLUDE_DIRS "include")

set_source_files_properties(SRCS src/gif.c PROPERTIES COMPILE_FLAGS -D__LINUX__)
