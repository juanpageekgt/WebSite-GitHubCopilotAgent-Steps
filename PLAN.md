# 🧭 PLAN DE DESARROLLO DEL SITIO WEB PERSONAL: Juan Pablo Ruiz

Este archivo contiene los 20 pasos organizados para crear tu sitio web personal usando GitHub Copilot Agent en VS Code, con HTML, CSS y JS. El enfoque es responsive, con modo claro/oscuro, íconos de Font Awesome, y secciones personalizadas para destacar tu perfil profesional como Ingeniero, MCT y especialista en IA.

---

## ✅ PASOS DEL PROYECTO CON PROMPTS COPILOT AGENT

### Prompt 1 - HTML base del sitio

```plaintext
Crea un archivo index.html con la estructura básica de un sitio web profesional. Incluye las siguientes secciones: 
- Header con el logo y un navbar con enlaces a: "Inicio", "Servicios", "Blog", "Contacto".
- Main para el contenido.
- Footer con redes sociales y copyright.

Usa etiquetas semánticas. Agrega el enlace a Font Awesome vía CDN y un archivo style.css en la carpeta raíz. También enlaza un archivo script.js.

Agrega un título del sitio: “Juan Pablo Ruiz - Ingeniero en Sistemas y Estratega en IA”.
```

### Prompt 2 - Estilos generales y diseño responsive

```plaintext
Crea un archivo style.css con lo siguiente:
- Define variables CSS para colores (modo claro y modo oscuro).
- Aplica diseño responsive para móviles y desktop.
- Estilo para navbar horizontal con hamburguesa en móviles.
- Tipografía moderna y legible.
- Usa la fuente ‘Inter’ desde Google Fonts.
- Agrega un botón de cambio de tema claro/oscuro con ícono de Font Awesome (sol/luna).
```

### Prompt 3 - Script para cambiar de tema

```plaintext
Crea un archivo script.js que:
- Detecte el tema preferido del sistema operativo.
- Permita cambiar entre modo claro y oscuro con un botón (ícono cambia entre sol y luna con Font Awesome).
- Guarda la preferencia del usuario en localStorage.
```

### Prompt 4 - Sección de presentación profesional

```plaintext
En el main del index.html, crea una sección de bienvenida que muestre mi nombre “Juan Pablo Ruiz”, el título “Ing.”, y un párrafo con mi experiencia profesional. 
Usa íconos de Font Awesome para destacar mis áreas: desarrollo frontend, arquitectura de software e inteligencia artificial. Usa un diseño centrado y amigable.
```

### Prompt 5 - Sección de servicios

```plaintext
Crea una sección “Servicios” con tarjetas que muestren:
- Desarrollo Frontend (ícono de laptop-code)
- Arquitectura de Software (ícono de sitemap)
- Soluciones con IA (ícono de brain)

Cada tarjeta debe tener título, ícono y descripción breve.
Diseña las tarjetas con sombras suaves, bordes redondeados y que se acomoden en grid responsive.
```

### Prompt 6 - Blog básico

```plaintext
Crea una sección “Blog” con 3 tarjetas de ejemplo para artículos. Cada tarjeta debe tener:
- Título
- Fecha
- Imagen (usa imágenes por defecto del tipo placeholder)
- Botón “Leer más”

Debe tener un diseño atractivo tipo grid y preparado para insertar enlaces a futuros artículos.
```

### Prompt 7 - Sección de contacto

```plaintext
Crea una sección “Contacto” con un formulario que tenga:
- Nombre, Email, Mensaje y un botón de enviar.
Valida los campos con JavaScript (formato de email, campos obligatorios). 
Agrega íconos de Font Awesome en los inputs. El formulario no necesita backend, solo validar al cliente.
```

### Prompt 8 - Footer con redes sociales

```plaintext
Crea un footer que incluya:
- Texto “© 2025 Juan Pablo Ruiz”
- Enlaces con íconos de Font Awesome a LinkedIn, GitHub y correo electrónico.
Estilo oscuro, con diseño limpio y centrado.
```

### Prompt 9 - Mejora UX

```plaintext
Agrega mejoras de UX:
- Scroll suave entre secciones.
- Animaciones suaves al cargar elementos.
- Accesibilidad básica (etiquetas ARIA, contraste adecuado).
Agrega esta lógica a script.js y style.css.
```

### Prompt 10 - Testimonios

```plaintext
Crea una sección “Testimonios” donde se muestren opiniones de clientes o estudiantes. Usa tarjetas con:
- Foto (opcional)
- Nombre
- Rol (por ejemplo: "Estudiante del Bootcamp", "Cliente IA")
- Comentario

Opcional: incluye carrusel automático o navegación con flechas. Usa íconos de comillas de Font Awesome.
```

### Prompt 11 - Certificaciones y reconocimientos

```plaintext
Crea una sección “Certificaciones y Reconocimientos” con tarjetas o lista de certificaciones obtenidas (por ejemplo: MCT, cursos de Microsoft, IA). Agrega los íconos correspondientes (graduation-cap, certificate) con Font Awesome.

Muestra una breve descripción y si es posible, un enlace a la certificación.
```

### Prompt 12 - Contadores animados

```plaintext
Agrega una sección con estadísticas animadas tipo contador con JS para:
- Años de experiencia
- Proyectos completados
- Estudiantes formados
- Charlas o talleres dados

Usa íconos (clock, code, users, microphone) de Font Awesome. Anima los números con JavaScript al hacer scroll.
```

### Prompt 13 - Portafolio de proyectos

```plaintext
Crea una sección “Portafolio” que muestre al menos 4 proyectos con:
- Imagen de vista previa
- Nombre del proyecto
- Tecnologías usadas
- Botón para ver más (enlace externo o popup)

Usa grid responsive. Ideal para mostrar experiencia real en frontend o IA.
```

### Prompt 14 - Calendario de eventos

```plaintext
Crea una sección “Agenda” o “Próximos eventos” con una lista de actividades o eventos con:
- Fecha
- Título del evento
- Plataforma (Zoom, YouTube, etc.)
- Botón para registrarse o asistir

Agrega íconos (calendar, video, link). Organiza cronológicamente.
```

### Prompt 15 - Página 404 personalizada

```plaintext
Crea una página 404.html con un diseño atractivo, mensaje claro y un botón para volver al inicio.
Incluye un ícono divertido (Font Awesome: exclamation-triangle o bug) y estilo coherente con el sitio.
```

### Prompt 16 - Banner de cookies

```plaintext
Agrega un banner que aparezca al cargar el sitio para solicitar consentimiento de cookies. Incluye botón “Aceptar” y un enlace a “Más información”. Guarda preferencia en localStorage para no mostrarlo de nuevo.
Estiliza discretamente con posición fija abajo.
```

### Prompt 17 - Breadcrumbs

```plaintext
Crea breadcrumbs arriba de artículos del blog o proyectos. Ejemplo: Inicio > Blog > Artículo.

Estilo discreto con separador tipo '>' y buen contraste. Íconos opcionales de house y file-alt (Font Awesome).
```

### Prompt 18 - Buscador interno

```plaintext
Agrega un input tipo búsqueda que filtre dinámicamente artículos del blog o proyectos en el portafolio. Usa JavaScript para ocultar los que no coincidan.

Estilo moderno, con ícono de lupa (Font Awesome). Ideal para mejorar UX.
```

### Prompt 19 - Modo lectura en blog

```plaintext
Crea un botón en cada artículo del blog que al activarse:
- Oculte navbar y sidebar
- Aumente tamaño de fuente
- Mejore contraste

Esto mejora la experiencia para lectores frecuentes.
```

### Prompt 20 - Descarga de CV

```plaintext
Crea una sección fija o destacada con botón “Descargar CV” y enlaces adicionales como tu perfil de LinkedIn, GitHub, YouTube.

Estilo claro, botones con íconos y acceso rápido desde la cabecera o el footer.
```

---

**🛠️ Recomendación:** Usar los prompts de manera progresiva. Puedes adaptar, combinar o dividir según el uso de GitHub Copilot Agent (máximo 50 prompts para cuentas free).

---

**Autor:** Juan Pablo Ruiz – Ing., MCT, Especialista en IA
**Sitio creado con:** HTML + CSS + JS + Font Awesome
