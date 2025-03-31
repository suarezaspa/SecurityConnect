# DeployementGuide
Inicialmente, descargar el archivo ZIP y descomprimir en la carpeta C:\xampp\htdocs.
Posteriormente, ingresar a la carpeta creada en la ruta ya establecida, crear una terminal y escribir el comando "php artisan migrate".
  Esto generará una confirmación si la base de datos "segurity" no existe, deberá ingresar "yes" en el espacio que se abre para crear la base de datos con las migraciones ya incluídas en la aplicación.
  Posteriormente, ingresar al administrador de base de datos y usar la base de datos creadas (segurity).
    En la base de datos, ir a la pestaña "SQL" e ingresar el código en la consola: 
    ´´´ 
    
    ´´´
  Luego, iniciar el servidor mediante la temrinal del editor de código de preferencia, ingresar el código "php artisan serve"
    Después de esto, ir al vínculo generado (generalmente es "http://127.0.0.1:8000")
  Esto redirige al usuario al apartado de registro de usuario, en donde el usuario ingresa los datos y estos son guardados en la base de datos.
    Luego, el usuario inicia sesión con las credenciales hechas en el registro de usuarios.
      //Esto tiene su pero, pues el rol de administrador solo puede ser creador desde la terminal en el edito de código usado. Todos los perfiles creados en el formulario son considerados como usuario común. Es decir, no             pueden acceder a las interfaces de administrador como el apartado "Gestionar Usuarios".
    
