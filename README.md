# Laboratorio-Temas-varios 💻
**Fecha:** [13/10/2001] 🗓️

## Contenido del Repositorio 📚
Este repositorio contiene la solución a un conjunto de ejercicios prácticos desarrollados en C# (.NET). El objetivo principal de la práctica es comprender y aplicar conceptos fundamentales de programación orientada a objetos y estructuras de control, tales como el uso de colecciones clave-valor (`Dictionary`), funciones recursivas, generación de números aleatorios y análisis de frecuencias con condicionales, así como la sobrecarga de métodos (*method overloading*).

## Tecnologías Utilizadas
- **Lenguaje / Framework:** C# / .NET Core (.NET SDK)
- **Base de datos:** N/A
- **Herramientas:** Visual Studio / Visual Studio Code, Git

## Capturas de Pantalla 🖥️

### Interfaz Principal
*(Incluir aquí las imágenes o capturas de la salida en consola para cada programa)*

- **Programa 1 - Manejo de Diccionarios (`Diccionario2`):**  
  Demuestra el uso de la estructura `Dictionary<string, object>` para almacenar pares clave-valor (cabeceras de usuario como ID, Usuario y Rol). Recorre e imprime únicamente las llaves (*Keys*) del diccionario mediante un bucle `foreach`.

- **Programa 2 - Cálculo Recursivo de Factorial (`Factorial`):**  
  Implementa una función recursiva `Factorial(long numero)` que calcula el factorial de un número entero largo con su correspondiente caso base (`numero <= 1`) y paso recursivo. Un ciclo `for` evalúa e imprime en consola los factoriales del 0 al 10.

- **Programa 3 - Análisis de Frecuencia de Dados (`Frecuencia`):**  
  Simula el lanzamiento de un dado de 6 caras durante 6,000 repeticiones utilizando la clase `Random`. Mediante una estructura de control `switch`, evalúa cada tiro y contabiliza la frecuencia con la que aparece cada cara, mostrando los resultados tabulados en consola.

- **Programa 4 - Sobrecarga de Métodos (`SobreCargaMetodos`):**  
  Ejemplifica el principio de sobrecarga de métodos al definir la clase `SobreCarga` con dos variantes del método `Cuadrado`: uno acepta un parámetro entero (`int`) y el otro un número decimal (`double`). El programa demuestra cómo el compilador selecciona dinámicamente la firma del método correcta en tiempo de ejecución.

## Estructura de Carpetas o Directorios

```plaintext
mi-repositorio/
├── Diccionario2/
│   └── Program.cs          # Código fuente del ejercicio con Dictionary
├── Factorial/
│   └── Program.cs          # Código fuente del cálculo recursivo del factorial
├── Frecuencia/
│   └── Program.cs          # Código fuente del simulador y contador de frecuencias
├── SobreCargaMetodos/
│   └── Program.cs          # Código fuente del ejemplo de sobrecarga de métodos
└── README.md               # Documentación general del repositorio
