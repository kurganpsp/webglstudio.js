<p align="center">
    <img src="https://raw.githubusercontent.com/jagenjo/webglstudio.js/master/press/images/logo.png" alt="WebGLStudio">
</p>

# WebGLStudio.js

WebGLStudio.js es un conjunto herramientas de gráficos 3D, de código abierto, basado en navegador. Puede editar escenas y materiales, diseñar efectos y sombreadores, codificar comportamientos y compartir su trabajo, todo dentro de un navegador utilizando tecnologías web estándar.


Algunas características importantes de WebGLStudio.js:

 * Un motor de gráficos 3D completo ([LiteScene.js] (https://github.com/jagenjo/litescene.js)) que admite múltiples luces, mapas de sombras, reflejos en tiempo real, materiales personalizados, postFX, skinning, animación y mucho más .
 
 * An easily extended, component-based system for controlling the rendering pipeline and interaction event hooks 
 
 * Fácil de usar, Lo que ve es lo que tienes (WYSIWYG) un editor que proporciona una interfaz única para todas las funciones de codificación, composición gráfica y línea de tiempo.

 * Un editor de gráficos para controlar comportamientos, sombreadores y efectos de procesamiento posterior, utilizando [LiteGraph.js] (https://github.com/jagenjo/litegraph.js).

 * Admite [LiteFileSystem.js] (https://github.com/jagenjo/litefilesystem.js), un sistema de archivos virtual que permite el almacenamiento de recursos en la web mediante arrastrar y 
 soltar, con cuotas configurables, usuarios y carpetas compartidas .

 * Exporta y comparte tu trabajo enviando un solo enlace.

Para mas imformacion, visitar http://webglstudio.org

![Interface](press/images/interface.jpg "Interface")

Características que faltan:
* Edición de malla, no puede seleccionar caras y moverlas
* Soporte para FBX, tiene algún tipo de soporte pero no completamente funcional
* Física

Instalando
----------

Para instalar WebGLStudio.js, copie los archivos del editor en su servidor, luego instale [LiteFileSystem.js] (https://github.com/jagenjo/litefilesystem.js) en la carpeta `fileserver/` dentro del directorio `editor/`.
LiteFileSystem es una biblioteca que maneja el almacenamiento remoto de archivos. Para obtener más información, consulte el archivo `/INSTALL.md` y la documentación [LiteFileSystem.js] (https://github.com/jagenjo/litefilesystem.js).

Retroalimentación
--------

Envíe todos los comentarios a javi.agenjo@gmail.com
