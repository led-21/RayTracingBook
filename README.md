# RayTracingBook

This project is a practical implementation based on the classic "Ray Tracing in One Weekend" book series. Following the step-by-step approach presented in the books, the goal is to build an image renderer from scratch using ray tracing techniques, enhancing knowledge in computer graphics and programming.

## Table of Contents

* [About the Project](#about-the-project)
* [Project Structure](#project-structure)
* [Technologies Used](#technologies-used)
* [How to Run](#how-to-run)
* [References](#references)

## About the Project

The project was developed by following the book’s progression, implementing each concept and feature incrementally. Among the main topics covered are:

* Generating simple images with ray tracing.
* Modeling 3D scenes with different geometric objects.
* Implementing materials (diffuse, metallic, dielectric).
* Adding lighting and antialiasing techniques.
* Improving performance and implementing advanced features.

## Project Structure

The structure follows the evolution proposed by the book, with each chapter representing a new step or functionality in the code. Example of directories and files:

```
├── src/
│   ├── main.cpp
│   ├── ray.h
│   ├── vec3.h
│   ├── hittable.h
│   ├── sphere.h
│   ├── camera.h
│   └── ... (other files as the project evolves)
├── images/
│   └── (rendered results)
├── README.md
```

## Technologies Used

* **C++** (C++11 or higher): Main programming language for algorithm implementation.
* **GCC/Clang Compiler**: For building executables.
* **Command-line tools**: For running and visualizing results.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/led-21/RayTracingBook.git
   cd RayTracingBook
   ```

2. Compile the project:

   ```bash
   cd src
   g++ main.cpp -o raytracer -std=c++11
   ```

3. Run the renderer:

   ```bash
   ./raytracer
   ```

4. The results will be saved in the `images/` folder or displayed directly in the terminal in PPM format.

## References

* [Ray Tracing in One Weekend (Peter Shirley)](https://raytracing.github.io/)
* [Official Book Repository](https://github.com/RayTracing/raytracing.github.io)
* C++ Documentation: [https://en.cppreference.com/](https://en.cppreference.com/)

---

This project is ideal for those who want to learn the fundamentals of Ray Tracing and Computer Graphics while improving their C++ programming skills.
