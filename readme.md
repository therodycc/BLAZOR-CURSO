# Introduccion a blazor

* ## ¿Qué es blazor?

Es una tecnología que nos permite escribir código de C# en el navegador del usuario. Es decir, que podremos escribir código de C#, y este va a correr en navegadores como Google Chrome, Firefox, Microsoft Edge, entre otros. 

* ## Este funciona gracias a una tecnologia llamada **WebAssembly**

Que nos ayuda a compilar lenguajes de alto nivel, como C#, C++, entre otros, para así poder correrlos en navegadores web.

* ## Modelos de alojamiento 

    * **Del lado del cliente**

     > la idea es que se descarga el runtime de .NET al navegador para así poder ejecutar el código de C#. Este modelo es el equivalente a los demás frameworks y librerías de JavaScript, como Angular y React. Cuando estamos creando una aplicación con este modelo, tenemos dos opciones:

     -> Blazor del lado del cliente: Que significa que solamente se va a generar el cliente

    -> Blazor alojado en ASP.NET Core: Que te genera un cliente y un backend estilo Web API en ASP.NET Core.

    * **Del lado del servidor**

    >  la aplicación se ejecuta del lado del servidor desde una aplicación de ASP.NET Core, y las actualizaciones de interfaz de usuario e interacciones se manejan a través de SignalR.


     **vamos a utilizar específicamente el Blazor alojado en ASP.NET Core, donde se nos genera el cliente y un Web API.**

     # Instalación de blazor

     Lo que debemos instalar es el sdk 
     > [link de descarga](https://dotnet.microsoft.com/learn/aspnet/blazor-tutorial/install)

     Y verificamos con el comando dotnet si ya está instalado
     > dotnet 


     # Creando nuestro primer proyecto

     1- Crear nuevo proyecto 
     
     2- 

