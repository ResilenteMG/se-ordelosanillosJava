# Proyecto: Modelado UML - El Señor de los Anillos

Este repositorio contiene el diseño de un diagrama de clases estructurado para representar la jerarquía de personajes del universo de Tolkien. El modelo se enfoca en la correcta aplicación de conceptos de herencia y asociación.

<img width="1481" height="789" alt="Diagrama sin título-Página-1 drawio" src="https://github.com/user-attachments/assets/390a3ace-db8f-438e-a535-f7e7818fb7a6" />

## 🛠️ Avance del Diagrama

Se ha completado la arquitectura base utilizando tres niveles de profundidad para organizar la información de forma lógica:

### 🎨 Diseño Visual
* **Nivel 1 (Verde)**: Superclase `CHARACTERS` con atributos globales.
* **Nivel 2 (Naranja)**: Subclases por razas que heredan de la clase superior.
* **Nivel 3 (Blanco)**: Objetos específicos (personajes) vinculados a sus razas.

### 📋 Estructura de Datos
El diagrama cuenta actualmente con los siguientes componentes integrados:

* **Razas Modeladas**: `HUMAN`, `ELF`, `DWARF`, `WIZARD` y `HOBBIT`.
* **Personajes Finalizados**: 
    * **Humanos**: Aragorn, Boromir, Faramir.
    * **Elfos**: Legolas, Arwen, Galadriel.
    * **Enanos**: Gimli, Thorin, Balin.
    * **Magos**: Gandalf, Saruman, Radagast.
    * **Hobbits**: Frodo, Sam, Pippin.

## ⚙️ Especificaciones Técnicas
* **Atributos**: Todos los campos están tipados (`int`, `String`, `boolean`, `double`) según estándares de programación orientada a objetos.
* **Herramienta**: Diagrama desarrollado en **draw.io**.
* **Alineación**: Se utilizó una disposición en cascada para optimizar el espacio y facilitar la lectura técnica.

---
*Este proyecto fue desarrollado como parte de la tarea práctica de Modelado de Software.*




<p align="center">
  Desarrollado por <b>Melissa Gómez 💞 Developers</b> <br>
  <a href="https://www.linkedin.com/mynetwork/grow/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/ResilenteMG" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=Github&logoColor=white" alt="GitHub">
  </a>
</p>
