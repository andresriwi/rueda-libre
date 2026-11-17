# Rueda Libre

Sitio web de alquiler de bicicletas y recorridos guiados en Medellín.

**Sitio publicado:** [andresriwi.github.io/rueda-libre](https://andresriwi.github.io/rueda-libre/)

## Contenido

- **Inicio** (`index.html`): presentación, servicios, flota, beneficios y rutas.
- **Tarifas y rutas** (`paginas/tarifas.html`): tarifas de alquiler y recorridos guiados.
- **Reservas** (`paginas/reservas.html`): formulario de solicitud e información de contacto.

## Tecnologías

- HTML5
- CSS3
- Bootstrap 5.3.3 y Bootstrap Icons
- Google Fonts

Bootstrap, Bootstrap Icons y las fuentes se cargan desde sus respectivos servicios externos, por lo que se requiere conexión a internet para verlos correctamente.

## Estructura del proyecto

```text
rueda-libre/
├── css/
│   └── styles.css
├── img/
├── paginas/
│   ├── reservas.html
│   └── tarifas.html
├── pruebas/
│   └── catalogo-bootstrap.html
├── index.html
├── bitacora.txt
└── README.md
```

## Ver el sitio localmente

Abre `index.html` en un navegador o usa la extensión **Live Server** de Visual Studio Code para servir el proyecto localmente. La navegación entre páginas usa rutas relativas, así que conserva la estructura de carpetas.

## Nota sobre las reservas

El formulario de reservas es una interfaz de demostración. No envía ni almacena solicitudes en un servicio de reservas.
