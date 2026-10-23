# 🌿 EcoMarket

Tienda en línea de productos ecológicos, reutilizables y sustentables. Proyecto de maquetación web desarrollado con **HTML5 semántico y CSS3 puro, sin JavaScript**.


## 📋 Descripción

EcoMarket ofrece una plataforma limpia y accesible donde los usuarios pueden explorar productos sostenibles, conocer la historia de la marca y contactar al equipo. Toda la interactividad (menú móvil, favoritos, carrusel, validación de formulario) se resuelve únicamente con CSS.

## 📄 Vistas

| Vista | Archivo | Contenido |
|---|---|---|
| Inicio | `index.html` | Hero, 6 productos destacados, footer |
| Productos | `views/productos.html` | Sidebar de filtros sticky, buscador, grid de 20 productos, paginación |
| Sobre nosotros | `views/sobre-nosotros.html` | Historia, principios ecológicos, carrusel de testimonios |
| Contacto | `views/contacto.html` | Formulario con validación visual, mapa y redes sociales |

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3: Grid, Flexbox, variables CSS, `scroll-snap`, pseudo-clases (`:checked`, `:target`, `:valid`, `:invalid`, `:focus-within`)
- Enfoque **Mobile First** y diseño responsivo
- Metodología de nombres BEM
- Git y GitHub (GitFlow y Conventional Commits)

**Restricciones cumplidas:** cero JavaScript y sin librerías ni frameworks externos.

## 🎨 Diseño

- Paleta: verdes y beige
- Tipografía del sistema, clara y legible
- Responsividad: 4 columnas (escritorio) -> 2 (tablet) -> 1 (móvil)

## 📁 Estructura del proyecto

```
EcoMarket/
├── css/
│   ├── main.css          # Reset, variables, tipografía
│   ├── layout.css        # Header, footer, grids
│   ├── components.css    # Cards, botones, inputs
│   └── animations.css    # Transiciones y keyframes
├── img/
│   ├── products/
│   ├── icons/
│   └── hero/
├── views/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   └── contacto.html
├── index.html
└── README.md
```

## 🚀 Cómo visualizar el proyecto

1. Clona el repositorio:
```bash
   git clone https://github.com/Yeffry-Vargas/EcoMarket_YeffryVargas.git
```
2. Entra a la carpeta:
```bash
   cd EcoMarket_YeffryVargas
```
3. Abre `index.html` en tu navegador (o usa la extensión *Live Server* de VS Code).

No requiere instalación ni dependencias.

## 📸 Capturas de pantalla

### Escritorio
<img width="911" height="458" alt="image" src="https://github.com/user-attachments/assets/4f7c8892-8b19-4573-a97c-c57c9d58d2f9" />
<img width="908" height="453" alt="image" src="https://github.com/user-attachments/assets/1eafe658-539d-464d-9706-cfeff5ba63a3" />
<img width="908" height="456" alt="image" src="https://github.com/user-attachments/assets/527f0545-572f-4578-a34c-9baf04686b67" />
<img width="911" height="453" alt="image" src="https://github.com/user-attachments/assets/1615c166-162b-4358-8c6e-61c00ccb9f24" />


## 🔀 Flujo de trabajo Git

- `main`: versión estable y desplegada
- `develop`: integración
- `feature/*`: una rama por sección o tarea (`feature/views-styles`, `feature/fill-styles`, etc.)
- Mensajes de commit siguiendo Conventional Commits (`feat:`, `fix:`, `docs:`, `style:`, `chore:`)
