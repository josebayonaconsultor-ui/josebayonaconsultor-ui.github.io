# José Bayona

Sitio web de **José Bayona Investigación y Consultoría** (Ocaña, Norte de Santander, Colombia).

> Investigo para comprender. Transfiero para transformar.

## Contenido del repositorio

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La página completa: textos, diseño y funcionamiento. |
| `noticias.json` | Las notas de la sección «Noticias y lecturas críticas». |
| `*.webp`, `*.png` | Fotografías y logotipo, optimizados para carga rápida. |

## Publicar el sitio (GitHub Pages)

1. En el repositorio, abra **Settings → Pages**.
2. En **Build and deployment**, elija **Deploy from a branch**.
3. Seleccione la rama `main` y la carpeta `/ (root)`. Guarde.
4. En uno o dos minutos el sitio queda público en `https://<usuario>.github.io/` (si el repositorio se llama `<usuario>.github.io`).

## Editar en línea desde GitHub

Todo se edita desde el navegador, sin instalar nada.

### Agregar la nota de la semana

1. Abra `noticias.json` y pulse el ícono del lápiz (**Edit this file**).
2. Copie un bloque existente, péguelo al inicio de la lista y cambie sus valores:

```json
{
  "fecha": "2026-11-09",
  "categoria": "Pensamiento crítico",
  "titulo": "Título de la nota",
  "resumen": "Resumen de dos a cuatro frases.",
  "pregunta": "¿Pregunta crítica que deja la nota?",
  "enlace": "https://enlace-a-la-fuente",
  "fuente": "Nombre de la fuente"
}
```

3. Separe cada bloque con una coma y pulse **Commit changes**.

Categorías disponibles: `Investigación`, `Actualidad`, `Pensamiento crítico`, `Transferencia`. Las notas se agrupan solas por semana (de lunes a domingo) y se numeran como ediciones. `enlace` y `fuente` pueden quedar vacíos (`""`).

### Cambiar un texto de la página

1. Abra `index.html` y pulse el lápiz.
2. Use **Ctrl + F** (o **Cmd + F**) para buscar la frase que quiere cambiar.
3. Edite solo el texto entre las etiquetas, sin borrar los signos `<` `>`.
4. Pulse **Commit changes**. El sitio se actualiza en uno o dos minutos.

### Cambiar una fotografía

Suba la nueva imagen con **el mismo nombre** del archivo que reemplaza (por ejemplo, `jose-bayona-inicio.webp`).

## Contacto

- WhatsApp: +57 316 498 7081
- Correo: josebayonaconsultor@gmail.com
- LinkedIn: https://www.linkedin.com/in/josebayonaconsultor/
- Instagram: https://www.instagram.com/josebayonaconsultor1/
- Google Scholar: https://scholar.google.com/citations?hl=es&user=gJseD9IAAAAJ
- CvLAC: https://scienti.minciencias.gov.co/cvlac/visualizador/generarCurriculoCv.do?cod_rh=0000033854
