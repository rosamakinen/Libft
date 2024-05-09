# Libft
##Library of C functions

In Libft I have implemented basic C functions in a library called Libft. The functions include string manipulation, datatype converting and memory management.

You can build the library by runnin Make while in the libft folder and include it in your code by adding the folder and adding #include "../libft.h" to your header file.

##From <ctype.h>
ft_isalpha - checks for an alphabetic character. <br>
ft_isdigit - checks for a digit (0 through 9).<br>
ft_isalnum - checks for an alphanumeric character.<br>
ft_isascii - checks whether c fits into the ASCII character set.<br>
ft_isprint - checks for any printable character.<br>
ft_toupper - convert char to uppercase.<br>
ft_tolower - convert char to lowercase.<br>

##From <string.h>
ft_memset - fill memory with a constant byte.<br>
ft_strlen - calculate the length of a string.<br>
ft_bzero - zero a byte string.<br>
ft_memcpy - copy memory area.<br>
ft_memmove - copy memory area.<br>
ft_strlcpy - copy string to an specific size.<br>
ft_strlcat - concatenate string to an specific size.<br>
ft_strchr - locate character in string.<br>
ft_strrchr - locate character in string.<br>
ft_strncmp - compare two strings.<br>
ft_memchr - scan memory for a character.<br>
ft_memcmp - compare memory areas.<br>
ft_strnstr - locate a substring in a string.<br>
ft_strdup - creates a dupplicate for the string passed as parameter.<br>

##From <stdlib.h>
ft_atoi - convert a string to an integer.<br>
ft_calloc - allocates memory and sets its bytes' values to 0.<br>

##Non-standard functions<br>
ft_substr - returns a substring from a string.<br>
ft_strjoin - concatenates two strings.<br>
ft_strtrim - trims the beginning and end of string with specific set of chars.<br>
ft_split - splits a string using a char as parameter.<br>
ft_itoa - converts a number into a string.<br>
ft_strmapi - applies a function to each character of a string.<br>
ft_striteri - applies a function to each character of a string.<br>
ft_putchar_fd - output a char to a file descriptor.<br>
ft_putstr_fd - output a string to a file descriptor.<br>
ft_putendl_fd - output a string to a file descriptor, followed by a new line.<br>
ft_putnbr_fd - output a number to a file descriptor.<br>
