# Ray Tracer

This project is a Ray Tracer written in C++ that utilizes CMake for build configuration. The ray tracer simulates the way rays of light interact with objects in a scene to generate realistic images.

## Features

- Ray-object intersection
- Reflection and refraction
- Unique behaviour for different materials
- Configurable camera and lighting

## Installation

### Prerequisites

- C++ compiler (e.g., g++, msvc, clang)
- CMake (version 3.10 or higher)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/Nathan-Romero/ray-tracer.git
    cd ray-tracer
    ```

2. Build the project using CMake:
    ```sh
    cmake -B build
    cmake --build build --config Release  # Create release binaries in `build\Release`
    ```

## Usage

After building the project, you can run the ray tracer executable to render an image. The following is an example command:

```sh
./ray-tracer > image.ppm
```

## Acknowledgements

Special thanks to [Peter Shirley](https://github.com/RayTracing) for the excellent tutorial "Raytracing in One Weekend".
