# BibliotecaDigitalPatrones

## 📘 Descripción del Sistema

Este proyecto representa una Biblioteca Digital desarrollada en Java(basada en un proyecto que realize en el segundo semestre), diseñada para gestionar libros electrónicos. Permite clonar libros, recorrer su catálogo, integrarse con lectores externos (como Kindle), y presentar el contenido en distintos formatos (texto o audio). Todo esto utilizando distintos patrones de diseño de manera funcional y con propósito claro.

---

## 🎯 El Problema

Una biblioteca digital necesita ofrecer a sus usuarios:
- Copias de libros sin alterar el original (para préstamos).
- Un sistema flexible para recorrer su colección.
- Compatibilidad con lectores externos (ej. Kindle).
- Posibilidad de cambiar la forma de visualización del contenido sin modificar la lógica principal.

---

## 🧩 Patrones Aplicados

| Patrón       | Justificación                                                                 |
|--------------|--------------------------------------------------------------------------------|
| **Prototype** | Se usa para clonar libros fácilmente al momento de prestar sin alterar el original. |
| **Iterator**  | Permite recorrer el catálogo de libros sin exponer su estructura interna.     |
| **Adapter**   | Facilita la integración de sistemas externos como Kindle que usan otra interfaz. |
| **Bridge**    | Desacopla la lógica de lectura del formato visual (texto/audio), permitiendo intercambiarlos dinámicamente. |

---

## 🏗️ Estructura del Proyecto

- BibliotecaDigitalPatrones/
  - src/
    - Biblioteca.app -> codigo fuente donde se encuentran todos los patrones
  - README.md


---

## ⚙️ Instrucciones de Compilación y Ejecución

1.- Para una compilación mas simple recomiendo abrir el proyecto en un programa compilador, de recomendacion Visual Studio Code.
