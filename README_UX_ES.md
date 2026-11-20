# Super Robot Wars UX — Traducción de fans al inglés y al español

Traducción de fans gratuita y no oficial de **Super Robot Wars UX** para **Nintendo 3DS**, disponible en inglés y español latinoamericano. Presentada por **Gyasuke & Wakabayashy Workshop**.

La traducción se distribuye mediante un **parcheador HTML que funciona sin conexión**. Usa tu propia copia limpia y descifrada del juego japonés.

**Versión pública del juego base** — 0.8.0 
**Versión experimental con parcheo opcional del DLC** — B057G26  
**Última actualización del README** — 13 de noviembre de 2026  
**Idiomas** — Inglés y español latinoamericano, con **interfaz del juego en inglés en ambas versiones**.

## Cambios en B057G26

- Fei-Yen HD ahora usa **Fei** como nombre corto. Se tradujeron los dos rótulos de nombre de Hallelujah en combate.
- Los rótulos de habilidades y sus descripciones usan **Cont. Action** y **Concentration**. Esta versión incorpora también el cambio de **Hot Blood** a **Valor** de G25.
- Se tradujeron más nombres de rutas en el aviso de intermisión, incluido **Byston Well**, además del encabezado de la bonificación de Shoko y los avisos de compra y canje del DLC.
- Se tradujeron rótulos y ayudas de los editores de nombres de pilotos y unidades. Se ajustó el editor para separar **Agnes Berge** en sus dos campos y conservar **Arnie** como apodo.

## Contenido

- Historia y diálogos de combate traducidos al inglés y al español latinoamericano. La voz de los personajes, la terminología, los nombres y la distribución del texto siguen en revisión.
- Los diálogos traducidos pueden superar la longitud en bytes del original japonés. Se pueden ampliar y redistribuir siempre que respeten el espacio del cuadro de texto y los límites de almacenamiento del juego.
- Menús, comandos, mensajes del sistema y demás textos de interfaz en inglés para ambas versiones.
- Gráficos tácticos y de combate, tarjetas narrativas y otros elementos visuales traducidos y revisados.
- **244 rótulos de ubicación revisados**. Se recuperó la información del lugar y la sala, separados por `/`. Se abrevian los descriptores comunes cuando conviene y se conservan los nombres distintivos.
- Tarjetas narrativas corregidas, incluidas las introducciones de las partes 2 y 3. El texto se distribuyó según los fragmentos animados del juego.
- Tarjeta del capítulo final corregida en ambos idiomas. Se restauró el texto negro sobre fondo blanco.
- Logotipo del título, avisos de derechos de autor de las series al arrancar, gráficos de habilidades de combate, bonificaciones, rótulos de ruta y comandos revisados, incluido E-Wave.
- Correcciones acumuladas de nombres y terminología, con comprobaciones de términos compartidos con Super Robot Wars BX y ajustes a los nombres de habilidades de piloto, como Resolve y Predict.
- Mejoras del parcheador en Android para la lectura de archivos, el cálculo de IVFC y el procesamiento de los datos de traducción.
- Correcciones acumuladas a partir de pruebas en emulador y reportes en consolas Nintendo 3DS.
- **Parcheo sin conexión**. El navegador procesa el archivo del juego localmente.

## Instalación

1. Haz una **copia de seguridad** del juego japonés original y de tus partidas guardadas.
2. Descarga y extrae el ZIP del parcheador HTML.
3. Abre el archivo `.html` en un navegador compatible y actualizado en tu computadora o dispositivo Android. Los archivos grandes requieren suficiente almacenamiento libre y memoria.
4. En el campo del juego base, selecciona tu copia **limpia, sin modificar y descifrada de Super Robot Wars UX en japonés** (`.cia`, `.cxi`, `.cci` o `.3ds`). La CIA japonesa v0 descifrada es la que más se ha probado. Los demás formatos admitidos pueden requerir más pruebas. Para la CIA del DLC, usa el campo **DLC de UX** en B057G26.
5. Elige **English** o **Español latinoamericano**. Los menús y la interfaz del juego se muestran en inglés con cualquiera de las dos opciones.
6. Si quieres comprobar el archivo de origen, pulsa **Comprobar archivos** (**Check files**). Luego pulsa **Reconstruir juego traducido** (**Rebuild translated game**) y guarda el archivo generado.
7. Ejecuta el juego reconstruido en un emulador compatible o en tu Nintendo 3DS. Guarda una copia de seguridad de tus partidas antes de probarlo.

**Importante.** Parte siempre del **juego japonés original descifrado**. Cada versión es acumulativa y se aplica directamente sobre el original.

### Parcheador y archivo de salida

El parcheador comprueba que los datos del juego sean compatibles y legibles. Requiere una copia descifrada.

Los rótulos de ubicación ampliados requieren **reconstruir el juego completo**. Usa **Reconstruir juego traducido** (**Rebuild translated game**) para generar el archivo de esta versión. La opción de generar un ZIP de Luma/LayeredFS está deshabilitada en esta versión.

### Parcheo opcional del DLC (experimental en B057G26)

Selecciona tu propia CIA limpia y descifrada del DLC japonés de UX (Title ID `0004008C00078A00`), pulsa **Parchear CIA del DLC** y guarda el archivo generado. Instala esa CIA por separado del juego traducido. Usa una copia completa, descifrada y sin traducir del DLC.

Esta opción conserva el trabajo de V7, con 48 entradas del catálogo y 138 textos de objetivos en inglés distribuidos en 47 misiones. Los títulos de Puzzle mantienen su prefijo japonés para que el juego reconozca su categoría. El mapa de campaña 9 sigue en japonés. El catálogo y los objetivos del DLC se muestran en inglés con cualquiera de los dos idiomas del juego base.

La reconstrucción del DLC incorporada en B057G24 se probó con una CIA real del DLC descifrada en PC cuyas misiones estaban ordenadas por nombre de archivo. El parcheador reconoce ese orden y restaura el orden de las misiones al reconstruir la CIA. **Queda pendiente probar la instalación y el DLC durante el juego.** Configura tanto el juego como el DLC con región Japón e idioma japonés, tal como requirieron las pruebas anteriores en consola. Si al abrir **Get DLC** aparece un error de conexión, cierra y vuelve a abrir UX antes de consultar las estadísticas de las unidades. El cierre inesperado que ocurría después de esa secuencia sigue pendiente de resolver.

## Pruebas y estado del proyecto

**B057G22 es la versión del juego base de la edición pública 0.8.0. B057G26 es la versión de prueba acumulativa más reciente.**

### Pruebas de juego

**El tester Marl completó una partida de principio a fin eligiendo siempre la segunda opción en cada bifurcación de ruta.** Esa partida cubrió la secuencia de rutas elegida. Quedan rutas alternativas y escenas opcionales por verificar.

La traducción y el sistema ampliado de rótulos de ubicación también funcionaron en una Nintendo 3DS real. Los rótulos de lugar y sala con `/` se mostraron correctamente en las escenas comprobadas.

### Validación de la versión actual

La narración corregida de la parte 3 se comprobó en emulador en inglés y español. La corrección de la tarjeta del capítulo final que se añadió en G22 pasó las pruebas de reconstrucción de textura y la inspección visual en ambos idiomas. En B057G26 se verificaron la sintaxis de JavaScript, la reconstrucción de los recursos modificados en ambos idiomas, la aplicación del parche del ejecutable y la ampliación de las ubicaciones. Quedan pendientes una reconstrucción completa y la comprobación en juego de las nuevas correcciones, incluido el editor de nombres.

Continúan las pruebas de rutas alternativas, escenas opcionales, combinaciones de combate, emuladores y configuraciones de consola. La partida completa documenta el recorrido de Marl. La cobertura del resto del contenido y la validación de correcciones posteriores se comprueban por separado.

## Limitaciones conocidas y reportes de errores

- Algunos **indicadores de acciones de combate** pequeños siguen en japonés, sobre todo ciertos símbolos de la pantalla de pronóstico de combate. Son elementos gráficos que se investigan aparte de los textos de interfaz ya traducidos.
- Otras tarjetas narrativas, rótulos largos y elementos de interfaz todavía pueden requerir ajustes de alineación o recorte.
- Algunas escenas opcionales, variantes de ruta y secciones avanzadas siguen pendientes de una revisión exhaustiva. Pueden aparecer textos sin traducir, inconsistencias terminológicas, problemas de diseño o errores propios de ciertas configuraciones.
- La traducción sigue en revisión editorial y visual. Cada texto e imagen requiere su propia revisión aunque el parche se genere correctamente.

Si encuentras un cierre inesperado, un gráfico sin traducir, una narración recortada, un término incorrecto u otro problema de interfaz, envía un reporte al equipo del proyecto. Si puedes, incluye lo siguiente.

- La **versión del parche** y el idioma elegido (**EN/ES**).
- La configuración de tu Nintendo 3DS o el nombre y la versión del emulador.
- El **capítulo**, la ruta y los pasos exactos para reproducir el problema.
- La última línea de diálogo visible, el gráfico afectado o el menú o pantalla donde ocurre.
- Una captura o un video corto. Si el juego se cierra, adjunta el registro o volcado del error si lo tienes.

Haz una copia de seguridad de tu partida antes de intentar reproducir un problema. **Excluye de los reportes las copias del juego protegidas por derechos de autor.**

## Créditos

- **Proyecto y presentación del parche** — Gyasuke & Wakabayashy Workshop

### Testers

- **Theoldnile**
- **Marl** — completó una partida eligiendo siempre la segunda opción en cada bifurcación.

Muchas gracias a quienes probaron el parche por su tiempo, dedicación, reportes detallados y comentarios. Su ayuda para detectar problemas de traducción, errores gráficos, fallas de diseño y errores específicos de consola es fundamental para mejorar el proyecto.

Gracias también a todas las personas que han reportado errores y apoyado la traducción.

## Aviso legal y distribución

Esta es una **traducción de fans no oficial y sin fines comerciales**. El proyecto es independiente de Bandai Namco y de los titulares de derechos originales y carece de su patrocinio o aval. El contenido original del juego, la música, las marcas y los personajes pertenecen a sus respectivos propietarios.

**El parche es gratuito. Está prohibido venderlo o restringir su acceso mediante pago. Si pagaste por él, te estafaron. El proyecto no autoriza a nadie a cobrar por el parche.**

La distribución se limita al parche y excluye la ROM, el DLC y la BIOS. Cada usuario es responsable de obtener y utilizar sus propios archivos del juego conforme a la legislación aplicable.

---

¡Gracias por jugar **Super Robot Wars UX** en inglés o español!

