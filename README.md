# Actividad 2 – Práctica Experimental

**Nombre de la actividad:** Construir una estructura web colaborativa con página principal y portafolios individuales en HTML5 – 01 APE

**Descripción:** El estudiante desarrollará, en equipo, una estructura básica de sitio web compuesta por una página principal (home) que centraliza el acceso a los portafolios individuales de cada integrante. Cada portafolio será una o dos páginas secundarias, manteniendo un diseño estandarizado y una estructura semántica consistente.

El objetivo es simular la organización de un sitio web real, aplicando buenas prácticas de HTML5, navegación y coherencia visual.

**Objetivo:** Construir una estructura web organizada utilizando HTML5, aplicando etiquetas semánticas, navegación entre páginas y consistencia en el diseño de interfaces.

**Tiempo estimado:** 2 a 3 horas

---

## Organización del repositorio

A continuación se muestra la estructura de carpetas y archivos que deben crear:

```plain
proyecto-equipo/
│
├── index.html                      # Página principal (home)
├── css/
│   └── estilo.css                  # Hoja de estilos común (consistencia visual)
│
└── portfolios/                     # Carpeta que agrupa los portafolios individuales
    ├── angel/                        # Carpeta de cada integrante
    │   ├── angel-index.html              # Página "Sobre mí" del portafolio
    │   └── angel-proyectos.html          # Página "Proyectos" del portafolio
    │
    ├── paulo/                       # Otro integrante (ejemplo)
    │   ├── paulo-index.html
    │   └── paulo-proyectos.html
    │
    └── carlos/                     # Otro integrante 
        ├── carlos-index.html
        └── carlos-proyectos.html

## Instrucciones

### 1. Trabajo en equipo
*(Coordinación grupal para la consistencia del sitio).*

### 2. Página principal (index.html)
Debe incluir:
* Estructura HTML5 completa.
* Uso de etiquetas semánticas (`header`, `nav`, `main`, `section`, `footer`).
* Título del sitio (ej. “Portafolio del equipo”).
* Lista de integrantes del equipo.
* Enlace funcional hacia el portafolio de cada integrante.
* Organización clara y ordenada del contenido.

### 3. Portafolio individual (por estudiante)
Cada integrante debe crear:
* Máximo 2 páginas HTML (ej. `sobre-mi.html`, `proyectos.html`).
* **Contenido mínimo:**
    * Presentación personal.
    * Intereses o habilidades.
    * Información académica o profesional básica.

### 4. Estandarización del diseño
Todos los portafolios deben:
* Mantener una estructura similar (mismo orden de secciones).
* Usar las mismas etiquetas semánticas.
* Tener coherencia en organización visual.
* Permitir navegación clara desde el home.

### 5. Buenas prácticas obligatorias
* Uso correcto de etiquetas HTML5.
* Indentación adecuada.
* Uso de `alt` en imágenes (si aplica).
* Enlaces funcionales.
* Nombres de archivos claros.

---

## Evidencia de entrega
Carpeta comprimida (`.zip` o `.rar`) con:
1. Página principal (`index.html`).
2. Estructura del sitio (incluye recursos utilizados y páginas de cada integrante).

---

## Rúbrica – Actividad Práctica Experimental (100 puntos)

| Criterio | Descripción | Puntaje |
| :--- | :--- | :---: |
| **Estructura del sitio web** | El sitio presenta una organización clara: home + páginas individuales correctamente vinculadas. Navegación funcional entre páginas. | 20 |
| **Página principal (home)** | Incluye listado completo de integrantes, enlaces correctos a cada portafolio y estructura semántica adecuada. | 20 |
| **Portafolio individual** | Cada estudiante presenta su contenido completo, organizado y coherente (máx. 2 páginas). | 20 |
| **Uso de HTML5 y semántica** | Uso correcto de etiquetas (`header`, `nav`, `main`, `section`, `footer`) y estructura HTML válida. | 15 |
| **Consistencia y estandarización** | Los portafolios mantienen uniformidad en estructura y organización visual. | 15 |
| **Buenas prácticas** | Código limpio, indentado, enlaces funcionales, uso de atributos como `alt` y nombres adecuados de archivos. | 10 |
| **Total** | | **100** |
