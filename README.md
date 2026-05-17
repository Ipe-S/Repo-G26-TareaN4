# TechAcademy — Sitio Web de Capacitación Tecnológica Presencial

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide_Icons-F56565?style=flat&logo=lucide&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow?style=flat)

Proyecto base de una **landing page** para un instituto de capacitación tecnológica presencial. Creado con fines de práctica y aprendizaje de flujos de trabajo con **Git y GitHub**.

---

## 📋 Descripción

`index.html` es un único archivo HTML estático que simula la página de inicio de **TechAcademy**, una academia ficticia de formación tecnológica. Incluye diseño responsivo, animaciones CSS, menú móvil funcional y scroll suave, todo sin necesidad de herramientas de build.

---

## 🗂️ Estructura del Proyecto

```
techacademy/
├── index.html       # Página principal (único archivo fuente)
└── README.md        # Este archivo
```

---

## 🧩 Secciones de la Página

| Sección | Descripción |
|---|---|
| **Navbar** | Barra de navegación fija con logo, enlaces y menú hamburguesa para móvil |
| **Hero** | Sección principal con degradado animado, titular de impacto y estadísticas |
| **Cursos** | Grid de 3 tarjetas: SQL Server, Power BI y Big Data & Analytics |
| **Beneficios** | 3 columnas destacando las ventajas de la modalidad presencial |
| **Footer** | Columnas con enlaces, redes sociales, contacto y derechos de autor |

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** semántico (etiquetas `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`)
- **Tailwind CSS** `v3` via CDN — utilidades de diseño responsivo
- **Lucide Icons** `v0.441.0` via CDN — iconografía vectorial
- **Google Fonts** — tipografías Syne (display) y DM Sans (cuerpo)
- **JavaScript vanilla** — menú móvil, smooth scroll e Intersection Observer para animaciones

> ⚠️ **Nota sobre el CDN de Tailwind:** El warning `cdn.tailwindcss.com should not be used in production` es esperado. Para este proyecto de práctica el CDN es suficiente. En un proyecto real se instalaría Tailwind via CLI o PostCSS.

---

## 🚀 Cómo Ejecutar

No requiere instalación ni dependencias. Solo abre el archivo en tu navegador:

```bash
# Opción 1 — Doble clic directo
Abre index.html con cualquier navegador moderno

# Opción 2 — Con VS Code + Live Server
1. Instala la extensión "Live Server" en VS Code
2. Clic derecho sobre index.html → "Open with Live Server"

# Opción 3 — Con Python (servidor local simple)
python -m http.server 8080
# Luego abre http://localhost:8080
```

---

## 📚 Cursos Ficticios Incluidos

### 1. SQL Server para la Toma de Decisiones
- **Duración:** 40 horas (10 sesiones de 4h)
- **Modalidad:** Presencial
- **Ubicación:** Sede Centro, Aula 402
- **Inicio:** 3 Feb 2025

### 2. Power BI: Cuadros de Mando Profesionales
- **Duración:** 32 horas (8 sesiones de 4h)
- **Modalidad:** Presencial
- **Ubicación:** Sede Norte, Lab B-201
- **Inicio:** 10 Feb 2025

### 3. Big Data & Analytics Fundamentos
- **Duración:** 48 horas (12 sesiones de 4h)
- **Modalidad:** Presencial
- **Ubicación:** Sede Centro, Lab Data 105
- **Inicio:** 17 Feb 2025

---

## 🎨 Paleta de Colores

| Rol | Color | Hex |
|---|---|---|
| Fondo principal | Slate 950 | `#020617` |
| Fondo secundario | Slate 900 | `#0f172a` |
| Acento primario | Indigo 600 | `#4f46e5` |
| Acento Power BI | Violet 600 | `#7c3aed` |
| Acento Big Data | Emerald 500 | `#10b981` |
| Texto principal | Slate 100 | `#f1f5f9` |
| Texto secundario | Slate 400 | `#94a3b8` |

---

## ✅ Propósito del Proyecto (Git/GitHub)

Este repositorio está diseñado para practicar los siguientes conceptos:

- `git init` / `git clone`
- `git add` / `git commit` / `git push`
- Creación y fusión de ramas (`git branch`, `git merge`)
- Pull Requests en GitHub
- Resolución de conflictos
- Uso de `.gitignore`
- GitHub Pages para despliegue estático

---

## 🌐 Despliegue en GitHub Pages

1. Sube el repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En "Source" selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos el sitio estará disponible en:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

---

## 📄 Licencia

Proyecto de uso educativo y libre. Sin licencia comercial.  
Los datos, nombres y cursos son completamente **ficticios**.

---

*Creado como proyecto base para práctica de Git/GitHub — 2025*
