# Proyecto 02: Currículum Vitae - HTML & CSS

Página web interactiva que funciona como currículum vitae (CV) digital, desarrollada con HTML y CSS como parte del curso de Desarrollo de Aplicaciones Web y Móviles (DAWM) en ESPOL.

## Descripción

Este proyecto presenta información profesional de manera clara, accesible y visualmente atractiva, incluyendo:

- Información de contacto y redes sociales
- Experiencia laboral
- Habilidades técnicas
- Educación
- Proyectos académicos
- Participación en eventos y conferencias
- Referencias profesionales

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica del contenido
- **CSS3**: Estilos y diseño responsivo
- **Font Awesome**: Iconos vectoriales
- **GitHub Pages**: Despliegue del sitio web

## Características Principales

### HTML Semántico
- Uso de etiquetas semánticas (`<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`)
- Estructura lógica y accesible del contenido
- Meta tags para SEO y redes sociales

### CSS Moderno
- Variables CSS para fácil personalización
- Grid y Flexbox para layouts responsivos
- Transiciones y animaciones sutiles
- Diseño Mobile-First
- Media queries para diferentes dispositivos
- Estilos de impresión optimizados

### Diseño Responsivo
- Adaptable a dispositivos móviles, tablets y escritorio
- Breakpoints: 480px, 768px, 968px
- Navegación optimizada para pantallas pequeñas

### Accesibilidad
- Contraste de colores adecuado
- Soporte para preferencias de movimiento reducido
- Estructura semántica para lectores de pantalla

## Estructura de Archivos

```
Proyecto02/
├── index.html                      # Página principal del CV
├── README.md                       # Documentación del proyecto
├── .gitignore                      # Archivos ignorados por Git
└── assets/                         # Recursos del proyecto
    ├── css/
    │   └── styles.css              # Estilos CSS
    ├── images/
    │   └── foto_perfil.png         # Foto de perfil
    └── docs/
        └── CV_JuanAndresMunizagaTorres.pdf  # CV original en PDF
```

## Despliegue en GitHub Pages

### Paso 1: Crear un Repositorio en GitHub

1. Inicia sesión en [GitHub](https://github.com)
2. Haz clic en el botón "New" para crear un nuevo repositorio
3. Nombra el repositorio (ejemplo: `cv-proyecto02`)
4. Asegúrate de que sea público
5. Haz clic en "Create repository"

### Paso 2: Subir los Archivos

#### Opción A: Usando la Interfaz Web de GitHub

1. En tu nuevo repositorio, haz clic en "uploading an existing file"
2. Arrastra y suelta los archivos `index.html` y `styles.css`
3. Escribe un mensaje de commit (ejemplo: "Subir archivos del CV")
4. Haz clic en "Commit changes"

#### Opción B: Usando Git desde la Terminal

```bash
# Navega a la carpeta del proyecto
cd "G:\My Drive\Semestres\6to Semestre\DAWM\Tareas\Proyecto02"

# Inicializa el repositorio Git
git init

# Agrega los archivos
git add index.html styles.css README.md

# Crea el primer commit
git commit -m "Agregar CV - Proyecto 02"

# Conecta con el repositorio remoto
git remote add origin https://github.com/TU_USUARIO/cv-proyecto02.git

# Sube los archivos
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a la pestaña "Settings" de tu repositorio
2. En el menú lateral izquierdo, haz clic en "Pages"
3. En "Source", selecciona la rama "main"
4. Deja la carpeta como "/ (root)"
5. Haz clic en "Save"
6. Espera unos minutos y tu sitio estará disponible en:
   ```
   https://TU_USUARIO.github.io/cv-proyecto02/
   ```

## Personalización

### Cambiar Colores

Edita las variables CSS en el archivo `styles.css`:

```css
:root {
    --primary-color: #8B5A8D;        /* Color principal */
    --primary-dark: #6B3A6D;         /* Color principal oscuro */
    --accent-color: #B8860B;         /* Color de acento */
    /* ... */
}
```

### Modificar Contenido

Edita el archivo `index.html` para actualizar:
- Información personal
- Experiencia laboral
- Habilidades
- Proyectos
- Referencias

## Requisitos del Proyecto

Este proyecto cumple con los siguientes requisitos establecidos en la documentación del curso:

- ✅ Uso de etiquetas estructurales HTML
- ✅ Implementación de HTML semántico
- ✅ Inclusión de elementos multimedia e interactivos
- ✅ Aplicación de reglas CSS
- ✅ Uso del modelo de caja (Box Model)
- ✅ Aplicación de principios de diseño
- ✅ Implementación de técnicas de layout (Grid y Flexbox)
- ✅ Enlaces a redes sociales y GitHub
- ✅ Diseño responsivo y accesible
- ✅ Despliegue en GitHub Pages

## Visualización Local

Para ver el proyecto localmente:

1. Abre el archivo `index.html` en tu navegador web preferido
2. O usa un servidor local como Live Server (extensión de VS Code)

## Autor

**Juan Andrés Munizaga Torres**
- Email: juanmuni@espol.edu.ec
- GitHub: [@Jmuniz27](https://github.com/Jmuniz27)
- LinkedIn: [jmuniz27](https://www.linkedin.com/in/jmuniz27)

## Licencia

Este proyecto fue desarrollado como parte del curso DAWM en ESPOL.

© 2025 Juan Andrés Munizaga Torres. Todos los derechos reservados.

## Referencias

- [Proyecto 02: Curriculum Vitae - HTML & CSS](https://dawm2.readthedocs.io/es/latest/proyectos/proyecto02.html)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
