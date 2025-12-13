# Training Schedule Management System

A C++ based application for managing training schedules, faculty information, and course allocations.

## Features

- Admin panel for managing the system
- Faculty login and management
- Training schedule management
- Course allocation system

## Getting Started

### Prerequisites

- C++ Compiler (GCC, Clang, or MSVC)
- CMake (for building from source)

### Building the Project

```bash
# Clone the repository
git clone https://github.com/Abhimanyu-04/Schedule_Management.git

# Navigate to project directory
cd Schedule_Management/Project_Flies

# Build the project
mkdir build && cd build
cmake ..
make

# Run the application
./app
```

## Usage

1. Run the application
2. Choose between Admin or Faculty login
   - Admin credentials:
     - Username: admin
     - Password: 12345
   - Faculty credentials are stored in `data/facultyLogin.csv`

## Project Structure

- `src/` - Source code files
- `include/` - Header files
- `data/` - Data files (CSV format)

