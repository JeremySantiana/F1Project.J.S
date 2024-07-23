# F1 PROYECTO

## Descripción

Este proyecto es una aplicación de JavaFX que muestra resultados de pilotos y constructores en una interfaz gráfica de usuario. La aplicación se conecta a una base de datos PostgreSQL para recuperar y mostrar los datos en tablas.

## Requisitos

- JDK 8 o superior
- JavaFX
- PostgreSQL
- Biblioteca JDBC de PostgreSQL

## Configuración de la Base de Datos

1. Asegúrese de tener PostgreSQL instalado y en funcionamiento.
2. Cree una base de datos llamada `formula1`.
3. Importe o cree las tablas necesarias (`results`, `drivers`, `constructors`) con los datos correspondientes.

## Uso

1. Clone el repositorio.
2. Importe el proyecto en su IDE preferido (por ejemplo, IntelliJ IDEA, Eclipse).
3. Asegúrese de que las bibliotecas de JavaFX y JDBC estén configuradas correctamente en el proyecto.
4. Actualice las credenciales de la base de datos en los métodos `loadDriverResults` y `loadConstructorResults` si es necesario.

```java
String url = "jdbc:postgresql://localhost:2003/formula1";
String user = "postgres";
String password = "postgresql.2003";
```

## Ejecucion
![IMG-20240715-WA0092](https://github.com/user-attachments/assets/8292aeb8-a278-44e5-9ab6-6c1a4ddce45a)
![IMG-20240722-WA0471](https://github.com/user-attachments/assets/f04fd401-757b-40be-8dd4-5ce434583469)
