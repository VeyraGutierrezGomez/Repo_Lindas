# Repo_Lindas

# Proyectos en Java – Ingeniería en Tecnologías de la Información

Este repositorio contiene una colección de proyectos desarrollados en Java como parte de prácticas académicas. Se utilizaron dos entornos de desarrollo: **IntelliJ IDEA Community Edition 2014.3.1.1** para la programación, y **Apache NetBeans IDE 17** para ejecutar proyectos con interfaz gráfica (GUI) y pruebas con base de datos.

## Tecnologías utilizadas

- **Lenguaje:** Java
- **Entorno principal de desarrollo:** IntelliJ IDEA Community Edition 2014.3.1.1
- **Ejecución de proyectos con GUI:** Apache NetBeans IDE 17
- **JDK:** Java Development Kit 17
- **Base de datos (en proyectos específicos):** MySQL vía **XAMPP**
  - Versión: xampp-windows-x64-8.2.12-0-VS16-installer
  - Interfaz: phpMyAdmin

---

## Proyectos incluidos

### Inventario_Cuarto_JELZ
Sistema de gestión de inventario personal con **interfaz gráfica** y conexión a **base de datos MySQL**. Permite registrar, visualizar, editar y eliminar objetos categorizados. Usa Java Swing para la GUI y PHPMyAdmin para gestionar la base de datos.

- Interfaz gráfica (Java Swing)
- Conexión a base de datos (XAMPP - MySQL)

### Inventario_Cuarto_VMGG
Versión local del sistema de inventario, también con **interfaz gráfica**, pero sin conexión a base de datos. Enfocado al registro visual de artículos personales usando estructuras de programación orientada a objetos.

- Interfaz gráfica (Java Swing)
- Sin conexión a base de datos

### Sistema_Bancario
Sistema bancario simulado con **interfaz gráfica**. Desarrollado exclusivamente para ejecutarse en **NetBeans**. Permite gestionar difrentes perfiles de un banco como administrador, subgerentes, usuario, app móvil y ventanilla bancaria.

- Interfaz gráfica
- Sin conexión a base de datos

### Sistema_Biblioteca_JELZ
Sistema de gestión de biblioteca **por consola**. Incluye registro de usuarios y libros, así como control básico de préstamos. Enfocado al uso de clases y lógica estructurada.

- Sin interfaz gráfica
- Sin base de datos

### Sistema_Consultorio_Medico_JELZ
Sistema completo para la gestión de citas médicas con conexión a **base de datos MySQL**. Se ejecuta en consola desde IntelliJ, pero incluye interacción con una base de datos para manejar citas, historiales, pacientes y pagos. Utiliza el servidor local **XAMPP** con phpMyAdmin.

- Interfaz gráfica
- Conexión a base de datos (XAMPP - MySQL)

---

## Instrucciones de ejecución

### Proyectos con interfaz gráfica (Inventario y Sistema Bancario)

1. Abre **Apache NetBeans IDE 17**.
2. Ve a Archivo > Abrir Proyecto y selecciona la carpeta del proyecto (descomprime el .zip si es necesario).
3. Asegúrate de tener configurado **JDK 17**.
4. Ejecuta la clase principal (Main, Formulario, etc.) o haz clic derecho en el proyecto > Run.

**Nota**: Para proyectos con base de datos (Inventario_Cuarto_JELZ), asegúrate de que el servidor **XAMPP** esté activo y que la base de datos correspondiente esté importada en phpMyAdmin.

### Proyectos con conexión a base de datos desde consola (`Sistema_Consultorio_Medico_JELZ`)

1. Abre **IntelliJ IDEA Community Edition 2014.3.1.1**.
2. Abre el proyecto correspondiente desde File > Open.
3. Asegúrate de tener XAMPP corriendo (MySQL encendido).
4. Verifica la conexión a la base de datos en el archivo de conexión (por ejemplo, Conexion.java).
5. Ejecuta la clase Main desde IntelliJ.

---

## Notas adicionales

- Todos los comentarios en el código están en español.
- Algunos textos visibles en interfaces pueden estar en inglés, según los requerimientos del diseño o la práctica.
- Todos los proyectos fueron desarrollados con fines educativos.


