Para compilación y ejecución:  

- Compilar: `gcc P1.c -Wall -Wextra (-lm si estás en Linux)`  
- Ejecutar: `./a.out`  
- Analizar memoria: `valgrind --leak-check=full ./a.out`    
  (Ayuda a encontrar fugas de memoria, accesos inválidos y problemas de gestión de memoria)  
