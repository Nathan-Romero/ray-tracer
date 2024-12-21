# Ray Tracer

![Final Scene](./images/jpg/final-scene.jpg)

## Overview

This project is a C++ Ray Tracer based on the book "Ray Tracing in One Weekend" by Peter Shirley. It uses CMake for build configuration and simulates the interaction of light with objects to create realistic images. The project includes features such as ray-object intersection, reflection and refraction, support for different materials, and configurable camera and lighting settings.

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
