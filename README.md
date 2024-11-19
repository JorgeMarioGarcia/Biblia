# La Biblia en LaTeX

Este es un proyecto que compila el contenido completo de la Biblia en formato LaTeX. Utiliza una estructura que permite visualizar los libros de la Biblia con un formato limpio y profesional, listo para ser compilado en un documento PDF.

## Descripción

El proyecto incluye:

- Estructura de documentos en LaTeX con la clase `book` para organizar los libros.
- Configuración de estilo y formato para capítulos, secciones y encabezados.
- Compatibilidad con múltiples paquetes de LaTeX para ofrecer un diseño estilizado y funcional.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

El archivo pricipal se llama Biblia.tex. Los libros estan (Por ahora los 5 primeros) en formato tex de forma individual. 


## Instalación

Para trabajar con este proyecto, asegúrate de tener LaTeX instalado en tu sistema. Puedes usar distribuciones como [TeX Live](https://www.tug.org/texlive/) o [MikTeX](https://miktex.org/).

### Requisitos de Paquetes

El archivo `Biblia.tex` utiliza los siguientes paquetes de LaTeX:

- `geometry`
- `setspace`
- `titlesec`
- `fancyhdr`
- `hyperref`
- `yfonts` (para fuentes góticas, si se requiere)

Puedes instalarlos con la gestión de paquetes de tu distribución de LaTeX o agregarlos automáticamente al compilar.

## Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Biblia.git
   cd LaBibliaEnLatex



pdflatex Biblia.tex

