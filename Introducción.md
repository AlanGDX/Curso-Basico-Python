## Introducción 
- ### **¿Qué es Python?**
Python es un lenguaje de programación versátil, fácil de aprender y ampliamente utilizado en diversos campos de la tecnología.
Creado originalmente por: Guido Van Rossum, nombrado así por el programa de televisión de BBC 'Monty Python's Flying Circus'.

  - **Lenguaje de propósito general:** Útil para desarrollo web, ciencia de datos, inteligencia artificial, automatización, y más.
  - **Fácil de aprender:** Su sintaxis es limpia y legible, ideal para principiantes.
  - **Interpretado:** No requiere compilación, se ejecuta línea por línea, lo que facilita el desarrollo rápido.
  - **Multiplataforma:** Funciona en Windows, macOS y Linux.

- Utilizado por muchas empresas populares como:
  - *Netflix*
  - *Google*
  - *Microsoft*
  - Entre otros.

---
- ### **Características principales:**
  - Sintaxis sencilla: Muy parecida al lenguaje humano.
  - Librerías estándar: Incluye módulos para trabajar con archivos, bases de datos, matemáticas avanzadas, etc.
  - Extensibilidad: Compatible con otros lenguajes como C y C++.
  - Comunidad activa: Miles de recursos gratuitos, foros y proyectos de código abierto.

---
- ### **Usos Comunes:**
  - Desarrollo web: Frameworks como Django y Flask.
  - **Ciencia de datos:** Librerías como NumPy, Pandas y Matplotlib.
  - **Inteligencia artificial:** TensorFlow y PyTorch son herramientas populares.
  - **Automatización:** Útil para crear scripts que ahorren tiempo.
  - **Desarrollo de videojuegos:** Con Pygame, por ejemplo.

---
- ### **Herramientas y recursos útiles:**
  - Editores de código: VS Code, PyCharm o incluso Jupyter Notebooks.
  - Gestión de dependencias: Usa ```pip``` para instalar paquetes.
  - Entornos virtuales: Usa ```venv``` para aislar tus proyectos.
  - Documentación oficial: [Documentación](Python.org).

---

### **Operadores matemáticos en Python:**
| Operador | Nombre         | Ejemplo |
|----------|----------------|---------|
| +        | Adición        | 2 + 2   |
| -        | Resta          | 3 - 1   |
| *        | Multiplicación | 5 * 3   |
| /        | División       | 5 / 2   |


| Operador | Nombre         | Ejemplo |
|----------|----------------|---------|
| %        | Módulo         | 5 % 2   |
| //       | División entera | 9 // 2  |
| **       | Exponente      | 2 ** 4  |

---
### Jerarquía de operaciones
Al igual que en otros lenguajes de programación, los operadores llevan un orden basado en la aritmética básica.

Esto quiere decir que algunas operaciones se realizarán antes que otras independientemente a su posición en la fórmula.

Es así como Python procesa los operadores y números, multplicaciones y divisiones antes que sumas y restas.

Por ejemplo: 

```- 2 + 2 * 3```

Primero se realiza la multiplicación y después la suma.

Sin embargo, si son del mismo "orden" Python las elabora de izquierda a derecha:

```2 * 2 / 3```

