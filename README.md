# *ft_printf*

## Description
This project is an implementation of the standard C library function `printf`. The goal is to recreate the basic functionality of the original `printf` while adding some custom features.

## Features
##### Mandatory
- **Format Specifiers**: Supports a variety of format specifiers, including `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, and `%X`.
##### Bonus
- **Width and Precision**: Allows specifying minimum width and precision for output.
- **Flags**: Supports various flags such as `0`, `-`, `+`, `#`, and space.
- **Modifiers**: Handles length modifiers like `hh`, `h`, `l`, `ll`, and `L`.
- **Color Formatting**: Additional feature to include color formatting in the output.

## Getting Started
### Prerequisites
The project is designed to be compatible with the 42 environment, so it's recommended to use the provided `libft` library.

### Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/marzianegro/42-ft_printf.git
    ```

2. Navigate to the project directory:

    ```bash
    cd 42-ft_printf
    ```

3. Compile the library:

    ```bash
    make
    ```

### Usage
1. Include the `ft_printf.h` header file in your project:

    ```c
    #include "ft_printf.h"
    ```

2. Call the `ft_printf` function as you would with the standard `printf`:

    ```c
    ft_printf("Hello, %s!\n", "world");
    ```

### Example
```c
#include "ft_printf.h"

int main()
{
    ft_printf("This is a simple example: %d\n", 42);
    return (0);
}
