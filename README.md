# Brizuvic Corp - Portal de Seguridad Industrial

Este es un demo interactivo y funcional desarrollado para **Corporación Brizuvic E.I.R.L.** (EPP, Extintores y Sistemas Contra Incendio). El proyecto está construido de forma ligera usando HTML, CSS, JavaScript y React UMD.

## Características

- **Diseño Premium**: Interfaz moderna y adaptada a la identidad corporativa industrial (colores rojo, amarillo y gris oscuro).
- **Asistente Selector de Extintores**: Un cuestionario interactivo en el Home para guiar al usuario en la elección del extintor adecuado según el tipo de riesgo.
- **Carrito de Cotizaciones Integrado**: Permite agregar múltiples productos a una lista, ajustar cantidades y generar automáticamente un mensaje detallado para el formulario de contacto.
- **Panel Administrativo (CMS)**: Un completo panel de gestión interno con gráfico SVG interactivo de ventas, CRUD de productos/servicios y visor de cotizaciones.
- **Imágenes Reales**: Activos visuales generados de forma específica para cascos, extintores, respiradores, mangueras y sinaléctica de seguridad.

## Estructura del Proyecto

- `index.html`: Punto de entrada principal (sitio público y panel CMS).
- `support.js`: Motor de ejecución React UMD y data bindings.
- `uploads/`: Carpeta de imágenes y recursos gráficos del proyecto.
- `screenshots/`: Capturas del prototipo de diseño.

## Cómo Ejecutar en Local

El proyecto no requiere ningún proceso de compilación ni dependencias complejas. Puedes abrirlo de dos formas:

1. **Directamente**: Haz doble clic sobre `index.html` para abrirlo en tu navegador web.
2. **Servidor Local (Recomendado)**: Usa una extensión como *Live Server* en VS Code, o ejecuta en tu consola:
   ```bash
   npx serve .
   ```

## Despliegue en GitHub Pages

Este repositorio está preparado para ser desplegado de forma gratuita en **GitHub Pages**:

1. Sube este proyecto a tu repositorio de GitHub.
2. En tu repositorio de GitHub, ve a **Settings** > **Pages**.
3. En la sección **Build and deployment**, selecciona la rama `main` (o `master`) y la carpeta `/root` (raíz).
4. Guarda los cambios. GitHub generará un enlace público en pocos minutos.
