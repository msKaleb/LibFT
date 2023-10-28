
## LibFt
42Cursus-libft/42Urduliz

## Key Features
This project groups in a single static library numerous replicated functions from the standard C library.
This libft version includes two fundamental projects in the common-core: get-next-line and ft_fprintf
- Get next line reads from a file descriptor (be it an actual file or the standard input) using a buffer.
it is useful for parsing information stored in a file (eg in FDF project)
- ft_fprintf: This differs from the original ft_printf in the first parameter: it takes a file descriptor.
With this file descriptor you can write to STDERR, to a file, or to the writting end of a pipe (useful in pipex or minishell)

## How To Use

```bash
# Clone this repository
$ git clone https://github.com/msKaleb/LibFT.git

# Go into the repository
$ cd LibFT

# Compile and create the static library (libft.a)
$ make / make bonus

# Now you can use it (don't forget to include the header files)
$ gcc -Wall -Werror -Wextra main.c libft.a -o program_name
```

