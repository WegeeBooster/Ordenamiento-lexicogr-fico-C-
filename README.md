# Ordenamiento lexicográfico

# Sobre el código
Este código en C++ genera todas las r-combinaciones posibles del conjunto "{1, 2, ..., n}", ordenadas de forma lexicográfica. El programa pide al usuario los valores de "n" y "r", valida la entrada, genera las combinaciones y las guarda en un archivo CSV. Al terminar, verifica que el número de combinaciones generadas coincida con el valor calculado mediante el coeficiente binomial "C(n, r)".

# Autor
Jorge Alejandro Montaño Gutierrez

# Fecha
12 de Abril de 2025

# Requisitos del sistema
- Un compilador C++ compatible con C++11 o superior.
- Sistema operativo: Windows, Linux o macOS.

## Instrucciones de compilación y ejecución
```bash
g++ -std=c++11 -o combinaciones combinaciones.cpp
./combinaciones
