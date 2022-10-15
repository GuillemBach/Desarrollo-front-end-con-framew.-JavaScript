1. La aparición de HTML5/CSS3/JS ha supuesto el nacimiento del desarrollo front-end moderno. (0.75 puntos)

• ¿Cuál es la ventaja del uso de etiquetas semánticas? Nombra y explica al menos 3 de estas ventajas.

Las etiquetas semánticas en el desarrollo front-end nos permiten dar estructura al documento HTML e indicar al mismo tiempo de que tipo se trata cada elemento o sección del documento, es decir, se usan las etiquetas para definir las diferentes partes del documento y que funcionalidad tendrá el contenido que contendrán dichas etiquetas semánticas. Por ejemplo; nos indicaran si se trata de un título y de que rango, si es un párrafo, una imagen, un encabezado, etc. 

El uso de etiquetas semánticas, a parte de dar estructura al documento, nos brinda numerosas ventajas más para el desarrollo front-end, como por ejemplo:

1.- Accesibilidad: Los lectores de pantalla para usuarios ciegos organizan la lectura del contenido de acuerdo con las etiquetas semánticas usadas.
2.- Posicionamiento en buscadores: Los motores de búsqueda analizan el código para saber qué clase de contenido muestran, y así saber cómo mostrarlo, y como posicionarlo en el buscador.
3.- Practico: El código semántico es más fácil de entender y mantener.
4.- Reusabilidad: La separación del contenido de la presentación permite que una página sea rediseñada cambiando sólo el CSS.

• Cita al menos 3 APIs HTML5 y explica brevemente su funcionalidad.

1.- Fullscreen: Ofrece la funcionalidad de poder poner en pantalla completa una web.

2.-Drag and drop: Permite establecer que elementos HTML van a poder ser arrastrados y soltados.

3.-History: Registra el histroial de navegación de un sitio web.

• Cita qué opción ofrece CSS3 para conseguir que se apliquen diferentes estilos CSS sobre el mismo elemento en su visualización en diferentes dispositivos (diferentes tamaños de pantalla).

CSS3 ofrece Media Queries para adaptar los diferentes elementos de un sitio web a diferentes tamaños de pantalla (dispositivos).

Los Media Queries son propiedades de CSS3, que nos permiten agregar condiciones a nuestra hoja de estilo, pudiendo utilizar una serie de layouts para desplegar de distintas formas un mismo contenido, el cual se irá adaptando al dispositivo que lo despliegue.

• Cita al menos 4 de las características principales de TypeScript (importante superset de JavaScript que trataremos en el siguiente capítulo).

1.- Tipado estático.
2.-Lenguaje compilado.
3.-Programación orientada a objetos.
4.-Compatibilidad: TypeScript es compatible con bibliotecas JavaScript 

2. El lenguaje CSS es muy rígido, poco práctico y ordenado a la hora de programar. Para evitar este problema se han creado los preprocesadores CSS, que ofrecen evidentes ventajas (0.5 puntos)

• Cita al menos 2 de estos preprocesadores.

1.- SASS
2.- LESS

• Cita al menos 4 ventajas que ofrecen estos preprocesadores.

1.- Reducir el código repetitivo
2.- Anidar estilos relativos a un elemento y selectores.
3.- Utilizar funciones.
4.- Mixins para estilos aplicables a varios elementos

• Explica brevemente en qué consisten los sourcemaps.

Los sourcemap se usan para poder hacer debugging (depurar) el código. El código concatenado, comprimido y en ocasiones ofuscado, da lugar a un código ilegible. Si necesitases hacer debugging a algo no serías capaz sin la ayuda de un sourcemap. Este le dice a la herramienta depuradora como volver a reconstruir el código para que sea legible. 

• Explica qué es un transpilador.

Un transpilador es un tipo de compilador que genera/traduce un código fuente en un lenguaje a otro código con un lenguaje diferente. Esta traducción solo es factible si los dos lenguajes (el original y el tranpilado) están en el mismo nivel de abstracción como por ejemplo Typescript i Javascript.

3. El flujo de trabajo profesional en front-end hace indispensable el uso de herramientas como controles de versiones y herramientas de gestión de módulos (0.75 puntos).

• Cita al menos dos sistemas de control de versiones y dos herramientas de gestión de módulos.

Control de versiones:

1.- Git.
2.- Mercurial.

Gestión de módulos:

1.- Node.js
2.- Parcel

• Cita y explica al menos 3 comandos de Git.

1.- git init: crea un nuevo repositorio local GIT.
2.- git reset: sirve para resetear el index y el directorio de trabajo al último estado de confirmación.
3.- git remote: te permite ver todos los repositorios remotos.

• Cita y explica brevemente las características más definitorias de WebPack.

-Entorno de desarrollo más productivo.
-Permite administrar todos los archivos estáticos del proyecto de una manera más eficiente.
-Es ampliamente usado por frameworks y librerías frontend actuales como React, Angular o Vue.
-Permite modificar nuestro código y prepararlo para hacer deploy en producción.
-Permite usar imports y exports de javascript moderno para la gestión de nuestro código javascript de manera simple.
-Es extensible y modular, a medida que necesitamos más funcionalidades podemos configurarlo para que se adapte a las necesidades del proyecto.
-Puede ejecutar la transpilación de Babel a ES5, lo que permite utilizar las últimas funciones de JavaScript sin preocuparse por el soporte del navegador.
-Permite usar require() para archivos CSS.
-Puede ejecutar un servidor web de desarrollo.
-Puede dividir los archivos de salida en varios archivos, para evitar tener un archivo js enorme para     cargar en el primer golpe de página.