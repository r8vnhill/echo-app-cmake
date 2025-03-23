# echo-app

**echo-app** is a minimal C++ project created as companion code for the [Build Systems](https://dibs.pages.dev) lessons from the *Diseño e Implementación de Bibliotecas de Software* course.

This project serves as a practical example to demonstrate:

- How to structure a simple C++ application
- How to configure a build system using CMake
- How to manage build artifacts and development environments with `.gitignore`
- How to evolve a project with tasks, extensions, and custom plugins

---

## 🛠 Build Instructions

To build the project using CMake:

```bash
# Create a build directory
mkdir -p build
cd build

# Generate project files and build
cmake ..
cmake --build .
```

This will generate the `echo-app` executable in the `build/` directory.

---

## 📂 Project Structure

```
.
├── CMakeLists.txt        # CMake build configuration
├── LICENSE               # BSD-style license
├── README.md             # This file
├── .gitignore            # Git ignores for multiple environments
└── src/
    └── main.cpp          # Entry point with a simple "Hello, world"
```

---

## 📚 Context

This repository is used as a teaching tool in the [dibs.pages.dev](https://dibs.pages.dev) course. You'll find progressive examples based on this code across topics like:

- Predefined and custom tasks
- Plugins and extensions
- Separation of business logic vs. application logic
- Compilation strategies for libraries and binaries
- Static analysis and documentation generation

---

## 🔒 License

Distributed under a BSD-style license. See [LICENSE](./LICENSE) for details.
