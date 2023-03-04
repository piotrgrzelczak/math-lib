add_library(MathLib STATIC)

include(sources.cmake)

target_include_directories(MathLib
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}/Sources
)
