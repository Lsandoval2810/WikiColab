# Wiki · Metodología de la Investigación

Una wiki estática, responsiva y de estilo académico sobre los conceptos esenciales de la metodología de la investigación científica.

## Contenido

- Técnicas de recolección de información
- Validez
- Muestra
- Tipos de muestreo
- Confiabilidad
- Piloteo
- Relación entre conceptos
- Referencias en formato APA

## Tecnologías

| Capa | Tecnología |
|------|-----------|
| Markup | HTML5 semántico |
| Estilos | CSS3 puro (sin frameworks) |
| Despliegue | Netlify (sitio estático) |

## Ejecución local

Basta con abrir `public/index.html` directamente en cualquier navegador. No requiere servidor ni dependencias.

```bash
# Opción 1 — doble clic en el archivo
open public/index.html

# Opción 2 — servidor HTTP mínimo de Python
python3 -m http.server 8080 --directory public
```

## Despliegue en Netlify

El sitio está configurado para despliegue continuo. El directorio de publicación es `public/` y no requiere paso de compilación.
