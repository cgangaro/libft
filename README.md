# Libft - Your Own C Library

Libft is a project aimed at creating a custom C library of standard and useful functions. The goal is to reimplement essential C functions to better understand and utilize them.

## Guidelines
- Written in C.
- No unexpected crashes (segfaults, bus errors, etc.).
- All allocated memory must be properly freed.
- Must include a Makefile with rules: `$(NAME)`, `all`, `clean`, `fclean`, and `re`.

## Mandatory Part
Create `libft.a` containing the following functions with `ft_` prefix:
- Character checks: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- String operations: `ft_strlen`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memccpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_strlcpy`, `ft_strlcat`, `ft_toupper`, `ft_tolower`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_atoi`
- Memory allocation: `ft_calloc`, `ft_strdup`
- Additional string functions: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_itoa`, `ft_strmapi`, `ft_striteri`
- File descriptor functions: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`
- List manipulation functions: `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## Usage
You can compile the library by running `make` in the root directory.
This will create `libft.a` which you can link to your projects.

## Creator's Note
Project made with ❤️ by [**cgangaro**](https://github.com/cgangaro).

If you found this project and README helpful, please consider giving it a ⭐ and following me!

Connect with me on [LinkedIn](https://fr.linkedin.com/in/camille-gangarossa-2ab929227)!

Feel free to reach out with any questions.