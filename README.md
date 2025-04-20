# student-database-crud-sqlalchemy
``
## Descripción (Description)

This project implements a basic CRUD (Create, Read, Update, Delete) system for managing student records. It utilizes SQLAlchemy as the Object Relational Mapper (ORM) to interact with the database, which is automatically created. The student data is presented visually using HTML tables rendered with Flask.

Este proyecto implementa un sistema CRUD (Crear, Leer, Actualizar, Borrar) básico para la gestión de registros de estudiantes. Utiliza SQLAlchemy como Object Relational Mapper (ORM) para interactuar con la base de datos, la cual se crea automáticamente. Los datos de los estudiantes se presentan visualmente mediante tablas HTML renderizadas con Flask.

## Cómo ejecutar (How to run)

1.  **Clonar el repositorio (Clone the repository):**
    ```bash
    git clone [https://github.com/cran/DELTD](https://github.com/cran/DELTD)
    cd [student-database-crud-sqlalchemy]
    ```

2.  **Crear un entorno virtual (Create a virtual environment) (Recomendado/Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Linux/macOS
    venv\Scripts\activate  # En Windows
    ```

3.  **Instalar las dependencias (Install dependencies):**
    ```bash
    pip install Flask SQLAlchemy
    ```

4.  **Ejecutar la aplicación Flask (Run the Flask application):**
    ```bash
    python SQLAlchemy.py
    ```
    * Flask normalmente se ejecuta en `http://127.0.0.1:5000/`.

5.  **Abrir en el navegador (Open in your browser):**
    * Ve a `http://127.0.0.1:5000/` para ver la aplicación en funcionamiento.

## Funcionalidades (Features)

* **Crear registro (Create record):** Al hacer clic en el botón "Crear Estudiante" (Create Student) o similar, **a form opens to add a new student (Name, Address, City, Postal Code).**
* **Leer registros (Read records):** La lista de estudiantes se muestra en una tabla HTML al cargar la página principal. **The list of students is displayed in an HTML table when the main page loads.**
* **Actualizar registro (Update record):** Al hacer clic en el botón "Editar" (Edit) junto a un estudiante, se abre un formulario para modificar sus datos. **By clicking the "Edit" button next to a student, a form opens to modify their data.**
* **Borrar registro (Delete record):** Al hacer clic en el botón "Borrar" (Delete) junto a un estudiante, se elimina su registro de la base de datos. **By clicking the "Delete" button next to a student, their record is deleted from the database.**
* **Base de datos con SQLAlchemy (Database with SQLAlchemy):** La base de datos se crea automáticamente utilizando SQLAlchemy. **The database is automatically created using SQLAlchemy.**
* **Interfaz web con Flask y HTML (Web interface with Flask and HTML):** La interfaz de usuario se construye con HTML y funciona mediante el framework Flask. **The user interface is built with HTML and functions using the Flask framework.**

## Estructura del proyecto (Project Structure)

```
├── SQLAlchemy.py      # Archivo principal de la aplicación Flask
├── templates/         # Contiene los archivos HTML
│   └── show_all.html
│   └── new.html
|   └── edit.html
└── README.md
```

## Notas (Notes)
* Este es un ejemplo básico de un sistema CRUD para la gestión de estudiantes utilizando SQLAlchemy para la base de datos y Flask para la interfaz web con HTML.
