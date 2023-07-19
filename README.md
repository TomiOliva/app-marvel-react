# app-marvel-react

Marvel App

Descripción
Marvel App es una aplicación web que te permite buscar y explorar personajes de Marvel utilizando la API pública de Marvel. Puedes buscar personajes por nombre y ver sus detalles, incluyendo su imagen, descripción y más información relevante.

Captura de pantalla
![image](https://github.com/TomiOliva/app-marvel-react/assets/114250784/32cf1ca6-8211-4177-8445-cc0528ad3985)


Instalación
Clona este repositorio en tu máquina local:
bash
Copy code
git clone https://github.com/tu-usuario/marvel-app.git
Save to grepper
Entra al directorio del proyecto:
bash
Copy code
cd marvel-app
Save to grepper


Instala las dependencias:
Copy code
npm install
Save to grepper
Configuración de la API de Marvel
La aplicación utiliza la API pública de Marvel para obtener información de los personajes. Para utilizar la API, necesitarás obtener una clave de API pública y privada de Marvel.

Ve al sitio web de Marvel Developer y crea una cuenta o inicia sesión si ya tienes una.

Después de iniciar sesión, accede a "My Developer Account" y luego a "Get A Key".

Sigue las instrucciones para obtener tu clave de API pública y privada.

En el archivo src/Components/Main.js, busca la variable apiKey y reemplaza "TU_CLAVE_DE_API" y "TU_CLAVE_PRIVADA" con tus claves de API obtenidas de Marvel.

javascript
Copy code
const apiKey = "TU_CLAVE_DE_API";
const privateKey = "TU_CLAVE_PRIVADA";


Uso
Para ejecutar la aplicación en modo de desarrollo, utiliza el siguiente comando:

sql
Copy code
npm start
Save to grepper
Esto iniciará la aplicación en el navegador en http://localhost:3000.

Características
Búsqueda de personajes por nombre.
Visualización de detalles de personajes, incluyendo imagen y descripción.
Interfaz de usuario amigable y atractiva.
Tecnologías utilizadas
React
React Router
Axios
Contribución
Si deseas contribuir a este proyecto, ¡eres bienvenido! Puedes abrir un pull request con tus mejoras o correcciones.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Contacto
tomasoliva011@gmail.com

¡Gracias por usar Marvel App!

