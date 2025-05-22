# 📄 get_next_line – Lectura eficiente línea por línea en C

---

## 🌟 Introducción

**get_next_line** es un proyecto fundamental del currículo de 42 Madrid, diseñado para desarrollar una función en C que permita leer un archivo o flujo de datos **línea a línea**. Esta función debe devolver cada línea completa incluyendo el salto de línea (`\n`) cuando exista, y gestionar la lectura de manera eficiente y segura, sin cargar todo el archivo en memoria.

Este proyecto pone a prueba habilidades avanzadas en gestión dinámica de memoria, manipulación de buffers, uso de variables estáticas y control de múltiples descriptores de archivo. Además, refuerza el entendimiento profundo de la interacción con el sistema operativo mediante llamadas al sistema.

---

## 🎯 Objetivos del proyecto

- Implementar la función:

  ```c
  char *get_next_line(int fd);
