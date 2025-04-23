# SyncCare
El proyecto CitasMedicas parece estar relacionado con la gestión de citas médicas

Administrar citas médicas, incluyendo la programación, edición y cancelación de citas.
Manejar datos de pacientes, médicos y horarios.
Proveer una interfaz backend desarrollada principalmente con JavaScript y posiblemente frameworks o bibliotecas como Node.js para la lógica del servidor.
Usar CSS y HTML para complementar el diseño y estructura de la aplicación.

Para instalar y ejecutar el proyecto CitasMedicas, sigue estos pasos:

Instalación
Clona el repositorio:

bash
git clone https://github.com/MarinaFran/CitasMedicas.git
Navega al directorio Backend:

bash
cd CitasMedicas/Backend
Instala las dependencias:

bash
npm install
Configura las variables de entorno:

Crea un archivo .env en la raíz del directorio Backend.
Agrega las siguientes variables de entorno:
Code
PORT=3000
DB_URL=mongodb+srv://<username>:<password>@apptestingcluster.8qjuddb.mongodb.net/?retryWrites=true&w=majority
JWT_ACCESS_SECRET=<clave_secreta>
JWT_ACCESS_SECRET_EXP=1d
HOST_MAIL=<host_mail>
PORT_MAIL=<puerto_mail>
USER_MAIL=<usuario_mail>
PASS_MAIL=<contraseña_mail>
MAIL_MAIL=<correo_remitente>
Reemplaza <username>, <password> y otras claves con tus valores específicos.
Inicia el servidor:

bash
npm start
Accede a la aplicación:

El servidor estará disponible en http://localhost:<PORT>, donde <PORT> es el valor que configuraste en el archivo .env.
