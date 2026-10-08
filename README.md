ACME AIR - Sistema de Reserva de Vuelos

ACME AIR es una aplicación web responsiva diseñada para la gestión y reserva de vuelos. Permite a los usuarios registrarse, iniciar sesión, explorar trayectos disponibles, seleccionar fechas de viaje, realizar check-in y revisar el historial de sus vuelos programados en una interfaz moderna e intuitiva.

 Descripción del Proyecto

El sistema está construido siguiendo los estándares de diseño enfocado en dispositivos móviles (mobile-first), utilizando HTML5 semántico y CSS modular (forms.css, layout.css, responsive.css y style.css).

Características Principales:

Gestión de Cuentas: Registro de usuarios, inicio de sesión y recuperación de contraseña.

Búsqueda Personalizada: Filtros para itinerarios de solo ida o ida y vuelta.

Check-In Digital: Proceso de confirmación de vuelo y registro de contactos de emergencia.

Consulta de Vuelos: Visualización del estado actual de los vuelos asignados al usuario.

 Guía de Navegación

A continuación se detalla el flujo de navegación entre las distintas páginas del proyecto:

[ Login (Login.html) ]
  ├── ➔ ¿No tienes cuenta? ───> [ Registro (registro.html) ] ───> [ Crear Clave (crear-clave.html) ] ───> [ Menú Principal ]
  ├── ➔ ¿Olvidaste clave? ────> [ Recuperar Clave (recuperar-clave.html) ] ───> [ Crear Clave (crear-clave.html) ]
  └── ➔ Iniciar Sesión ───────> [ Menú Principal (menu.html) ]
                                    ├── ➔ Buscar Vuelos ──> [ Búsqueda (buscar_vuelos.html) ] ──> [ Vuelos Disponibles (vuelos.html) ]
                                    ├── ➔ Check In ────────> [ Check In (checkin.html) ]
                                    └── ➔ Mis Vuelos ──────> [ Mis Vuelos (mis_vuelos.html) ]


Detalle de Vistas:

Inicio de Sesión (Login.html): Punto de acceso para usuarios registrados. Permite redirigir a registro o recuperación de clave.

Registro (registro.html): Formulario para capturar los datos personales y de ubicación del nuevo usuario.

Crear / Recuperar Contraseña (crear-clave.html / recuperar-clave.html): Flujos para reestablecer credenciales de acceso.

Menú Principal (menu.html): Panel central con accesos directos a las funciones del sistema.

Búsqueda de Vuelos (buscar_vuelos.html): Formulario para seleccionar origen, destino y fechas de vuelo.

Vuelos Disponibles (vuelos.html): Lista detallada con horarios, duraciones y precios.

Check In (checkin.html): Resumen de reserva y formulario de contacto de emergencia.

Mis Vuelos (mis_vuelos.html): Historial del estado de los vuelos del usuario (a tiempo, aterrizó, etc.).

 Capturas de las Vistas

Para incluir tus capturas de pantalla, guarda las imágenes dentro de una carpeta llamada img/ o screenshots/ en la raíz de tu proyecto y asegúrate de que coincida la ruta.

1. Iniciar Sesión

2. Registro de Usuario

3. Recuperar y Crear Contraseña

Recuperar Contraseña

Crear Contraseña





4. Menú Principal

5. Búsqueda de Vuelos

6. Vuelos Disponibles

7. Check In

8. Mis Vuelos

 Tecnologías Utilizadas

HTML5: Estructuración semántica de cada una de las vistas.

CSS3: Estilos con variables CSS, Flexbox y media queries para diseño responsivo.

Git / GitHub: Control de versiones y trabajo colaborativo.
