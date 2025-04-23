# SyncCare

SyncCare es una aplicación diseñada para gestionar citas médicas de forma eficiente. Permite a los usuarios (pacientes, doctores y administradores) programar, editar y cancelar citas, así como manejar datos relacionados con pacientes, médicos y horarios.

## Características Principales
- Gestión de citas médicas.
- Control de datos de pacientes, doctores y especialidades.
- Sistema de autenticación con tokens JWT.
- Backend desarrollado con Node.js y MongoDB.

## Tecnologías Utilizadas
- **Lenguajes:** JavaScript, CSS, HTML.
- **Backend:** Node.js.
- **Base de Datos:** MongoDB.
- **Frontend:** (Si aplica, puedes incluir detalles).

## Instalación

Sigue estos pasos para clonar e instalar el proyecto localmente:

1. Clona el repositorio:
   ```bash
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
