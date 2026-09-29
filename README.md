# Demo de estudio jurídico — JC web studio

Página web estática de un abogado ficticio, creada por JC web studio.

Incluye presentación profesional con retrato generado, áreas de práctica, preguntas frecuentes y enlaces de contacto. Diseño adaptable a celulares, sin dependencias ni formulario.

## Sitio en GitHub Pages

https://jrcwebdesign.github.io/demo-estudio/

En Settings > Pages, usar Deploy from a branch, rama main y carpeta / (root).

## Ver la demo localmente

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Abrir http://127.0.0.1:4173. También se puede abrir `index.html` directamente.

## Archivos

- `index.html`: contenido y enlaces.
- `styles.css`: diseño.
- `app.js`: menú móvil.
- `assets/`: retrato ficticio.
- `estudio/README.md`: detalles de personalización y del retrato.

Para publicar en un alojamiento estático, usar la raíz del repositorio como directorio público. No requiere compilación.

La identidad es ficticia. El correo usa el dominio reservado `.example` y las redes apuntan a las páginas principales de las plataformas. Reemplazar los enlaces para un uso profesional real.

