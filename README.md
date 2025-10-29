EventEaseApp es una aplicación web desarrollada con Blazor para la gestión de eventos corporativos y sociales. Permite a los usuarios explorar eventos, registrarse fácilmente y a los organizadores monitorear la asistencia en tiempo real.

Características principales
- Exploración de eventos: Visualiza eventos con nombre, fecha y ubicación.
- Registro rápido: Formulario con validación para inscribirse usando nombre y correo electrónico.
- Seguimiento de asistencia: Consulta el número de personas registradas y gestiona la participación.
- Administración de sesiones: Estado de usuario y registro de asistencia en memoria.
- Página 404 personalizada: Mejor experiencia de navegación.
- Optimización de rendimiento: Renderizado virtualizado para listas grandes de eventos.

Cómo ejecutar
- Clona el repositorio.
- Abre la solución en Visual Studio o VS Code.
- Ejecuta el proyecto con dotnet run o desde el entorno de desarrollo.
- Accede a la aplicación en tu navegador en http://localhost:5000 (o el puerto configurado).

Estructura del proyecto
- /Pages: Páginas principales de la aplicación (eventos, registro, asistencia, error).
- /Components: Componentes reutilizables como la tarjeta de evento.
- /Models: Modelos de datos (evento, registro, asistencia).
- /Services: Servicios para gestión de estado y asistencia.
