# proyecto_asistentes

Crea un proyecto en Laravel 5.4 con el nombre ‘proyecto_asistentes’ en el cual deberás aplicar los
siguientes conceptos.

  A. Crear una base de datos con el nombre ‘proyecto_asistentes’ y crear la conexión.
  B. Crear un login con la autenticación básica de Laravel.
  C. Haciendo uso de migraciones modificar la estructura básica de la tabla usuarios con la siguiente
     estructura:
     
        a. Tabla ‘users’
          i. id (AI, Primary key, NO NULL),
          ii. name (varchar, NO NULL),
          iii. email (varchar, NOT NULL, UNIQUE),
          iv. password (varchar, NOT NULL),
          v. ocupacion (varchar, NO NULL),
          vi. edad (int 2, NULL),
          vii. activo (int 1, NOT NULL, DEFAULT 1)
          viii. created_at (datetime, NOT NULL),
          ix. updated_at (datetime, NOT NULL)

  D. Crear una tabla haciendo uso de las migraciones con la siguiente estructura:
  
      a. Tabla ‘habilidades’
      
          i. id (AI, Primary key, NO NULL),
          ii. user_id (Int, Foreign Key),
          iii. habilidad (varchar 255, NO NULL)
          iv. created_at (datetime, NOT NULL)
          v. updated_at (datetime, NOT NULL)
