# 42Heilbronn :desktop_computer: :de:

## Project - Libft :books:

:white_check_mark: **125/125**

:green_circle: **Mandatory Part**

**Program name** - libft.a 
**Turn in files** - Makefile, libft.h, ft_*.c\
**Makefile**      - NAME, all, clean, fclean, re\
**External functs.** - Detailed below\
**Libft authorized** -  n/a\
**Description**      - Write your own library: a collection of functions that will be a useful tool for your cursus.

:eight_spoked_asterisk: **Part 1 - Libc functions**

Redo a set of functions from the libc. Functions have the same prototypes and implement the same behaviors as the originals.\
They comply with the way they are defined in their man. The only difference will be their names.\
They begin with the ’ft_’ prefix. For instance, strlen becomes ft_strlen.

Included functions:
- isalpha
- isdigit
- isalnum
- isascii
- isprint
- strlen
- memset
- bzero
- memcpy
- memmove
- strlcpy
- strlcat
- toupper
- tolower
- strchr
- strrchr
- strncmp
- memchr
- memcmp
- strnstr
- atoi

With using malloc():

- calloc
- strdup

:eight_spoked_asterisk: **Part 2 - Additional functions**
---
![Additional functions(1) in libft](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft001.png)
---
![Additional functions(2) in libft](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft002.png)
---
![Additional functions(3) in libft](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft003.png)
---

![Additional functions(4) in libft](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft004.png)


-----------------------------------------------------------

:yellow_circle: **Bonus part**

:eight_pointed_black_star: Functions to work with linked list:

```
typedef struct s_list
{
  void           *content;
  struct s_list  *next;
}                t_list;
```

![Additional functions(1) in libft bonus](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft_b_001.png)
----
![Additional functions(1) in libft bonus](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft_b_002.png)
----
![Additional functions(1) in libft bonus](https://github.com/Tilek12/42HN-libft/blob/master/.pics_libft/libft_b_003.png)
----

