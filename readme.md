# Task Manager

Esta es una aplicación de gestión de tareas desarrollada con Flask.

# Imagenes del Proyecto
![Sin nada](imagenes\primero.png)
![Con tareas](imagenes\segundo.png)
![Una tarea completada](imagenes\tercero.png)

## Características
- Crear, leer, actualizar y eliminar tareas.
- Validación de fechas para evitar asignar tareas con fechas de vencimiento en el pasado.
- Completar tareas y gestionar el estado de cada una.

## Requisitos
- Python 3.8+
- Flask
- Flask-WTF
- Flask-SQLAlchemy

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu_usuario/task-manager.git
    cd task-manager
    ```

2. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

3. Crea la base de datos:
    ```bash
    from controllers import app, db
    with app.app_context():
        db.create_all()
    ```

4. Ejecuta la aplicación:
    ```bash
    python controllers.py
    ```

## Uso

- Navega a `http://localhost:5000/tasks` para ver y administrar tus tareas.
