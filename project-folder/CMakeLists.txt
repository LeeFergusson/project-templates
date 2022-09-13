project(simple_example) # Create project "simple_example"
set(CMAKE_CXX_STANDARD 17) # Enable c++17 standard

# Add main.cpp file of project root directory as source file
set(SOURCE_FILES src/main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(simple_example ${SOURCE_FILES})
