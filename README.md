# C Standard Library

A complete from-scratch reimplementation of essential C standard library functions, extended with additional data structures and utilities used as a personal toolkit across all C projects.

## Implemented Functions

### String Manipulation
`ft_strlen` `ft_strcpy` `ft_strncpy` `ft_strcat` `ft_strncat` `ft_strchr` `ft_strrchr` `ft_strstr` `ft_strcmp` `ft_strncmp` `ft_strsplit` `ft_strdup` `ft_strtrim` `ft_strjoin` `ft_strsub` `ft_strnew` `ft_strdel` `ft_strclr` `ft_striter` `ft_striteri` `ft_strmap` `ft_strmapi`

### Memory
`ft_memset` `ft_bzero` `ft_memcpy` `ft_memccpy` `ft_memmove` `ft_memchr` `ft_memcmp` `ft_memalloc` `ft_memdel`

### Character Classification
`ft_isalpha` `ft_isdigit` `ft_isalnum` `ft_isascii` `ft_isprint` `ft_toupper` `ft_tolower`

### I/O
`ft_putchar` `ft_putstr` `ft_putendl` `ft_putnbr` `ft_putchar_fd` `ft_putstr_fd` `ft_putendl_fd` `ft_putnbr_fd`

### Conversion
`ft_atoi` `ft_itoa`

### Linked List (Bonus)
`ft_lstnew` `ft_lstadd` `ft_lstdel` `ft_lstdelone` `ft_lstiter` `ft_lstmap`

## Build

```bash
make        # build libft.a
make bonus  # include linked list functions
make clean  # remove objects
make fclean # remove objects + library
make re     # full rebuild
```

## Usage

```c
#include "libft.h"

char *joined = ft_strjoin("Hello, ", "World!");
ft_putendl(joined);   // Hello, World!
free(joined);
```

## Tech Stack

`C` `Static Library` `Makefile`

