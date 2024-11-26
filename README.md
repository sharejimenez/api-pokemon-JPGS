## Angular - Consumiendo APIs
Este proyecto está desarrollado con Angular y Material Design. Integra dos APIs:

API de Escuelas: Proporciona datos de usuarios para la autenticación y visualización.
API de Pokémon: Proporciona datos de Pokémon que se pueden listar y gestionar dentro de la aplicación.
Los datos fueron extraídos utilizando services y son utilizados para distintas funcionalidades, como autenticación de usuarios y manejo de acciones en una tabla interactiva. Además, el proyecto incluye mejoras visuales y de usabilidad, como un avatar en el menú lateral, un botón de cerrar sesión y un buscador para facilitar la navegación.

## Tabla de Contenidos
Objetivo
Descripción
Características
Instalación
Estructura
Tecnologías
Pruebas
Conclusión

## Objetivo
Crear una aplicación en Angular que consuma dos APIs: una para gestionar la autenticación de usuarios y otra para listar Pokémon. Permitir al usuario interactuar con ambas funcionalidades mediante una interfaz fácil de usar.

## Descripción
Este proyecto es una aplicación Angular que demuestra cómo consumir y trabajar con múltiples APIs externas.

Autenticación de Usuarios: Se utiliza la API de Escuelas para validar las credenciales de los usuarios. Si los datos son correctos, se muestra una pantalla de bienvenida; de lo contrario, se genera una alerta con SweetAlert.
Gestión de Pokémon: A través de la API de Pokémon, se muestra una lista interactiva de Pokémon. Se incluyen acciones como editar, eliminar, y modificar (aunque estas no impactan directamente en la API).
Mejoras incluidas:

Avatar del usuario integrado en el menú lateral.
Botón de cerrar sesión.
Buscador en la tabla de Pokémon para facilitar la búsqueda.
Interfaz modernizada con Angular Material.
## Características
Consumo de dos APIs externas:
Usuarios para autenticación.
Pokémon para listar y gestionar datos.
Acciones en la tabla de Pokémon:
Eliminar.
Modificar.
Editar.
Autenticación de usuarios utilizando servicios.
Paginación para la tabla de Pokémon.
Búsqueda dinámica en la tabla de Pokémon.
Interfaz moderna con Material Design.
Rutas protegidas para la navegación.
Menú lateral con avatar del usuario.
SweetAlert para notificaciones elegantes.
Instalación
Sigue estos pasos para instalar y ejecutar el proyecto:

## Clona el repositorio:

bash
Copiar código
git clone https://github.com/sharejimenez/api-pokemon-JPGS.git
cd loginAutenticacion-JPGS
Instala las dependencias:

bash
Copiar código
npm install
Ejecuta el proyecto:

bash
Copiar código
ng serve
Accede a la aplicación desde tu navegador en http://localhost:4200.

## Estructura
Creación del proyecto en Angular:

Comando utilizado: ng new loginAutenticacion-JPGS.
Servicios:

user.service.ts: Consume la API de Escuelas.
pokemon.service.ts: Consume la API de Pokémon.
Componentes:

User List (user-list.component): Muestra la lista de usuarios.
Pokemon List (pokemon-list.component): Muestra y gestiona la lista de Pokémon.
Interfaz:

## Tabla interactiva para mostrar usuarios y Pokémon.
Menú lateral con avatar del usuario.
Tabla de Pokémon con buscador y paginación.

Angular: Framework frontend para el desarrollo de la aplicación.
RxJS: Para manejar las solicitudes HTTP y respuestas de las APIs.
Angular Material: Para componentes de interfaz como tablas, buscadores, y paginación.
NgxPagination: Para implementar la paginación en las tablas.
SweetAlert: Para mostrar alertas elegantes y funcionales.
Pruebas
Se incluyen capturas del proyecto en ejecución dentro de la carpeta imagenesPruebas.

## Conclusión
Trabajar con múltiples APIs permite aprovechar funcionalidades ya implementadas, ahorrando tiempo y esfuerzo. En este proyecto se creó una aplicación en Angular que demuestra cómo consumir APIs para gestionar usuarios y datos dinámicos como Pokémon. Además, se mejoró la usabilidad con un avatar personalizado, un buscador y acciones interactivas.

Gracias a herramientas como Angular Material y SweetAlert, fue posible diseñar una interfaz intuitiva y profesional. Este proyecto fue desarrollado en Angular y es  fácil de integrar diversas funcionalidades utilizando servicios.

