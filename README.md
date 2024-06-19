# C++ Project Template with CMake

This project is a template for creating C++ projects using CMake. It provides a minimal structure to quickly get started with development.

## Project Structure
    empty_cpp_project/
    ├── CMakeLists.txt
    ├── src/
    │ └── main.cpp
    └── README.md

- `CMakeLists.txt` — the main CMake configuration file.
- `src/` — directory for source files.
- `README.md` — this file.

## Requirements

- CMake 3.10 or higher
- C++ compiler (e.g., g++, clang, or MSVC)

## Build and Run Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/ReyLegar/empty_cpp_project.git
   cd empty_cpp_project
2. Create the `build` directory:
    ```sh
    mkdir build
    cd build
3. Configure the project with CMake:
    ```sh
    cmake ..
4. Build the project:
    ```sh
    cmake --build .
5. Run the executable:
    ```sh
    ./executable_file
