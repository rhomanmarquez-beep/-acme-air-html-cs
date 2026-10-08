# ACME AIR - Sistema de Búsqueda y Gestión de Vuelos

## Descripción del Proyecto

ACME AIR es una aplicación web interactiva desarrollada para la gestión de vuelos, reservaciones y servicios al pasajero. Permite a los clientes buscar vuelos disponibles, realizar el proceso de Check-In con datos de contacto en caso de emergencia, consultar el estado de sus trayectos y administrar su cuenta de usuario.

El proyecto está diseñado bajo estándares modernos de HTML5 y CSS3, implementando un diseño responsive adaptativo con arquitectura modular CSS (separado en gestión de formularios, estructura global, estilos adaptativos y variables generales). Esto garantiza una navegación limpia, fluida e intuitiva tanto en dispositivos móviles como en pantallas de escritorio.

---

## Características Principales

- **Gestión de Autenticación:** Inicio de sesión, registro de nuevos usuarios, recuperación y restablecimiento de contraseña.
- **Búsqueda de Vuelos:** Formulario dinámico para seleccionar origen, destino, fechas de salida y regreso, e indicar trayectos de solo ida.
- **Resultados de Búsqueda:** Visualización detallada de los vuelos encontrados con horarios, duración del trayecto, códigos de vuelo y tarifas en COP.
- **Proceso de Check-In:** Formulario para confirmación de abordaje y registro obligatorio de un contacto de emergencia.
- **Mis Vuelos:** Consulta del historial e itinerarios del usuario con estados en tiempo real (A TIEMPO, ATERRIZÓ).
- **Diseño Adaptativo:** Interfaz optimizada para pantallas pequeñas (móviles) y escritorios.

---

## Tecnologías Utilizadas

- **HTML5:** Marcado semántico para la estructura de las vistas.
- **CSS3:** Maquetación modular (Flexbox, CSS Grid) y consultas de medios (Media Queries) para la adaptabilidad.
- **Git y GitHub:** Control de versiones y trabajo colaborativo por ramas.

---

## Estructura de Archivos del Proyecto

```text
ACME-AIR/
├── css/
│   ├── forms.css        # Estilos para elementos de formulario, campos de texto, desplegables y botones
│   ├── layout.css       # Estructura del contenedor principal, tarjetas (cards) y encabezados
│   ├── responsive.css   # Reglas de adaptación para pantallas móviles y escritorios
│   └── style.css        # Estilos globales, paleta de colores, tipografías y botones base
├── img/
│   ├── logo.png         # Logotipo e imagotipo de ACME AIR
│   └── screenshots/     # Carpeta para almacenar las capturas de pantalla de la interfaz
├── Login.html           # Vista de inicio de sesión
├── registro.html        # Formulario para registro de nuevos usuarios
├── recuperar-clave.html # Formulario para solicitar restablecimiento de contraseña
├── crear-clave.html     # Formulario para crear una nueva contraseña
├── menu.html            # Menú principal de navegación para usuarios autenticados
├── buscar_vuelos.html   # Formulario de búsqueda con origen, destino y fechas
├── vuelos.html          # Vista de vuelos disponibles y precios
├── checkin.html         # Formulario de Check-In y contacto de emergencia
└── mis_vuelos.html      # Lista e historial de vuelos comprados por el usuario



Guía de Navegación del SistemaEl flujo de uso de la aplicación se divide en los siguientes módulos principales:1. Módulo de Autenticación y AccesoInicio de Sesión (Login.html): Es la pantalla inicial. Si el usuario no tiene cuenta, puede ir a registro.html. Si olvidó su clave, puede ir a recuperar-clave.html.Registro (registro.html): Formulario para ingresar nombre completo, número de identificación, correo electrónico, teléfono y ciudad. Al guardar, redirige a crear-clave.html.Recuperación de Contraseña (recuperar-clave.html y crear-clave.html): Permite enviar la solicitud de restablecimiento e ingresar una nueva contraseña.Acceso: Tras autenticarse correctamente, el usuario accede al menu.html.2. Módulo de Menú Principal (menu.html)Ofrece tres accesos principales y la opción de cerrar sesión:Buscar vuelos: Dirige al formulario de búsqueda (buscar_vuelos.html).Check In: Dirige al formulario de confirmación de abordaje (checkin.html).Mis Vuelos: Dirige al historial de itinerarios (mis_vuelos.html).Cerrar Sesión: Redirige nuevamente a Login.html.3. Módulo de Búsqueda y ResultadosBúsqueda de Vuelos (buscar_vuelos.html): Permite especificar origen, destino, fecha de salida, fecha de regreso o activar la casilla "Solo ida".Vuelos Disponibles (vuelos.html): Despliega las opciones encontradas con sus horarios (ej. 05:30 - 06:30), duración (1h 30 min), código de vuelo (ej. VAA025) y precios en COP.4. Módulo de Pasajeros y Check-InCheck-In (checkin.html): Muestra el resumen del vuelo y solicita el nombre completo y teléfono del contacto de emergencia.Mis Vuelos (mis_vuelos.html): Muestra los vuelos programados y pasados, su código, fecha, ruta y estado actual (A TIEMPO, ATERRIZÓ).Capturas de las VistasGuarda las capturas de pantalla dentro de la carpeta img/screenshots/ con los nombres de archivo señalados para que se visualicen correctamente:Módulo de AutenticaciónVistaArchivo HTMLCaptura de PantallaInicio de SesiónLogin.htmlRegistro de Usuarioregistro.htmlRecuperar Contraseñarecuperar-clave.htmlCrear Contraseñacrear-clave.htmlMódulo Principal y BúsquedaVistaArchivo HTMLCaptura de PantallaMenú Principalmenu.htmlBúsqueda de Vuelosbuscar_vuelos.htmlVuelos Disponiblesvuelos.htmlMódulo de Servicios y PasajerosVistaArchivo HTMLCaptura de PantallaCheck-Incheckin.htmlMis Vuelosmis_vuelos.html
