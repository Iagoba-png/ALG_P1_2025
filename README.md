Para compilación y ejecución:

-> gcc P1.c -Wall -Wextra (-lm si estás en linux)
-> ./a.out   (ejecución)
-> valgrind --leak-check=full ./a.out     (Ayuda a encontrar fugas de memoria, accesos inválidos y problemas de gestión de memoria)
