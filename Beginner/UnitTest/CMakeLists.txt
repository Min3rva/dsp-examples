file(GLOB SOURCES "src/*.cpp")

# Source files
add_executable( UnitTest src/imageTest.cpp )

# Includes
target_link_libraries( UnitTest image ${OpenCV_LIBS})
