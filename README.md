# TareaAD03
Aplicación de IntelliJ enlazada con Base de Datos MySQL con las tablas City, Country y Language

Menu:
1. Cargar países, ciudades y lenguas
2. Mostrar todos los países
3. Filtrar países por tipo de gobierno
4. Insertar una nueva ciudad
5. Borrar una ciudad por ID
6. Modificar el país de una ciudad
7. Salir

Para poder ejecutar cada opción del menú, he creado las siguientes carpetas:

- dao (que contiene las clases CityDAO.java, CountryDAO.java y LanguageDAO.java)
- entities (que contiene las clases City.java, Country.java y Language.java)
- services (que contiene las clases CityService.java, CountryService.java y LanguageService.java)

CLASES DAO:
1. Las clases DAO son componentes de software que se encargan de interactuar con la base de datos. Su función principal es abstraer la lógica de acceso a datos del resto de la aplicación, lo que facilita el mantenimiento y la portabilidad del código.
2. Funciones:
   - Ejecutar consultas SQL (CRUD: Crear, Leer, Actualizar, Borrar).
   - Mapear los resultados de las consultas a objetos Java (entidades).
   - Manejar excepciones relacionadas con la base de datos.
4. Establecer y gestionar la conexión a la base de datos.
5. Beneficios:
   - Separación de responsabilidades: La lógica de acceso a datos se encuentra en un solo lugar, lo que facilita su modificación y mantenimiento.
   - Reusabilidad del código: Las clases DAO se pueden reutilizar en diferentes partes de la aplicación.
   - Abstracción de la base de datos: El resto de la aplicación no necesita conocer los detalles de la base de datos, lo que permite cambiar la base de datos sin afectar el resto del código.
   - Mejora la legibilidad y organización del código.

CLASES ENTITIES:
1. Las clases de entidades son clases Java que representan objetos o conceptos del mundo real que almacenan en la base de datos. Cada entidad se corresponde con una tabla de la base de datos y sus atributos se corresponden con las columnas de la tabla.
2. Características:
  - Atributos.
  - Constructores.
  - Métodos.

CLASES SERVICES:
1. Las clases de servicios son componentes de software que contienen la lógica de la aplicación.
2. Su función principal es coordinar las operaciones entre las clases DAO y la capa de presentación.
3. Responsabilidades:
   - Recibir solicitudes de la capa de presentación.
   - Validar los datos de entrada.
   - Invocar a las clases DAO para acceder a la base de datos.
   - Realizar transformaciones o cálculos sobre los datos.
   - Devolver los resultados a la capa de presentación.
5. Beneficios:
   - Separación de responsabilidades: La lógica se encuentra en un solo lugar, lo que facilita su modificación y mantenimiento.
   - El código es reutilizable.
   - Abstracción de la capa de acceso a datos, es decir, no necesita conocer los detalles de la base de datos, entonces si se realizan cambios en ésta, el código no se ve afectado.
   - Mejora la legibilidad y organización del código.
   
