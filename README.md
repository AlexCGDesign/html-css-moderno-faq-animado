# Tutoriales AlexCG

Repositorio de prácticas front-end con ejemplos de HTML y CSS enfocados en animación, componentes interactivos y layouts modernos.

## Contenido

- `faq/`: página de preguntas frecuentes para un curso de CSS, construida con `<details>`, `:has()` y transiciones puramente en CSS.
- `slider-animado/`: slider con animación basada en `@property`, `clip-path` y selectores modernos.

## Vista previa

![Captura de la FAQ](faq-page.png)

## Cómo abrir el proyecto

1. Levanta un servidor local desde la raíz del repo:

```bash
python3 -m http.server 8000
```

2. Abre en el navegador:

- `http://127.0.0.1:8000/faq/faq.html`
- `http://127.0.0.1:8000/slider-animado/index.html`

## Estructura

```text
.
├── faq/
│   ├── faq.html
│   └── estilos-faq.css
├── slider-animado/
│   ├── index.html
│   ├── index-css.html
│   ├── formulario.html
│   └── estilos.css
└── README.md
```
