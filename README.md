<h1> Registro</h1>
Registro de usuarios creado en .Net Core, MySql y Angular 11
<hr/>
           <h4>Versiones utilizadas en Back:</h4>
<li><code>Entity Framework Core v5.0.3</code>
<li><code>Entity Framework Core Tools  v5.0.3</code>
<li><code>Pomelo Entity Framework Core MySql  v5.0.0</code>
<hr/>
           <h4>Base de datos:</h4>
<li><code>MySql v8.0.23</code>
<hr/>
           <h4>Versiones utilizadas en Front:</h4>
<li> <code>Angular v11.1.3</code>
<li><code>NodeJs v12.18.4</code>
<hr/>
           <h4>Software utilizados:</h4>
<li><code> Back: Visual Studio 2019</code>
<li><code> Front: Visual Studio Code</code>
<li><code> DB: MySQL Workbench 8.0</code>
<hr/>
           <h4>Ejecución:</h4>
<ol start=1>
<li>Abra el proyecto "registro.sln" que se dentro de la carpeta back con Visual Studio 2019.
<li>Ejecute el proyecto pulsando sobre "IIS Expres" en la parte superior, esto lo redirigira a una nueva ventana de navegador.
<li>Dentro de la ventana abierta podrá visualizar "Swagger" con todos los servicios de la API, entre los que se encuentan seguido de la ruta <code>https://localhost:44368</code>:<br>
           ─GET: <code>/api/Registro/</code> → Permite visualizar un listado de todos los registros almacenados en la base de datos.<br>
           ─POST: <code>/api/Registro/</code> → Permite almacenar registros en la base de datos.<br>
           ─GET: <code>/api/Registro/id</code> → Permite visualizar un único registro correspondiente a la id ingresada, en caso de requerirse.<br>
           ─PUT: <code>/api/Registro/id</code> → Permite actualizar un único registro correspondiente a ala id ingresada, en caso de requerirse.<br>
           -DELETE: <code>/api/Registro/id</code> → Permite eliminar un único registro correspondiente a ala id ingresada, en caso de requerirse.<br>
<li>Abra la carpeta registro que se encuentra dentro de la carpeta front en la terminal de Visual Studio Code, en la PowerShell de Windows, o en la terminal de su sistema 
operativo.
<li>Ejecute el comando <code>ng serve -o</code> para que el proyecto se abra en una ventana de navegador en cuanto esté disponible.
<li>El proyecto ya está listo para realizar su prueba.
</ol>
           <h4>Vistas:</h4>
           <h5>Formulario inválido</h5>
<img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/FormularioInválido.PNG">
           <p> Cuando el formulario ha sido tocado o contiene información en formato incorrecto, el botón de registrar no se activa y lanza una alerta sobre el campo inválido
                      indicando el error.</p>
<h5>Registro exitoso</h5>
       <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/RegistroExitoso.png"> 
           <p>Cuando la información es correcta y se logra almacenar el registro en la base de datos, se muestra un mensaje de éxito.</p>
   <h5>Registro fallido</h5>
       <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/Registro%20fallido.png"> 
           <p>Cuando la información es incorrecta o no se puede tener acceso a la base de datos, se muestra un mensaje de error.</p>    
              <h5>Lista Vacía</h5>
       <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/ListaVacía.PNG"> 
           <p>Cuando no se encuentra información registrada en la base de datos, la lista se visualizará vacía.</p>  
           <h5>Base de datos</h5>
           <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/DB.PNG"> 
           <p>Información almacenada en la base de datos.</p>
           <h5>Lista Normal</h5>
           <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/Listado%20normal.PNG"> 
           <p>Cuando se encuentra información registrada en la base de datos y no se ha aplicado ningún filtro, la lista se visualiza en orden de registro.</p>
           <h5>Filtro por Nombre</h5>
           <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/Listado%20por%20nombre.PNG"> 
           <p>Cuando se hace click sobre el botón "Por nombre" se filtra el listado por orden alfabético de A a Z.</p>
           <h5>Filtro por Documento</h5>
           <img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/Listado%20por%20documento.PNG"> 
           <p>Cuando se hace click sobre el botón "Por documento" se filtra el listado por orden de documento, del número más grande al más pequeño lo que se puede 
           interpretar como filtro de "Más joven a más viejo".</p>
