# Blog Preview Card

Este componente es una tarjeta de vista previa para blogs, diseñada utilizando HTML puro y Tailwind CSS para mostrar información clave de un artículo de manera atractiva y compacta.

## Características

- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla gracias a Tailwind CSS.
- **Personalizable**: Fácil de ajustar estilos y contenido mediante clases de Tailwind.
- **Accesible**: Cumple con las mejores prácticas de accesibilidad.

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu-usuario/blog-preview-card.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd blog-preview-card
    ```

## Uso

Incluye el código HTML en tu proyecto y asegúrate de tener Tailwind CSS configurado:

```html
<div class="max-w-sm rounded overflow-hidden shadow-lg">
  <img class="w-full" src="ruta/a/la/imagen.jpg" alt="Imagen del blog">
  <div class="px-6 py-4">
    <div class="font-bold text-xl mb-2">Título del Blog</div>
    <p class="text-gray-700 text-base">
      Descripción breve del artículo.
    </p>
  </div>
  <div class="px-6 pt-4 pb-2">
    <a href="https://enlace-al-blog.com" class="text-blue-500 hover:underline">Leer más</a>
  </div>
</div>
```

## Personalización

Puedes modificar las clases de Tailwind CSS para ajustar el diseño según tus necesidades. Consulta la [documentación oficial de Tailwind CSS](https://tailwindcss.com/docs) para más detalles.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).
