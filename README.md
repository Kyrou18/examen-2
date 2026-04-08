# Sistema de Gestión de Videojuegos

##  Descripción

Aplicación desarrollada en Java que permite gestionar videojuegos mediante operaciones CRUD (Crear, Leer, Actualizar y Eliminar), utilizando archivos de texto como almacenamiento y arquitectura por capas.

Incluye:
- Interfaz por consola
- Interfaz gráfica estilo Steam (supuestamente XD)
- Validaciones de datos
- Manejo de errores

---

##  Cómo ejecutarlo

1. Abrir el proyecto en NetBeans 28
2. Ejecutar la clase:

presentacion.Menu

o directamente:

presentacion.VentanaGUI

---

##  Estructura del proyecto

src/
├── entidades/
│   └── Videojuego.java
├── accesodatos/
│   └── VideojuegoDAO.java
├── logica/
│   └── VideojuegoService.java
└── presentacion/
    ├── Menu.java
    └── VentanaGUI.java

---

##  Tecnologías utilizadas

- Java
- Swing (interfaz gráfica)
- Archivos .txt (persistencia)
- NetBeans 28

---

## ✨ Funcionalidades

- Agregar videojuegos
- Listar videojuegos
- Buscar por ID
- Actualizar datos
- Eliminar registros
- Filtrar en tiempo real (GUI)

---

## 🎨 Diseño

La interfaz gráfica fue diseñada con estilo inspirado en Steam:
- Tema oscuro
- Tabla estilizada
- Colores profesionales
