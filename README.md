Guía de Usuario para el Consumo del Repositorio
Para utilizar correctamente este repositorio, sigue los pasos a continuación:

1. Instalar Node.js
Asegúrate de tener instalado la ultima version Node.js disponible en la pagina oficial en tu equipo. Puedes descargarlo desde nodejs.org.

2. Descargar el frontend
Descarga y descomprime el archivo Frontend.rar incluido en este repositorio y abrelo en Visual Studio Code.

3. Implementar la base de datos
Importa la base de datos GestionUTA en SQL Server Management Studio Developer (SSMS).

4. Configurar la cadena de conexión en el backend (Visual Studio 2022).
En el archivo de configuración del backend (Web.config), reemplaza la cadena de conexión por la correspondiente a tu servidor local.
Puedes usar la siguiente como referencia: connectionString="Data Source=DESKTOP-IVSAKBK\PA_1;Initial Catalog=GestionUTA;Integrated Security=True;Encrypt=false"
