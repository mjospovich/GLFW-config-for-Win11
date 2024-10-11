
# GLFW Config in Visual Studio Code for Windows 11

## Setup

### Requirements:

1. **Install 32-bit MinGW**:
   - Follow this video tutorial: [MinGW Installation Guide](https://www.youtube.com/watch?v=GxFiUEO_3zM).
   - Install the `mingw32-base` and `mingw32-gcc-g++` packages.

2. **Install `gdb` Debugger**:
   - Ensure `gdb` is installed by running `gdb --version` in the terminal (included in `mingw32-base` package).

3. **Add MinGW to your PATH**:
   - Add the MinGW `bin` directory (usually `C:\MinGW\bin`) to your system's PATH.

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mjospovich/GLFW-config-for-Win11.git
   cd GLFW-config-for-Win11
   ```

2. **Open the folder in VS Code**:
   ```bash
   code .
   ```

## Usage:

### Manually:

- `Ctrl + Shift + B` to compile the project.
- Run the program by executing `./build/main.exe`.

### Auto Compile and Run:

- `F5` to compile, debug, and run the project.
- `Ctrl + F5` to run without debugging.

## MacOS
To do this on MacOS visit this ![Github Repository](https://github.com/abotica/GLFW_mac_config/tree/main)
