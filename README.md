# Sara Sánchez Cañola · Web personal

Mi portfolio personal: quién soy, qué sé hacer y los proyectos en los que trabajo.

**Web:** https://saraley.github.io

## Sobre mí

Técnica de redes y estudiante del Técnico Superior en Administración de Sistemas Informáticos en Red (ASIR), con el curso de especialización en Ciberseguridad. Practico pentesting en Hack The Box.

- LinkedIn: https://www.linkedin.com/in/sara-s%C3%A1nchez-ca%C3%B1ola/
- Email: janeth882008@gmail.com

## Qué incluye la web

- Presentación y resumen del perfil
- Habilidades: sistemas, redes, servicios de red, virtualización, ciberseguridad, código y datos
- Portfolio de proyectos
- Pentesting: progreso en Hack The Box Academy
- Trayectoria académica y laboral, e idiomas
- Contacto

## Tecnologías

HTML, CSS y JavaScript sin dependencias. Todo está en un único archivo, `index.html`, y las imágenes van incrustadas. Las tipografías (Bricolage Grotesque y Figtree) se cargan desde Google Fonts. La web se adapta al móvil y al modo claro u oscuro del dispositivo.

## Cómo añadir un proyecto al portfolio

Abre `index.html` y busca la lista `PROJECTS` al final del archivo. Copia una entrada, pégala dentro de la lista y cambia los textos:

```js
{
  titulo: "Nombre del proyecto",
  texto: "Qué hace y qué has aprendido.",
  etiquetas: ["Linux", "Redes"],
  enlace: "https://github.com/saraley/mi-proyecto"
}
```

- `enlace` es opcional.
- Si una entrada lleva `ejemplo: true`, se muestra con la etiqueta "Ejemplo". Quítala cuando sea un proyecto real.

## Cómo actualizar el progreso de Hack The Box

En la sección `Pentesting` de `index.html`, cambia los valores de las barras (`width:85%` y `width:25%`) y los textos `Nivel`, `203 / 240 XP` y `Progreso`.

## Publicación

La web se publica con GitHub Pages:

1. El repositorio se llama `saraley.github.io` y es público.
2. El archivo principal se llama `index.html` y está en la raíz.
3. En **Settings > Pages**, la fuente es la rama `main`, carpeta `/ (root)`.

Cada cambio que se sube a `main` se publica en unos minutos.

## Estructura

```
.
├── index.html   # toda la web
└── README.md
```
