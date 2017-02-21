# ¿Qué es Markdown y por qué los periodistas lo usan?
(Guía rápida)

![Logo_Markdown_by_DCurtis](https://github.com/dcurtis/markdown-mark/blob/master/svg/markdown-mark-solid.svg)

Markdown es ["una herramienta de conversión de texto a HTML para escritores web"](http://daringfireball.net/projects/markdown/), creada por John Gruber con el objetivo de ayudarte a concentrar en la escritura en vez de en el formateo del documento y lo qué sucede con dicho formato cuando exportas el documento a otro formato (un revoltijo).

Esto significa que el documento de texto que escribes utilizando la sintaxis de Markdown se convierte a HTML (y puede ser exportado a otros formatos como .PDF y .Doc sin inconvenientes).

Markdown usa caracteres de puntuación comunes. Por ejemplo: si rodeas con asteriscos una `*palabra en itálica*` esta se verá como *palabra en itálica* y en HTML como `<i>palabra en itálica</i>`. ¿Dos asteriscos? `**Palabra en negritas**` se transforma en **palabra en negritas** y en `<b>palabra en negrita</b>`. Markdown tiene estilos de sintaxis para títulos, listas, citas o block quotes, enlaces y más (ver abajo). Muy relevante: ["es usado en todas las formas de escritura en Github".](https://guides.github.com/features/mastering-markdown/)

Un detalle: puedes escribir contenido y transformarlo en HTML pero Markdown no añadirá las etiquetas de estructura de un documento HTML (Ej: `<!document type>`, `<body>`, etc.). Tu tendrás que hacerlo en el HTML.

## Ayuda a reporteros a escribir velozmente y facilita la colaboración

Muchas salas de redacción y periodistas usan Markdown para escribir sus contenidos, especialmente si pasan por un proceso de edición y de producción digital colectiva que incluye a otros reporteros, diseñadores y programadores.

En [Poynter escribieron](https://www.poynter.org/2015/keeping-up-with-the-times-free-tech-for-nonprofit-newsrooms/384231/) no hace mucho de un caso típico de los nuevos tipos de flujo de trabajo editorial que involucra el uso de Markdown: "Los periodistas de investigación en el Marshall Project escriben directamente en Google Docs y comparten sus textos con un editor cuando han terminado. Entonces, un script de código que Vong [Ivar Vong, director de tecnología] escribió, convierte el texto a lenguaje Markdown que el diseñador gráfico usará cuando diseñe la historia para el sitio web de el Marshall" project.

Es una de las herramientas que decenas de operaciones periodisticas digitales ya han adoptado para "reducir las barreras entre programadores y no programadores" que trabajan juntos, [descubrió](http://towcenter.org/reducing-barriers-between-programmers-and-non-programmers-in-the-newsroom/) el Tow Center for Digital Journalism.

Reporteros en NPR y ProPublica usan Markdown como parte de su flujo de trabajo para producir y manejar los textos de sus artículos y reportajes. [Vox Media adquirió Editorially](http://stet.editorially.com/articles/editorially-joins-vox-media/) (una startup que redefinió la experiencia de escritura, control de versiones y colaboración editorial, mediante el uso de Markdown entre otros de sus grands caracterñisticas), para potenciar su, de por sí, innovadora tecnología de publicación. Plataformas y startups como Stack Overflow, Carto, Codeacademy, para nombrar algunas, han [adoptado Markdown como su herramienta de formateo de contenido](https://carto.com/blog/why-we-use-markdow).

¿Por qué tanta vaina con Markdown? Bueno, pues porque es tan fácil de aprender su sintaxis que es a prueba de periodistas. Permite escribir de modo muy rápido sin preocuparse del interlineado o los espacios entre párrafos o los estilos tipográficos y tamaños de letra o lo que sea que en un documento Word normalmente haces haciendo click en las opciones del menú del programa, para que tu texto se vea lindo. Acá no. Dos cucharadas y a la papa, como dicen los antiguos en Chile.

## Aprende en cinco minutos

Como los documentos de Markdown son documentos de texto simple, puedes usar cualquier editor de texto para crear, editar y guardar un documento. Es decir, puedes escribir estilo Markdown en [Sublime Text](https://www.sublimetext.com/), [Atom](www.atom.io), [Vim](http://www.vim.org/), [Visual Studio](https://code.visualstudio.com/docs), [Brackets](http://brackets.io/), [Notepad++](https://notepad-plus-plus.org/) o cualquier otro editor de texto que prefieras. Sólo **recuerda una regla primordial**: debes guardar el documento con la extensión de archivo **punto md** o **punto markdown**. Así: `nombredearchivo.md` o bien `nombredearchivo.markdown`.

A continuación, la sintaxis básica para formatear textos en Markdown (via la guía de Github ["Mastering Markdown"]((https://guides.github.com/features/mastering-markdown/)).


```markdown
Bloque de código con sintaxis resaltada

# Título 1 o h1
## Título 2 o h2
### Título 3 o h3
#### Título 4 o h4
##### Título 5 o h5
###### Título 6 o h6

- Lista
- Con viñetas

1. Lista
2. Numerada

**Negritas**
*Itálica*
***Itálica & negritas juntas***
`Código`

Línea horizontal
*******

> Cita o bloque de cita

[Enlace](url)

Para añadir una imagen: ![Imagen](fuente de la imagen, una url)

```

Para más ejemplos y opciones avanzadas de sintaxis revisa:
- [Una guía de Markdown para escribir para la web de forma más sencilla (en inglés)](https://scotch.io/bar-talk/a-guide-to-markdown-for-simpler-web-writing
).
- [Documentación oficial del creador de Markdown John Gruber (inglés)](https://daringfireball.net/projects/markdown/)
- [Glosario y trucos de Markwdown (inglés)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Guía visual de Markdown y tutoriales (inglés)](http://commonmark.org/help/)
- [Lista de variaciones de sintaxis de Markdown creadas por distintas organizaciones](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors)

## Elige y prueba un editor de Markdown

Mientras un editor de texto ofrece un modo sencillo y rápido de crear un documento `.md`, el beneficio real de utilizar Markdown es evidente cuando tienes que convertir el archivo a otro formato para publicación, como HTML (web), .PDF (libro) o un documento Word (para edición tradicional).

Si eres periodista, como ya leíste, quizás tengas que escribir un artículo en Markdown, convertirlo a HTML y añadirle cascadas de estilos (CSS) y scripts de Javascript para la puesta en página web. O bien, tendrás que enviar el archivo `.md` a un editor, a un colega del área de gráficos interactivos o a un desarrollador web. Lo más probable es que todo lo anterior lo estarás haciendo dentro de un repositorio de Github al cual tu equipo y tú tienen acceso.

Ya que ese es tu caso, te irá mucho mejor si escoges y utilizas uno de los muchos editores de Markdown existentes. Puedes buscar ["mejores editores de Markdown"](https://www.google.com/search?q=mejor+editor+de+markdown&ie=utf-8&oe=utf-8&client=firefox-b-ab) o [“best Markdown editors”](https://www.google.com/search?num=50&client=firefox-b-ab&q=%22best+markdown+editors%22&oq=%22best+markdown+editors%22&gs_l=serp.3..0l2j0i22i30k1l8.6222.10539.0.10858.7.7.0.0.0.0.79.391.6.6.0.foo%2Cewh%3D0%2Cnso-enksa%3D0%2Cnso-enfk%3D1%2Cnso-usnt%3D1%2Cnso-qnt-npqp%3D0-2%2Cnso-qnt-npdq%3D0-5%2Cnso-qnt-npt%3D0-13%2Cnso-qnt-ndc%3D300%2Ccspa-dspm-nm-mnp%3D0-065%2Ccspa-dspm-nm-mxp%3D0-1625%2Cnso-unt-npqp%3D0-2%2Cnso-unt-npdq%3D0-35%2Cnso-unt-npt%3D0-1%2Cnso-unt-ndc%3D300%2Ccspa-uipm-nm-mnp%3D0-0125%2Ccspa-uipm-nm-mxp%3D0-0875%2Ccfro%3D1%2Cewh%3D0%2Cnso-enksa%3D0%2Cnso-enfk%3D0...0...1.1.64.serp..1.6.390...0i67k1j0i7i30k1j0i13k1j0i30k1.4y9J40xDMGw) para descubrir el que satisfaga tus necesidades.

Preparé una lista corta de editores favoritos para escritorio y para trabajo en línea. Todos permiten guardar y sincronizar tu trabajo con servicios en la nube, así como prever los cambios que realizas en tiempo real para ahorrar tiempo y energía.

1. [Stackedit](https://stackedit.io): Editor en línea gratuito, permite sincronizar y guardar documentos en Google Drive y Dropbox, y compartirlos. Una buena introducción a Markdown.
2. [IA Writer](https://ia.net/writer/): Aplicacion para escritorio para computadores Mac (cuesta $3,99). Simple, diseño limpio, incluye un set de caractersticas como "modo de escritura concentrado", plantillas, corrector ortográfico y sincronización con Dropbox e iCloud. Soy parcial: es el editor que uso a diario.
3. [Atom](www.atom.io): De codigo abierto, gratuito. Es un editor de texto para código pero incluye una opción para ver el documento con estilos aplicados en una ventana paralela a la que usas para escribir. Luego de instalar Atom, debes ir a la opción del menú: “Packages” y elegir “Markdown preview”: “Toggle preview”. Cómo es desarrollado por Github incluye muchas características construidas para facilitar la conexión y trabajo con tu repositorio en Github. Ha sido criticado por problemas de velocidad pero ultimamente pareciera andar muchísmo mejor.
4. [MacDown](http://macdown.uranusjr.com/) (Mac): De código abierto y gratuito. Aplicación de escritorio. Tiene muchos usuarios.
5. [Prose.io](http://prose.io/): Editor en línea, de código abierto y gratuito. Desarrollado para “administrar contenido en Github”. Prose.io fue desarrollado por Development Seed, compañía que decidió hacerlo para sus propios proyectos "libres de CMS". Atributos: “Úsalo para crear, editar, borrar archivos y guardar cambios directamente en Github”. Utilizado por periodistas familiarizados con Github y Jekyll, un generador de sitios web estáticos.
6. [Dillinger.io](http://dillinger.io/): Open source, basado en web, libre de costo. Permite guardar y sincronizar documentos con Drive, Github, Dropbox y Medium.
7. [Classeur.io](http://classeur.io/): Freemium online y desktop. De los creadores de Stackedit.

Si sigues buscando verás que hay [muchas](https://www.slant.co/topics/899/~best-markdown-editor-for-os-x), muchsimas [más](https://speckyboy.com/markdown-tools-editors/) opciones. Prueba los que te parezcan hasta encontrar tu editor ideal.

¿Mencioné que puedes añadir [emojis](http://www.webpagefx.com/tools/emoji-cheat-sheet/) en algunas versiones extendidas de Markdown, como la que usa Github?

```
  :metal:
  :clap:
  :rocket:
  :tada:
 ```
 :metal:
 :clap:
 :rocket:
 :tada:

Para finalizar, realiza este [ejercicio de escritura con Markdown, fork y pull request](https://github.com/craft2es/markdownparaperiodistas/ejercicio_markdown_pullrequest.md).

*Puedes leer este artículo en mi sitio web: [miguelpaz.info](http://miguelpaz.github.io/markdown-para-periodistas.html)*

---
*La guía [Markdown para periodistas](https://github.com/craft2es/markdownparaperiodistas) es parte de los materiales del curso Craft 2 del Programa Bilingüe de la Maestría de Periodismo de CUNY*

 [//]: # (Así es como escribes comentarios en tu Markdown para que no se vean en tu página web HTML.)
