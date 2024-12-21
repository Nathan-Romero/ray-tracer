# Ray Tracer

This project is a Ray Tracer written in C++ that utilizes CMake for build configuration. The ray tracer simulates the way rays of light interact with objects in a scene to generate realistic images.

## Features

- Ray-object intersection
- Phong shading model
- Reflection and refraction
- Multiple object types (spheres, planes, etc.)
- Configurable camera and lighting

## Installation

### Prerequisites

- C++ compiler (e.g., g++, clang++)
- CMake (version 3.10 or higher)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/Nathan-Romero/ray-tracer.git
    cd ray-tracer
    ```

2. Create a build directory and navigate into it:
    ```sh
    mkdir build
    cd build
    ```

3. Run CMake to configure the project:
    ```sh
    cmake ..
    ```

4. Build the project:
    ```sh
    make
    ```

## Usage

After building the project, you can run the ray tracer executable to render an image. The following is an example command:

```sh
./ray-tracer > image.ppm
```

