# WorkerManager

A simple C++ employee management system built with CMake.

## Features

- Add employee records
- Display employee records
- Delete employee records
- Modify employee records
- Search employee records
- Sort employee records
- Clear employee records

## Project Structure

```text
.
+-- CMakeLists.txt
+-- include/
|   +-- Mangermeau.h
|   +-- boss.h
|   +-- employee.h
|   +-- manager.h
|   +-- worker.h
+-- src/
    +-- Manager.cpp
    +-- Mangermeau.cpp
    +-- WorkerManage.cpp
    +-- boss.cpp
    +-- employee.cpp
    +-- worker.cpp
```

## Requirements

- CMake 3.10 or later
- A C++ compiler, such as MinGW-w64, MSVC, or GCC

## Build

```powershell
cmake -S . -B build
cmake --build build
```

The executable will be generated in the `bin/` directory.

## Run

```powershell
.\bin\WorkerManager.exe
```

## Notes

`build/` and `bin/` are ignored by Git because they contain generated build files and runtime output.
