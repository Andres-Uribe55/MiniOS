# 🚀 Minions OS - Mini Sistema Operativo Web

## 📝 Descripción  
Minions OS es un **mini sistema operativo web** que permite a los usuarios acceder a múltiples aplicaciones de manera sencilla e intuitiva. Su diseño interactivo simula un sistema donde cada aplicación se comporta como una ventana independiente. Mediante HTML, CSS y un enfoque semántico moderno, logra una navegación fluida y organizada, mejorando la experiencia de usuario al explorar diferentes funcionalidades sin salir de la misma interfaz.

## Estructura del Proyecto  
 Minions-OS/
 ├── 📂 assets/         # Contiene imágenes, iconos y fondos de la interfaz.
 ├── 📂 styles/         # Hojas de estilo CSS para el diseño y apariencia.
 ├── 📂 apps/           # Aplicaciones dentro del sistema operativo.
 │   ├── 📂 restaurante/  # Aplicación para gestión de restaurantes.
 │   ├── 📂 musicapp/     # Plataforma para descubrir y escuchar música.
 │   ├── 📂 yogaPositions/ # Herramienta de rutinas y posturas de yoga.
 │   ├── 📂 Web_feria/    # Eventos y actividades de feria digital.
 ├── 📜 index.html       # Archivo principal que estructura la interfaz.
 ├── 📜 README.md        # Documentación del proyecto.

## Explicación del Código  
El sistema operativo está construido principalmente con **HTML y CSS**, asegurando **responsividad y accesibilidad**. Algunos aspectos clave:

1. **Interacción de Aplicaciones**  
   - Cada aplicación está dentro de un `<iframe>`, lo que permite cargar sus páginas de forma independiente.  
   - Los `<input type="checkbox">` actúan como interruptores para mostrar y ocultar los iframes según la selección del usuario.  
   - Se utiliza `:has()` en CSS para controlar la visibilidad de las aplicaciones sin necesidad de JavaScript.

2. **Estilos Responsivos**  
   - Uso de **CSS Grid y Flexbox** para una organización adaptable.  
   - Variables CSS (`--principal-color`, `--secundary-color`) para personalizar el esquema de colores.

3. **Estructura de Navegación**  
   - La sección `.apps` funciona como el "dock" del sistema operativo, donde cada aplicación tiene un icono interactivo.  
   - Al seleccionar una aplicación, el iframe correspondiente se activa y muestra su contenido.

## Instrucciones de Navegación y Despliegue  
1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/tu-repositorio/minions-os.git
   ```
2. **Abrir el proyecto**  
   - Navega hasta la carpeta del proyecto.  
   - Abre `index.html` en un navegador compatible.  
3. **Modo de uso**  
   - Haz clic en los iconos de las aplicaciones para abrirlas dentro del sistema.  
   - Puedes interactuar con cada una sin necesidad de recargar la página.  
4. **Despliegue**
   Para correr el sistema en un servidor local:  
   ```bash
   python -m http.server 8080
   ```
   Luego, accede desde `http://localhost:8080/`.

## Integrantes del Grupo  
- **Jhon Rojas**  
- **Angelica Cuervo**  
- **Omar Uribe**

## links:
- **Azure:** https://dev.azure.com/riwi-cohorte-4/Van%20Rossum/_backlogs/backlog/Van%20Rossum%20Team/Features?workitem=1913
- **Despliegue:** https://andres-uribe55.github.io/MiniOS/
