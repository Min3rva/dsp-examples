file(GLOB SOURCES "src/*.cpp")

# Source files
add_library( image ${SOURCES} )

# Includes
target_include_directories(image PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/inc)
