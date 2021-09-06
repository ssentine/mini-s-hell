# mini(s)hell
A copy of BASH.

Features
pipes, semicolons, escape sequences, enviroment variables, $?, ~, redirections: > >> <

Builtins: cd, pwd, echo, export, unset, env, exit.

Signals: Ctrl-C, Ctrl-\, Ctrl-D.

Parser opens quotes ' " like in bash and handles \ even in ' " different context.

Commands work with absolute and relative paths.

Minishell writes errors to 2, output to 1 and prompt to 0. Acts as bash.

# Compile the binary
make

# Execute the binary
./minishell

<img width="661" alt="Screen Shot 2021-09-06 at 6 03 29 PM" src="https://user-images.githubusercontent.com/82203604/132236324-592f7385-6268-457a-a7f2-a813d7628eec.png">
