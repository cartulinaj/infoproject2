# block1infop2

A C++ project for Block 1 Informatics P2.

## Project Structure

```
block1infop2/
├── src/              # Source files (.cpp)
├── include/          # Header files (.h, .hpp)
├── tests/            # Test files
├── build/            # Build output directory
├── CMakeLists.txt    # CMake build configuration
├── Makefile          # Alternative Makefile build configuration
└── README.md         # This file
```

## Prerequisites

- C++ compiler (g++ or clang++)
- CMake 3.10 or higher (optional, for CMake build)
- Make (for Makefile build)

## Building the Project

### Option 1: Using CMake (Recommended)

```bash
# Create build directory
mkdir -p build
cd build

# Configure the project
cmake ..

# Build the project
cmake --build .

# Run the executable
./block1infop2
```

### Option 2: Using Makefile

```bash
# Build the project
make

# Run the executable
make run

# Clean build artifacts
make clean
```

### Option 3: Direct Compilation

```bash
# Compile directly with g++
g++ -std=c++17 -Wall -Wextra -Iinclude src/main.cpp -o block1infop2

# Run the executable
./block1infop2
```

## Usage

After building, run the executable:

```bash
./block1infop2
```

or from the build directory (if using CMake):

```bash
./build/block1infop2
```

## Development

To add new source files:
1. Place `.cpp` files in the `src/` directory
2. Place `.h` or `.hpp` header files in the `include/` directory
3. Update `CMakeLists.txt` if needed (for CMake builds)
4. The Makefile automatically picks up all `.cpp` files in `src/`

## Contributing

This is a university project for Block 1 Informatics P2.