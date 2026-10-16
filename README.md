### Tickyiyo ###

## Descripción
**Tickyiyo** es una plataforma web moderna e interactiva diseñada específicamente para la venta y gestión de tiquets para diversos eventos, conciertos y funciones. Cuenta con un sistema de inicio de sesión seguro, una interfaz visual optimizada con una paleta de colores profesional en tonos verdes y una experiencia de usuario fluida desarrollada con HTML5, CSS3 y JavaScript.

## Estructura
```text
Tickyiyo/
│
├── html/
│   ├── login.html        # Interfaz de inicio de sesión
│   └── dashboard.html    # Panel principal del sistema
│
├── css/
│   └── login.css         # Estilos y diseño visual del login
│
├── js/
│   └── login.js          # Lógica de validación de credenciales y eventos
│
└── img/
    ├── usuario.png       # Icono de usuario para la interfaz
    └── favicon/
```
Detalle de los módulos
​Módulo de Autenticación (Login):
​Permite al usuario ingresar sus credenciales (correo electrónico y contraseña).
​Incluye validación mediante JavaScript para comprobar los datos de acceso (admin@gmail.com / 123456).  
​Gestiona la redirección automática hacia el panel principal (dashboard.html) si los datos son correctos, o muestra alertas de error en caso contrario.
​Módulo de Interfaz Visual (UI/UX):
​Diseñado con un fondo de degradado profesional (verde oscuro a negro) y un contenedor central limpio con bordes redondeados y efectos interactivos en botones e inputs.  
​Incorpora tipografía moderna y recursos gráficos personalizados (favicons e iconos de usuario).
​Módulo de Navegación:
​Enlaces de retorno fluidos hacia la página principal del proyecto para facilitar la movilidad del usuario dentro del sitio web. 
