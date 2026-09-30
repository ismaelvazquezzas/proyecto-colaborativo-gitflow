#  GameStore — Tienda Online de Videojuegos

Plataforma web de catálogo y venta de videojuegos digitales para PC y consolas. Proyecto desarrollado en equipo aplicando el flujo de trabajo colaborativo **GitFlow**, gestión de tareas mediante tablero **Kanban** y despliegue continuo en **GitHub Pages**.

-  **Sitio web en producción (GitHub Pages):** [https://github.com/users/ismaelvazquezzas/projects/2]
---

##  Integrantes del equipo

| Nombre y Apellidos | Usuario de GitHub | Responsabilidades principales |
|---|---|---|
| Ismael Vázquez | @ismaelvazquezzas | Maquetación de `index.html` y estilos base de la cabecera |
| Mateo Cotrofe | @MateoCotrofe | Estructura de `producto.html` y galería interactiva |
| Guillermo Domínguez | @pitocondria | Diseño de `carrito.html` y tabla de pedidos |
| Ismael Piñeiro | @ipineiroamonda | Creación de `README.md`, documentación |

---

## Estructura del proyecto

El sitio web está compuesto por páginas HTML enlazadas con una navegación común y gobernadas por una única hoja de estilos compartida:

```text
gamestore/
├── index.html        # Portada, sección Hero, catálogo de destacados y versión en el footer
├── producto.html     # Ficha de detalle del juego (Cyber Odyssey) con galería interactiva
├── carrito.html      # Resumen de compra, tabla de pedidos e importes totales
├── estilos.css       # Hoja de estilos compartida para todo el sitio
└── README.md         # Documentación oficial del proyecto