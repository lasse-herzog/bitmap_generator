project(bitmap_generator_lib)

set(HEADER_FILES
    drawing_utils.h
    figures.h
    printing_utils.h
    utils.h
    )

set(SOURCE_FILES
    drawing_utils.c
    figures.c
    printing_utils.c
    )

add_library(bitmap_generator_lib STATIC ${SOURCE_FILES} ${HEADER_FILES})