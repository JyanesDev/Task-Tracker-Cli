# Task-Tracker-Cli
# Task Tracker CLI

Task Tracker CLI es una herramienta sencilla para gestionar tareas desde la línea de comandos. 

## Funcionalidades
- Agregar, actualizar y eliminar tareas.
- Marcar tareas como "en progreso" o "completadas".
- Listar tareas por estado (pendientes, en progreso, completadas).
- Persistencia de datos en un archivo JSON.

## Requisitos
- Java 11+.
- Maven.

## Instrucciones
### Clonar el repositorio

```
git clone https://github.com/tu-usuario/task-tracker-cli.git
cd task-tracker-cli
```

### Compilar el proyecto
```
mvn compile
```

### Ejecutar el CLI
```
java -cp target/classes com.jyanesdev.tasktracker.Main
```

### Comandos disponibles
```
# Agregar una tarea
add "Descripción de la tarea"

# Actualizar una tarea
update <ID> "Nueva descripción"

# Eliminar una tarea
delete <ID>

# Marcar tarea como en progreso
mark-in-progress <ID>

# Marcar tarea como realizada
mark-done <ID>

# Listar todas las tareas
list

# Listar tareas por estado
list todo
list in-progress
list done

```


