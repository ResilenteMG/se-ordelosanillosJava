# 🛡️ Ejercicio: Sistema de Personajes de Fantasía
Este proyecto consiste en la implementación de un sistema de clases en Java,  para gestionar diferentes razas de personajes, aplicando conceptos fundamentales de la Programación Orientada a Objetos (POO).
## 📊 Diseño del Modelo (UML)
Para planificar la estructura, utilicé Figma para diseñar el siguiente diagrama de clases:

<img width="653" height="297" alt="PERSONAJES SDLA" src="https://github.com/user-attachments/assets/c152efa7-1dc3-44b5-88f3-d7ccb23239e9" />

Nota: El diagrama muestra la relación de herencia entre la clase base y las subclases especializadas.

## 🚀 Conceptos de POO Aplicados
En este ejercicio se han trabajado tres pilares de la programación:

1. Herencia
Se definió una clase principal llamada PERSONAJES que actúa como molde. Las clases HUMANO, ELFO, ENANO y HOBBIT heredan sus características, evitando la duplicación de código.

2. Atributos y Encapsulamiento
Cada personaje cuenta con tres atributos esenciales definidos en la clase padre:

nombre: Tipo String para identificar al personaje.

edad: Tipo int para su representación numérica.

arma: Tipo String para definir su equipo de combate.

3. Polimorfismo
Se implementó el método imprimirDetalles(): void. Aunque todos los personajes tienen este método, cada raza lo utiliza de forma distinta (sobrescritura), permitiendo que un "Elfo" muestre sus datos de una manera diferente a un "Enano".

Gemini dijo
¡Entendido! Vamos a armar un README.md completo que no solo muestre el diagrama, sino que explique todo el ejercicio de forma profesional. Este lenguaje es el que suelen pedir los tutores para que el repositorio quede bien documentado.

Aquí tienes una propuesta que puedes copiar y pegar:

🛡️ Ejercicio: Sistema de Personajes de Fantasía
Este proyecto consiste en la implementación de un sistema de clases en Java (o el lenguaje que estés usando) para gestionar diferentes razas de personajes, aplicando conceptos fundamentales de la Programación Orientada a Objetos (POO).

📊 Diseño del Modelo (UML)
Para planificar la estructura, utilicé Figma para diseñar el siguiente diagrama de clases:

Nota: El diagrama muestra la relación de herencia entre la clase base y las subclases especializadas.

🚀 Conceptos de POO Aplicados
En este ejercicio se han trabajado tres pilares de la programación:

1. Herencia
Se definió una clase principal llamada PERSONAJES que actúa como molde. Las clases HUMANO, ELFO, ENANO y HOBBIT heredan sus características, evitando la duplicación de código.

2. Atributos y Encapsulamiento
Cada personaje cuenta con tres atributos esenciales definidos en la clase padre:

nombre: Tipo String para identificar al personaje.

edad: Tipo int para su representación numérica.

arma: Tipo String para definir su equipo de combate.

3. Polimorfismo
Se implementó el método imprimirDetalles(): void. Aunque todos los personajes tienen este método, cada raza lo utiliza de forma distinta (sobrescritura), permitiendo que un "Elfo" muestre sus datos de una manera diferente a un "Enano".

## 🛠️ Estructura del Código
Personaje.java: Clase abstracta/padre.

Razas/: Paquete que contiene las clases derivadas.

Main.java: Clase principal para ejecutar y probar la creación de los personajes.


---
<p align="center">
  Desarrollado por <b>Melissa Gómez 💞 Developers</b> <br>
  <a href="https://www.linkedin.com/mynetwork/grow/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/ResilenteMG" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=Github&logoColor=white" alt="GitHub">
  </a>
</p>
