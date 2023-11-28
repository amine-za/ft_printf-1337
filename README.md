# ft_printf Project - 42 Network

## Description

This project, part of the 42 network's curriculum, aims to recreate the standard C library function `printf`. The `ft_printf` function will be able to handle various format specifiers, modifiers, and flags, just like the original `printf` function.

## Features

- Supports basic format specifiers (e.g., `%c`, `%s`, `%d`, `%x`, `%f`).
- Handles width and precision modifiers.
- Supports length modifiers (e.g., `hh`, `h`, `l`, `ll`).
- Implements some flags (e.g., `0`, `-`, `+`, `#`, ` `).
- Handles conversion of floating-point numbers with a specified precision.

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/ft_printf.git
    ```

2. Navigate to the project directory:

    bash :
    cd ft_printf
    

3. Compile the project:

    bash :
    make


4. Include the `ft_printf.h` header in your project and use the `ft_printf` function:

    #include "ft_printf.h"

    int main() {
        ft_printf("Hello, %s!\n", "world");
        return 0;
    }

5. Compile your project with the `libftprintf.a` library:

    bash :
    gcc -o my_program my_program.c libftprintf.a
    

6. Run your program:

    bash :
    ./my_program
    

## Project Structure

- `srcs/`: Contains the source code files.
- `includes/`: Contains the header files.
- `libftprintf.a`: The compiled library.
- `Makefile`: Makefile for compiling the project.

## Additional Notes

- This project was developed as part of the [42 network](https://www.42.fr/) curriculum.
- Contributions and bug reports are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
