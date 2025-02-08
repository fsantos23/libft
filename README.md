# 📚 Libft

A custom C library implementing various standard library functions, created as part of the 42 curriculum.

## 🔍 About

Libft is a fundamental project at 42 that recreates standard C library functions along with additional utility functions for future projects. This library serves as a building block for all subsequent C programming projects at 42.

## 🛠️ Functions

### String Functions
- `ft_strlen` - Calculate string length
- `ft_strncmp` - Compare two strings
- `ft_strchr` - Locate character in string
- `ft_strrchr` - Locate character in string from the end
- `ft_strnstr` - Locate a substring in a string
- `ft_strdup` - Create a duplicate of a string
- `ft_substr` - Extract substring from string
- `ft_strjoin` - Concatenate two strings
- `ft_strtrim` - Trim beginning and end of string
- `ft_split` - Split string into array using delimiter

### Memory Functions
- `ft_memset` - Fill memory with a constant byte
- `ft_bzero` - Zero a byte string
- `ft_memcpy` - Copy memory area
- `ft_memmove` - Copy memory area with overlap handling
- `ft_memchr` - Scan memory for a character
- `ft_memcmp` - Compare memory areas
- `ft_calloc` - Allocate and zero memory

### Character Functions
- `ft_isalpha` - Check for alphabetic character
- `ft_isdigit` - Check for digit
- `ft_isalnum` - Check for alphanumeric character
- `ft_isascii` - Check for ASCII character
- `ft_isprint` - Check for printable character
- `ft_toupper` - Convert to uppercase
- `ft_tolower` - Convert to lowercase

### Number/String Conversion
- `ft_atoi` - Convert string to integer
- `ft_itoa` - Convert integer to string

### File Descriptor Functions
- `ft_putchar_fd` - Output char to file descriptor
- `ft_putstr_fd` - Output string to file descriptor
- `ft_putendl_fd` - Output string with newline to file descriptor
- `ft_putnbr_fd` - Output number to file descriptor

### Linked List Functions (Bonus)
- `ft_lstnew` - Create new list node
- `ft_lstadd_front` - Add node at beginning
- `ft_lstsize` - Count list nodes
- `ft_lstlast` - Get last node
- `ft_lstadd_back` - Add node at end
- `ft_lstdelone` - Delete node
- `ft_lstclear` - Delete list
- `ft_lstiter` - Apply function to all nodes
- `ft_lstmap` - Create new list applying function

## 📋 Requirements

- GCC compiler
- Make

## 🚀 Installation

```bash
git clone https://github.com/[your-username]/libft.git
cd libft
make
```

This will create `libft.a`.

## 💻 Usage

Include the header in your C file:
```c
#include "libft.h"
```

Compile your program with the library:
```bash
gcc your_program.c -L. -lft
```

## ⭐ Show your support

Give a ⭐️ if this project helped you!
