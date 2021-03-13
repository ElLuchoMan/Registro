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
<img src="https://github.com/ElLuchoMan/Registro/blob/master/Vistas/DB.PNG">
