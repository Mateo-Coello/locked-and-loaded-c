---
title: Introducción
nav_order: 1
---

# Locked and Loaded C

## Objetivo
Hola chicos, la idea de este repo es proporcionarles una guía clara y actualizada para tener un entorno listo para aprender C/C++. 

## Motivación
Esperen, **¿por qué el repo no se llama `Locked and Loaded C++`?** La idea de empezar desde C puede ser un poco confusa, mas aún si no tienen una idea clara de lo que es un lenguaje de bajo nivel. Python un lenguaje que ya han tenido el gusto de conocer, es considerado de alto nivel. 

Pero, **¿qué es eso de alto y bajo nivel?**
Un lenguaje de programación ejecuta nuestras instrucciones de forma estructurada. Estas instrucciones se escriben de acuerdo a la sintaxis del lenguaje. Un lenguaje de alto nivel proporciona una sintaxis simple —a menudo acompañada de un tipado dinámico— que permite escribir programas de forma más rápida, sin preocuparse tanto por el manejo de la memoria. Es aquí donde se encuentra una distinción clara entre un lenguaje de alto y uno de bajo nivel: el **manejo de memoria**. 

Los lenguajes de alto nivel poseen una abstracción muy elevada en cuanto a su sintaxis, lo cual, en palabras simples, significa que nos ocultan muchos de los procesos que ocurren detrás de escena. Algunos de estos procesos incluyen la asignación de memoria para una variable según su tipo, o la asignación de memoria para un arreglo (en Python, conocido como lista). 

Como un adelanto de los conceptos que engloban a un lenguaje de bajo nivel, se encuentra el tipado estático, es decir, definir explícitamente el tipo de una variable. Por ejemplo, en Python una variable `x` que contiene un número entero como el `5` se puede escribir simplemente como `x = 5`. En un lenguaje como C, se debe especificar que nuestra variable es de tipo entero al anteponer la palabra clave `int` antes del nombre de la variable: `int x = 5;`. Si son observadores, se habrán dado cuenta de que aparece un punto y coma al final de la declaración (statement en inglés) y es porque el compilador lo requiere para determinar el fin de nuestra instrucción. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/e17e13c5-9e04-41e5-b15d-c9a8295e984e" alt="image" width="400px"/>
</p>

En términos sencillos, una declaración involucra acciones como definir una variable, definir una función o controlar el flujo del programa (por ejemplo, con if/else). A diferencia de C, en Python no es necesario incluir un `;` al final de una declaración. Sin embargo, la tabulación (indentación) y el salto de linea entre declaraciones es muy importante, ya que forma parte de la sintaxis de Python.

Ahora bien, **¿qué es un compilador?**
Seguramente han escuchado que Python es un lenguaje interpretado; es decir, utiliza un intérprete para convertir las instrucciones que escribimos a lenguaje máquina. Espero que hayan tenido la oportunidad de instalar el intérprete de Python, y no simplemente hayan utilizado un entorno como Google Colab o Jupyter Notebooks. De lo contrario, esta parte podría resultar un poco más compleja de entender. 

Todas las instrucciones que escribimos, sin importar el lenguaje de programación, son transformadas en un lenguaje entendible para el procesador de nuestra computadora (CPU). Esta transformación convierte nuestras instrucciones en código binario (`0` y `1`), lo cual el procesador puede ejecutar sin problema alguno. Este proceso de transformación se logra mediante un **intérprete** en el caso de Python, y mediante un **compilador** en el caso de C o C++. 

Un **intérprete** transforma línea por línea nuestro programa a código binario durante su ejecución. Esa es la razón por la que un lenguaje interpretado suele ser más lento, ya que a medida que se ejecuta cada línea esta recien es transformada en código binario. En contraste, un **compilador** transforma todo nuestro programa en un archivo ejecutable en lenguaje máquina antes de que el programa se ejecute. Por ello, un lenguaje compilado suele ser considerablemente más rápido, aunque cada vez que introducimos algún cambio en nuestro programa, este debe ser nuevamente compilado. 

Con todo ello en mente, estamos listos para crear un entorno listo para aprender C y eventualmente C++.
