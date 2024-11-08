# Task Manager

Esta es una aplicación de gestión de tareas desarrollada con Flask.

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

## Contribuir
1. Haz un fork del proyecto.
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcionalidad`).
3. Haz commit de tus cambios (`git commit -am 'Agrega nueva funcionalidad'`).
4. Haz push de la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia
Este proyecto está bajo la Licencia MIT.
