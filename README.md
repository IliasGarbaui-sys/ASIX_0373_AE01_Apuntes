Git hub

1. Git y el concepto de control de versiones
El control de versiones es una técnica fundamental dentro de la informática y del desarrollo de software que permite registrar, organizar y gestionar todos los cambios realizados sobre los archivos de un proyecto a lo largo del tiempo. Su objetivo principal es mantener un historial completo y ordenado de modificaciones, de forma que sea posible consultar versiones anteriores, recuperar información perdida y comprender cómo ha evolucionado un proyecto desde su creación hasta su estado actual.
Cuando se trabaja en un proyecto, los archivos no permanecen estáticos. Se modifican constantemente: se añaden líneas de texto, se eliminan partes que ya no sirven, se corrigen errores y se incorporan nuevas funcionalidades. El control de versiones actúa como una especie de memoria del proyecto, guardando cada cambio importante para que nunca se pierda y siempre se pueda volver atrás si es necesario.
En proyectos muy pequeños, realizados por una sola persona y durante un periodo corto de tiempo, es posible trabajar sin un sistema de control de versiones. Sin embargo, incluso en estos casos, el riesgo de cometer errores sigue existiendo. Basta con guardar mal un archivo, sobrescribir una versión correcta o eliminar algo por accidente para perder horas de trabajo. A medida que el proyecto crece, estos riesgos aumentan considerablemente.
Cuando un proyecto se vuelve más grande o participan varias personas, el control de versiones deja de ser opcional y se convierte en una necesidad absoluta. Sin un sistema adecuado, es muy fácil que surjan problemas como archivos duplicados, versiones contradictorias o cambios que se pisan entre sí. También se vuelve complicado saber quién ha hecho una modificación concreta o qué cambio ha provocado un error en el funcionamiento del proyecto.
El control de versiones permite solucionar todos estos problemas proporcionando una estructura clara y organizada. Cada modificación queda registrada de forma cronológica, permitiendo revisar el historial completo del proyecto. Esto hace posible analizar cuándo se introdujo un error, comparar versiones distintas de un mismo archivo o recuperar una versión anterior que funcionaba correctamente.
Dentro de los sistemas de control de versiones existentes, Git es uno de los más utilizados y extendidos en la actualidad. Git es un sistema de control de versiones distribuido, lo que supone una diferencia muy importante con respecto a otros sistemas más antiguos. En un sistema distribuido, cada copia del proyecto contiene todo el historial de cambios, no solo la versión más reciente.
Esto significa que cada desarrollador tiene en su ordenador una copia completa del proyecto, con todas las versiones guardadas desde el inicio. No se depende de un único servidor central para acceder al historial, lo que aporta una mayor seguridad frente a pérdidas de datos. Incluso si el servidor remoto deja de funcionar, las copias locales siguen conservando toda la información del proyecto.
El carácter distribuido de Git también proporciona una gran flexibilidad. Cada usuario puede trabajar de forma independiente en su ordenador, realizando cambios y guardándolos sin necesidad de estar conectado a internet. Cuando lo desee, puede sincronizar su trabajo con el resto del equipo, enviando o recibiendo los cambios realizados por otros colaboradores.
Git no se limita a guardar archivos como si fuera una simple copia de seguridad. Además de almacenar los contenidos, registra información detallada sobre cada cambio. Para cada modificación importante, Git guarda quién realizó el cambio, en qué momento se hizo y con qué propósito. Esta información queda asociada a cada versión del proyecto y permite comprender el contexto de cada decisión tomada durante el desarrollo.
Gracias a este sistema, el historial de un proyecto se convierte en una herramienta de documentación muy valiosa. No solo se puede ver qué se cambió, sino también por qué se cambió. Esto es especialmente útil cuando pasa mucho tiempo entre versiones o cuando nuevas personas se incorporan al proyecto y necesitan entender su funcionamiento.
Otra ventaja clave del control de versiones con Git es la posibilidad de experimentar sin miedo. Al saber que cualquier cambio queda registrado y que siempre se puede volver atrás, los desarrolladores pueden probar nuevas ideas, modificar partes del proyecto o refactorizar código con mayor tranquilidad. Si algo no funciona, basta con volver a una versión anterior sin perder el trabajo previo.
En el ámbito profesional, el uso de Git y del control de versiones es un estándar. Empresas, equipos de desarrollo y proyectos colaborativos dependen de estas herramientas para organizar su trabajo, evitar errores y mantener una evolución controlada del software. Git se ha convertido así en una pieza clave no solo para programadores, sino también para diseñadores web, administradores de sistemas y cualquier persona que trabaje con archivos que cambian con el tiempo.
En resumen, el control de versiones permite transformar un conjunto de archivos en un proyecto vivo, con memoria, orden y seguridad. Git aporta a este concepto una forma moderna, distribuida y eficiente de gestionar cambios, convirtiéndose en una herramienta esencial para el desarrollo web y la informática actual.




2. Qué es Git y para qué se utiliza
Git es un software que se instala directamente en el ordenador del usuario y que permite gestionar versiones de archivos de forma local. Se trata de una herramienta diseñada específicamente para controlar la evolución de un proyecto a lo largo del tiempo, registrando cada cambio relevante que se realiza sobre los archivos. Su función principal es guardar un historial completo de modificaciones y permitir volver atrás en cualquier momento si algo no funciona como se esperaba.
A diferencia de otras herramientas más simples, Git no se limita a hacer copias de seguridad. Git analiza los cambios que se realizan entre una versión y otra, almacenando únicamente la información necesaria para reconstruir el estado del proyecto en cualquier punto de su historia. Esto hace que el sistema sea eficiente, rápido y muy fiable, incluso en proyectos grandes con muchos archivos.
Git trabaja directamente sobre carpetas del sistema operativo, llamadas repositorios. Un repositorio es, básicamente, la carpeta que contiene el proyecto y sobre la que Git va a realizar el seguimiento de cambios. Dentro de esta carpeta se encuentran los archivos normales del proyecto, como documentos, páginas web o recursos gráficos, y también una carpeta interna especial que Git utiliza para almacenar toda la información relacionada con el control de versiones.
Esta carpeta interna es fundamental para el funcionamiento de Git. Aunque normalmente permanece oculta al usuario, en ella se guarda el historial completo del proyecto, incluyendo todas las versiones, los cambios realizados, la información de cada modificación y la estructura de las distintas ramas de trabajo. Sin esta carpeta, Git no podría realizar ninguna de sus funciones, ya que es donde reside la “memoria” del proyecto.
Una vez que un repositorio está inicializado, Git comienza a vigilar los archivos que contiene. Cada vez que se realizan cambios, estos pueden ser registrados de forma consciente por el usuario, creando nuevas versiones del proyecto. De este modo, el desarrollador tiene el control total sobre cuándo se guarda un cambio importante y qué modificaciones forman parte de cada versión.
Git se utiliza para llevar un control detallado de los cambios realizados en un proyecto. Esto significa que es posible saber exactamente qué archivo se ha modificado, qué parte del contenido ha cambiado y en qué momento ocurrió. Este nivel de detalle es especialmente útil cuando se trabaja durante largos periodos de tiempo o cuando varias personas intervienen en el mismo proyecto.
Otra función clave de Git es la posibilidad de comparar versiones antiguas y nuevas. Gracias al historial que mantiene, se pueden analizar las diferencias entre distintas versiones de un mismo archivo o del proyecto completo. Esto permite entender cómo ha evolucionado el contenido, detectar errores introducidos recientemente o revisar decisiones tomadas en etapas anteriores del desarrollo.
Git también permite recuperar archivos eliminados o modificados por error. En un entorno sin control de versiones, borrar un archivo importante puede suponer una pérdida definitiva. Con Git, ese archivo sigue existiendo en versiones anteriores del proyecto, por lo que se puede restaurar fácilmente sin afectar al resto del trabajo realizado posteriormente.
Una de las características más potentes de Git es la posibilidad de trabajar en paralelo mediante ramas. Las ramas permiten crear líneas de desarrollo independientes dentro de un mismo proyecto. Esto significa que se pueden probar nuevas ideas, añadir funcionalidades o realizar cambios importantes sin alterar la versión principal del proyecto. Si el resultado es satisfactorio, esos cambios se pueden integrar; si no, se pueden descartar sin consecuencias.
El uso de ramas facilita enormemente la organización del trabajo, tanto a nivel individual como en equipo. Permite separar tareas, experimentar con seguridad y mantener siempre una versión estable del proyecto disponible. Este sistema es una de las razones por las que Git se ha convertido en una herramienta tan popular en el desarrollo profesional.
Git también se utiliza para coordinar el trabajo de varias personas. En proyectos colaborativos, cada miembro del equipo puede trabajar sobre su propia copia del repositorio, realizando cambios de forma independiente. Posteriormente, estos cambios se pueden combinar de manera controlada, evitando conflictos y manteniendo un historial claro de quién ha hecho cada aportación.
Una de las grandes ventajas de Git es que la mayoría de sus operaciones se realizan en local. Esto significa que acciones como guardar versiones, consultar el historial o crear ramas no requieren conexión a internet. Al trabajar de forma local, Git es muy rápido y permite al usuario seguir trabajando incluso sin acceso a una red.
La conexión a internet solo es necesaria cuando se desea compartir los cambios con otros usuarios o sincronizar el repositorio local con uno remoto. Esta independencia de la red convierte a Git en una herramienta muy flexible, adaptada tanto al trabajo individual como al trabajo en equipo.
En conjunto, Git no es solo una herramienta técnica, sino una forma organizada y segura de trabajar con archivos en constante evolución. Su uso mejora la calidad del trabajo, reduce errores y permite afrontar proyectos complejos con mayor confianza y control.




3. Sistema de control de versiones distribuido
El concepto de sistema de control de versiones distribuido es uno de los pilares fundamentales de Git y una de las razones principales por las que se ha convertido en el sistema más utilizado en la actualidad. Cuando se dice que Git es distribuido, se hace referencia a que no existe una única copia central del proyecto de la que dependan todos los usuarios, sino que cada persona que trabaja con el proyecto dispone de una copia completa e independiente del repositorio.
En los sistemas de control de versiones más antiguos, el funcionamiento se basaba en un servidor central que contenía el proyecto. Los usuarios se conectaban a ese servidor para obtener los archivos y enviar sus cambios. Si el servidor fallaba o no estaba disponible, el trabajo se detenía. Además, los usuarios no tenían acceso al historial completo del proyecto, sino solo a la versión que descargaban en ese momento.
En Git, el enfoque es totalmente distinto. Cada vez que un usuario clona un repositorio, lo que obtiene no es únicamente la última versión de los archivos, sino una copia íntegra del proyecto con todo su historial de cambios desde el primer momento en que se creó. Esto incluye todas las versiones anteriores, todos los commits realizados y toda la información asociada a ellos. Gracias a esto, cada copia del repositorio es, en sí misma, una copia de seguridad completa del proyecto.
Una de las consecuencias más importantes de este sistema distribuido es que cada usuario tiene una copia completa del proyecto en su propio ordenador. Esto significa que puede consultar el historial de cambios, revisar versiones anteriores o analizar modificaciones sin necesidad de conectarse a ningún servidor externo. El trabajo no depende constantemente de una conexión a internet, lo cual es especialmente útil en entornos con conexión limitada o cuando se trabaja desde distintos lugares.
El hecho de poder trabajar sin conexión es una ventaja clave. Un usuario puede modificar archivos, crear commits y organizar su trabajo de forma local sin necesidad de estar conectado a GitHub u otro servicio remoto. Todos esos cambios quedan registrados en su repositorio local y pueden sincronizarse más adelante cuando se disponga de conexión. Esto aporta una gran libertad y flexibilidad en la forma de trabajar.
Otro aspecto fundamental del sistema distribuido es la reducción del riesgo de pérdida de datos. Al existir múltiples copias completas del repositorio en diferentes ordenadores, la información no depende de un único punto. Si un repositorio remoto se pierde o se daña, es posible recuperarlo a partir de cualquiera de las copias locales existentes. Cada clon actúa como una copia de seguridad del proyecto completo.
La colaboración entre equipos también se ve enormemente beneficiada por este enfoque distribuido. Cada miembro del equipo puede trabajar de forma independiente en su propia copia del repositorio, realizando cambios, pruebas y mejoras sin interferir directamente con el trabajo de los demás. Posteriormente, esos cambios pueden integrarse en el repositorio remoto común, manteniendo un historial claro y ordenado de todas las contribuciones.
Cuando se clona un repositorio, el proceso implica la descarga de todos los archivos del proyecto junto con toda la información histórica almacenada en Git. Esto permite consultar cualquier cambio realizado desde el inicio del proyecto, analizar cómo ha evolucionado el código, entender por qué se tomaron ciertas decisiones y recuperar versiones anteriores si es necesario. No se trata solo de trabajar con el presente del proyecto, sino de tener acceso completo a su pasado.
Este acceso total al historial convierte a Git en una herramienta muy potente para el aprendizaje, el mantenimiento y la mejora continua de proyectos. Cualquier error puede rastrearse hasta el momento exacto en que se introdujo, y cualquier versión estable puede recuperarse sin dificultad. Todo esto es posible gracias a la naturaleza distribuida del sistema.
En resumen, el sistema de control de versiones distribuido de Git proporciona independencia, seguridad, flexibilidad y una enorme capacidad de colaboración. Cada copia del repositorio es completa, autosuficiente y plenamente funcional, lo que hace que el trabajo con Git sea robusto y adaptable a prácticamente cualquier entorno o necesidad.


4. Estados de los archivos en Git
Git organiza y gestiona los archivos de un proyecto mediante un sistema de estados que permite saber en todo momento en qué punto del proceso de control de versiones se encuentra cada archivo. Esta clasificación es fundamental para entender cómo funciona Git internamente y para trabajar de forma ordenada y segura con los cambios que se realizan en un proyecto.
Cada archivo dentro de un repositorio puede encontrarse en uno de tres estados principales. Estos estados reflejan el grado de preparación del archivo para formar parte del historial del proyecto y permiten al usuario decidir con precisión qué cambios se van a guardar y cuáles no. Gracias a este sistema, Git evita que se confirmen cambios por accidente o que se incluyan modificaciones que aún no están listas.
El primer estado es el estado modificado. Un archivo se encuentra en estado modificado cuando ha sido alterado en el directorio de trabajo, es decir, cuando el usuario ha cambiado su contenido respecto a la última versión guardada. Estos cambios pueden ser tan simples como corregir una línea o tan complejos como reescribir gran parte del archivo. Git detecta automáticamente que el archivo ha sido modificado, pero en este punto no guarda esos cambios en el historial.
Los archivos en estado modificado existen únicamente en el entorno de trabajo local del usuario. Esto significa que los cambios aún no forman parte del repositorio como tal y podrían perderse si no se gestionan correctamente. Este estado permite experimentar, probar y modificar libremente los archivos sin afectar todavía al historial del proyecto. Es una fase de trabajo flexible donde se pueden hacer ajustes antes de decidir qué cambios merecen ser registrados.
El segundo estado es el estado preparado. Un archivo pasa a este estado cuando el usuario decide explícitamente que los cambios realizados deben formar parte de la próxima versión del proyecto. Preparar un archivo implica seleccionar su estado actual y marcarlo como listo para ser guardado. En este punto, Git toma una instantánea del archivo tal y como se encuentra y la almacena temporalmente para su posterior confirmación.
El estado preparado es especialmente importante porque permite un control muy preciso sobre los cambios que se van a registrar. El usuario puede elegir preparar solo algunos archivos y dejar otros fuera, incluso aunque todos hayan sido modificados. Esto es muy útil cuando se han realizado distintos tipos de cambios y se quiere mantener un historial limpio y bien organizado, separando cada conjunto de modificaciones en commits distintos.
Además, preparar un archivo no significa que los cambios ya estén definitivamente guardados. El archivo preparado todavía puede ser modificado de nuevo antes de la confirmación, lo que generaría nuevas diferencias entre el directorio de trabajo y la versión preparada. Esto refuerza la idea de que Git ofrece múltiples niveles de control antes de registrar un cambio de forma permanente.
El tercer estado es el estado confirmado. Un archivo alcanza este estado cuando los cambios preparados se guardan definitivamente en el repositorio. En este momento, Git registra una nueva versión del archivo en su historial interno, junto con información adicional como la fecha, el autor y el mensaje descriptivo del cambio. A partir de este punto, los cambios pasan a formar parte de la historia del proyecto.
Los archivos en estado confirmado están almacenados de manera segura dentro del repositorio Git. Esto significa que pueden recuperarse en cualquier momento, compararse con versiones anteriores o utilizarse como referencia para futuras modificaciones. El estado confirmado representa un punto estable del proyecto y suele corresponder a avances significativos o cambios que ya han sido revisados y considerados correctos.
Este sistema de estados proporciona un control muy detallado del proceso de guardado de versiones. Permite separar claramente el trabajo en progreso de los cambios que están listos para ser registrados, evitando errores habituales como confirmar archivos a medio terminar o incluir modificaciones que no deberían formar parte del commit. Gracias a esta estructura, Git facilita una forma de trabajo más consciente y organizada.
En conjunto, los estados modificado, preparado y confirmado forman un flujo de trabajo lógico y seguro. El usuario modifica archivos libremente, selecciona cuidadosamente qué cambios desea guardar y finalmente confirma solo aquello que realmente debe formar parte del historial. Este mecanismo es una de las claves que hacen de Git una herramienta tan potente y fiable para el control de versiones.


5. Ubicación de los archivos en Git
Para comprender correctamente cómo funciona Git, no basta con conocer los estados de los archivos, sino que también es fundamental entender las distintas ubicaciones en las que pueden encontrarse. Git trabaja con tres ubicaciones principales que representan las diferentes fases por las que pasan los archivos desde que se modifican hasta que se almacenan de forma permanente en el historial del proyecto.
Estas ubicaciones no son tres carpetas visibles iguales entre sí, sino tres niveles lógicos que permiten a Git organizar el trabajo del usuario y gestionar los cambios de manera segura y controlada. Cada ubicación cumple una función concreta dentro del flujo de trabajo del control de versiones.
La primera ubicación es el directorio de trabajo. El directorio de trabajo es la carpeta local del sistema donde el usuario trabaja directamente con los archivos del proyecto. En este directorio se crean nuevos archivos, se editan los existentes y se eliminan aquellos que ya no son necesarios. Es el espacio de trabajo habitual, donde se desarrolla el proyecto de forma activa.
Los archivos que se encuentran en el directorio de trabajo reflejan el estado actual del proyecto tal y como lo ve el usuario en su ordenador. Cuando se modifica un archivo en esta ubicación, Git detecta el cambio automáticamente y lo marca como modificado. Sin embargo, esos cambios aún no forman parte del historial del repositorio ni están protegidos frente a pérdidas accidentales.
El directorio de trabajo permite trabajar con total libertad. El usuario puede probar ideas, corregir errores o realizar cambios sin que estos afecten inmediatamente a la versión oficial del proyecto. Esta separación entre el trabajo diario y el historial del repositorio es clave para evitar errores y mantener la estabilidad del proyecto.
La segunda ubicación es la zona de preparación. Esta zona actúa como un área intermedia entre el directorio de trabajo y el repositorio definitivo. En la zona de preparación, Git guarda la información de los archivos que el usuario ha decidido incluir en la próxima versión del proyecto.
La zona de preparación no es un directorio visible como el directorio de trabajo. Se trata de un área interna gestionada por Git, donde se almacena una especie de lista que indica qué archivos y qué versiones concretas de esos archivos están listas para ser confirmadas. Esta zona permite seleccionar de forma precisa qué cambios se van a guardar y cuáles se quedarán fuera.
Gracias a la zona de preparación, el usuario no está obligado a confirmar todos los cambios realizados. Puede elegir solo algunos archivos o incluso partes concretas del trabajo, dejando otros cambios para más adelante. Esto ayuda a mantener un historial más limpio, organizado y fácil de entender, especialmente en proyectos grandes o colaborativos.
La tercera ubicación es el directorio Git. El directorio Git es una carpeta interna que Git crea dentro del proyecto y que contiene toda la información necesaria para el control de versiones. Aunque normalmente no se manipula directamente, es el corazón del repositorio y la parte más importante del sistema.
En el directorio Git se almacenan los commits, las ramas, las referencias y todos los metadatos asociados al proyecto. Cada vez que se confirma un conjunto de cambios, Git guarda una nueva versión dentro de este directorio. Esta información permite reconstruir cualquier estado anterior del proyecto y analizar su evolución a lo largo del tiempo.
El directorio Git es también el elemento que se copia cuando se clona un repositorio. Gracias a él, cada copia del proyecto contiene el historial completo, lo que refuerza el carácter distribuido de Git. Sin este directorio, Git no podría funcionar, ya que perdería la referencia de todas las versiones y cambios realizados.
En conjunto, estas tres ubicaciones forman un flujo de trabajo claro y estructurado. El usuario trabaja en el directorio de trabajo, selecciona los cambios importantes en la zona de preparación y finalmente los guarda de forma permanente en el directorio Git. Esta organización interna es una de las razones por las que Git ofrece tanto control y fiabilidad en la gestión de versiones.




6. Qué es un commit y por qué es tan importante
Un commit es uno de los conceptos más importantes dentro del funcionamiento de Git. Representa una versión concreta del proyecto en un momento determinado y actúa como una fotografía exacta del estado de los archivos que han sido seleccionados previamente en la zona de preparación. Cada commit captura cómo se encontraba el proyecto en ese instante y lo guarda de forma permanente en el historial del repositorio.
Cuando se realiza un commit, Git no solo guarda los archivos tal como están en ese momento, sino que también almacena información adicional que describe el cambio. Esta información incluye un mensaje descriptivo escrito por el usuario, que explica qué se ha modificado y con qué objetivo. Este mensaje es fundamental, ya que permite entender el sentido de cada cambio incluso mucho tiempo después de haberlo realizado.
Los commits permiten avanzar en el desarrollo del proyecto de una manera estructurada y controlada. En lugar de acumular cambios sin orden, cada conjunto de modificaciones importantes queda registrado como una unidad lógica. Esto ayuda a dividir el trabajo en pasos claros y coherentes, facilitando tanto el desarrollo individual como el trabajo en equipo.
Una de las grandes ventajas de los commits es que crean un historial detallado del proyecto. Gracias a este historial, es posible recorrer la evolución del proyecto desde su inicio hasta su estado actual. Cada commit representa un punto estable que puede ser consultado, analizado o recuperado si es necesario. Esto aporta seguridad y tranquilidad durante el desarrollo.
El uso correcto de commits también facilita enormemente la localización de errores. Si en algún momento aparece un fallo en el proyecto, se puede revisar el historial de commits para identificar cuándo se introdujo el problema. Al tener los cambios bien separados y documentados, resulta mucho más sencillo detectar el origen del error y corregirlo sin afectar al resto del trabajo.
Otra función clave de los commits es la posibilidad de volver a versiones anteriores. Si un cambio reciente no funciona como se esperaba o provoca problemas, se puede recuperar un estado anterior del proyecto de forma sencilla. Esto evita la pérdida de trabajo y permite experimentar con nuevas ideas sin miedo a romper el proyecto de forma irreversible.
En el trabajo en equipo, los commits juegan un papel esencial. Cada miembro del equipo puede realizar commits con sus propios cambios, dejando constancia clara de qué ha hecho y por qué. Esto mejora la comunicación entre los desarrolladores y evita confusiones, ya que todos pueden ver el progreso del proyecto y entender las decisiones tomadas.
Además, los commits bien realizados ayudan a mantener un proyecto organizado y profesional. Un historial claro, con mensajes descriptivos y cambios bien delimitados, facilita el mantenimiento del proyecto a largo plazo. Incluso personas que no participaron en el desarrollo inicial pueden comprender rápidamente cómo funciona el proyecto y cómo ha evolucionado.
En definitiva, un commit no es solo una acción técnica, sino una forma de documentar el trabajo. Representa una decisión consciente de guardar un conjunto de cambios con un objetivo concreto. Por ello, aprender a utilizar los commits de forma correcta es una de las habilidades más importantes al trabajar con Git y con cualquier sistema de control de versiones moderno.

7. GitHub y su función principal
GitHub es una plataforma basada en la web cuya función principal es alojar repositorios Git en la nube. Actúa como un repositorio remoto al que se pueden subir los proyectos desarrollados en local, permitiendo que estos estén disponibles desde cualquier lugar y en cualquier momento. GitHub se ha convertido en una herramienta fundamental en el desarrollo moderno, tanto en proyectos individuales como en trabajos colaborativos.
Es importante entender que GitHub no sustituye a Git. Git es el sistema de control de versiones que se ejecuta en el ordenador del usuario y gestiona los cambios de los archivos de forma local. GitHub, en cambio, funciona como un complemento que permite almacenar esos repositorios en internet, compartirlos y sincronizarlos con otros usuarios o con otros dispositivos del mismo usuario.
La relación entre Git y GitHub se basa en la sincronización. El usuario trabaja normalmente en su repositorio local utilizando Git, realizando cambios, creando commits y organizando el proyecto. Cuando desea compartir esos cambios o guardarlos en la nube, los sincroniza con GitHub. Del mismo modo, si hay cambios realizados directamente en el repositorio remoto, estos pueden descargarse al repositorio local.
Una de las funciones más importantes de GitHub es la posibilidad de crear repositorios públicos y privados. Los repositorios públicos son visibles para cualquier persona y se utilizan habitualmente para proyectos de código abierto o trabajos que se quieren compartir. Los repositorios privados, en cambio, solo son accesibles para los usuarios autorizados, lo que permite trabajar en proyectos personales o empresariales con mayor privacidad.
GitHub facilita enormemente la colaboración entre usuarios. Varios desarrolladores pueden trabajar sobre el mismo proyecto, cada uno desde su propio ordenador, y sincronizar sus cambios en un único repositorio remoto. Esto permite que el trabajo se reparta de forma eficiente y que todos los miembros del equipo tengan acceso a la última versión del proyecto y a su historial completo.
Otra función clave de GitHub es servir como copia de seguridad del proyecto. Al estar alojado en la nube, el repositorio remoto actúa como respaldo frente a pérdidas de datos locales, fallos del sistema o errores humanos. Aunque Git ya es un sistema distribuido, contar con un repositorio remoto añade una capa adicional de seguridad.
GitHub también permite visualizar de forma clara el historial de commits. A través de su interfaz web, se pueden consultar todos los commits realizados en un repositorio, ver cuándo se hicieron, quién los realizó y qué archivos se modificaron. Esta visualización facilita la comprensión del desarrollo del proyecto y resulta especialmente útil en entornos educativos y profesionales.
Además, GitHub ofrece herramientas adicionales que mejoran la gestión de proyectos, como la posibilidad de añadir descripciones, documentación y archivos README que explican el propósito del repositorio. Esto ayuda a que cualquier persona que acceda al proyecto pueda entender rápidamente de qué trata y cómo utilizarlo.
Una de las funcionalidades más destacadas de GitHub es GitHub Pages. Este servicio permite publicar proyectos web directamente desde un repositorio, siempre que el contenido sea compatible, como páginas HTML y CSS. Gracias a GitHub Pages, un repositorio puede convertirse en una página web accesible públicamente, lo que resulta muy útil para mostrar trabajos, prácticas o proyectos finales.
En conjunto, GitHub actúa como el punto de encuentro entre el control de versiones y la colaboración en línea. No solo almacena repositorios, sino que facilita el trabajo en equipo, mejora la organización de los proyectos y permite compartir resultados de forma sencilla y profesional. Por este motivo, GitHub se ha convertido en una herramienta imprescindible para estudiantes, desarrolladores y equipos de trabajo en el ámbito de la informática.



8. Diferencias fundamentales entre Git y GitHub
Aunque Git y GitHub están estrechamente relacionados y suelen utilizarse juntos, cumplen funciones distintas y es fundamental comprender sus diferencias para utilizarlos correctamente. Confundir ambos conceptos es habitual, especialmente al comenzar, pero entender qué hace cada uno permite aprovechar todo su potencial.
Git es una herramienta que se ejecuta de forma local en el ordenador del usuario. Una vez instalada, permite gestionar el control de versiones directamente sobre las carpetas del sistema. Git funciona sin necesidad de conexión a internet, ya que todas las operaciones principales, como registrar cambios, consultar el historial o recuperar versiones anteriores, se realizan en el propio equipo. Esto hace que Git sea rápido, flexible y muy fiable incluso en entornos sin acceso a la red.
El objetivo principal de Git es controlar versiones. Se encarga de registrar cada cambio que se realiza en los archivos, mantener un historial completo del proyecto y permitir al usuario moverse entre distintas versiones según sea necesario. Git trabaja con repositorios locales y guarda toda la información del proyecto dentro de la carpeta interna del repositorio, lo que garantiza que el historial esté siempre disponible.
GitHub, en cambio, es un servicio online que funciona a través de internet. No se instala como un programa tradicional, sino que se accede mediante un navegador web. GitHub aloja repositorios Git en la nube, actuando como un repositorio remoto al que los usuarios pueden subir sus proyectos. Para utilizar GitHub es imprescindible disponer de conexión a internet, ya que todas las operaciones se realizan contra servidores externos.
La función principal de GitHub es facilitar la colaboración y el acceso remoto a los proyectos. Permite que varias personas trabajen sobre el mismo repositorio, compartan cambios y mantengan sincronizadas sus versiones. Además, GitHub sirve como punto central donde se almacena una copia del proyecto, accesible desde cualquier lugar y dispositivo.
Desde el punto de vista histórico, Git fue creado en el año 2005 por Linus Torvalds con el objetivo de gestionar el desarrollo del núcleo de Linux. Su diseño se centró en la velocidad, la eficiencia y la seguridad del historial de versiones. GitHub apareció más tarde, en 2008, como una plataforma que aprovechaba Git para ofrecer un entorno colaborativo en la web. En 2018, GitHub fue adquirido por Microsoft, lo que consolidó aún más su posición como plataforma líder en alojamiento de repositorios.
Otra diferencia importante es el tipo de tareas que se realizan en cada uno. Con Git se trabaja principalmente en local, creando commits, organizando versiones y gestionando el desarrollo del proyecto. Con GitHub se gestionan aspectos como la visibilidad del repositorio, la colaboración entre usuarios, la documentación y la publicación de proyectos.
Aunque Git y GitHub pueden utilizarse de forma independiente, su uso conjunto es lo más habitual y lo más eficaz. Git puede funcionar sin GitHub, ya que permite el control de versiones en local sin necesidad de servicios externos. Del mismo modo, GitHub no tiene sentido sin Git, ya que depende de este sistema para gestionar los repositorios que aloja.
En el desarrollo moderno, Git y GitHub forman una combinación esencial. Git aporta el control preciso y detallado de las versiones, mientras que GitHub añade la dimensión colaborativa y remota. Juntos permiten trabajar de forma profesional, organizada y segura en proyectos informáticos, tanto individuales como en equipo.


9. Instalación y configuración inicial de Git
Antes de comenzar a utilizar Git de forma efectiva, es imprescindible realizar una instalación correcta del sistema en el ordenador. Git es un software que debe estar presente en el sistema operativo para poder gestionar repositorios locales y trabajar con el control de versiones. Sin esta instalación previa, no es posible utilizar ninguna de las funcionalidades que ofrece Git.
El proceso de instalación depende del sistema operativo, pero el objetivo es el mismo en todos los casos: disponer de Git como herramienta disponible en el sistema para poder ejecutarlo desde la línea de comandos o desde entornos de desarrollo como Visual Studio Code. Una vez instalado, es fundamental comprobar que la instalación se ha realizado correctamente. Para ello, se verifica la versión instalada de Git, lo que confirma que el sistema reconoce la herramienta y que está lista para ser utilizada.
Tras la instalación, el siguiente paso esencial es la configuración inicial de Git. Esta configuración no afecta a un solo proyecto, sino que define la identidad del usuario en todos los repositorios del sistema. Git necesita saber quién realiza cada cambio para poder registrar correctamente la autoría de las modificaciones. Esta información es clave en proyectos colaborativos, donde varias personas trabajan sobre los mismos archivos.
La identidad del usuario en Git se compone principalmente de dos datos: el nombre del usuario y su dirección de correo electrónico. Estos datos se asocian a cada commit que se realiza y permiten identificar quién ha realizado cada modificación dentro del historial del proyecto. Gracias a esta información, es posible saber quién introdujo un cambio concreto, en qué momento y con qué propósito.
La configuración de estos datos se realiza de forma global, lo que significa que se aplican automáticamente a todos los repositorios que el usuario cree o utilice en ese ordenador. Esto evita tener que configurar la identidad repetidamente en cada proyecto y garantiza coherencia en el historial de versiones. En el sistema, esta información se guarda en un archivo de configuración interno que Git consulta cada vez que se registra un cambio.
Esta fase de configuración es especialmente importante cuando Git se utiliza junto con plataformas como GitHub. En estos casos, el correo electrónico configurado en Git debe coincidir con el correo asociado a la cuenta de GitHub para que los commits queden correctamente vinculados al perfil del usuario en la plataforma. De esta manera, GitHub puede mostrar quién ha realizado cada commit y mantener un historial claro y organizado.
Además, la configuración inicial ayuda a evitar problemas de identificación, especialmente en entornos compartidos o en ordenadores utilizados por varias personas. Si no se configura correctamente la identidad, los commits podrían aparecer sin autor claro o con datos incorrectos, lo que dificulta el trabajo en equipo y la trazabilidad de los cambios.
En resumen, la instalación y configuración inicial de Git es un paso obligatorio y fundamental para trabajar con control de versiones de forma profesional. Instalar Git garantiza que la herramienta esté disponible en el sistema, mientras que la configuración de la identidad del usuario permite registrar los cambios de manera clara, ordenada y correctamente atribuida. Sin esta preparación previa, el uso de Git pierde gran parte de su utilidad y fiabilidad.


10. Ramas y rama por defecto
Las ramas son uno de los conceptos más importantes y potentes dentro de Git. Permiten trabajar en distintas líneas de desarrollo de un mismo proyecto de forma paralela, sin que los cambios de una línea afecten directamente a otra. Gracias a las ramas, es posible experimentar, corregir errores o desarrollar nuevas funcionalidades sin poner en riesgo la versión estable del proyecto.
Una rama puede entenderse como una copia independiente del proyecto en un momento determinado. Cada rama tiene su propio historial de commits y evoluciona de manera separada. Esto significa que los cambios realizados en una rama no afectan al resto hasta que se decide integrarlos. Esta característica es fundamental tanto en proyectos individuales como en proyectos colaborativos, ya que permite organizar el trabajo de forma mucho más segura y estructurada.
La rama principal es la que contiene la versión estable del proyecto. En ella se mantiene el código que se considera listo para su uso o publicación. Normalmente, esta rama refleja el estado más fiable del proyecto y es la que se sincroniza con los repositorios remotos para compartir el trabajo con otros usuarios o para publicar el proyecto, por ejemplo, mediante GitHub Pages.
Durante muchos años, en las versiones antiguas de Git, la rama principal recibía el nombre de master. Este nombre se utilizó por defecto en millones de repositorios y formó parte del flujo de trabajo tradicional de Git durante mucho tiempo. Sin embargo, con la evolución de las herramientas y las prácticas de desarrollo, se decidió adoptar un nombre más neutro y descriptivo.
En versiones más recientes de Git, la rama principal se denomina main. Este cambio comenzó a aplicarse a partir de Git 2.28 y fue adoptado también por GitHub en el año 2020. Desde ese momento, todos los repositorios nuevos creados en GitHub utilizan main como rama principal por defecto. No obstante, muchos repositorios antiguos siguen utilizando master, ya que el nombre de la rama depende de cómo se creó inicialmente el repositorio.
Es importante entender que el nombre de la rama principal no afecta al funcionamiento técnico de Git. Tanto master como main cumplen exactamente la misma función. La diferencia es únicamente nominal, pero utilizar el nombre correcto evita confusiones, especialmente cuando se trabaja con repositorios nuevos o en entornos educativos y profesionales.
Git permite configurar la rama por defecto para que todos los repositorios nuevos utilicen siempre el mismo nombre. Esta configuración se realiza una sola vez y asegura que, cada vez que se inicializa un repositorio, la rama principal tenga el nombre deseado. De este modo, se mantiene coherencia entre proyectos y se evitan errores derivados de trabajar en una rama equivocada.
La configuración de la rama por defecto resulta especialmente útil cuando se crean muchos repositorios desde línea de comandos o cuando se trabaja en distintos equipos. Tener un estándar claro para el nombre de la rama principal facilita la organización del trabajo, la documentación y la comunicación entre los miembros de un equipo.
En el contexto de GitHub, la rama por defecto tiene un papel clave. Es la rama que se muestra por defecto al acceder al repositorio, la que se utiliza para generar la documentación principal y la que suele asociarse a servicios como GitHub Pages. Por este motivo, es importante saber cuál es la rama principal y trabajar correctamente sobre ella.
En resumen, las ramas permiten desarrollar proyectos de forma paralela, ordenada y segura. La rama principal representa la versión estable del proyecto y su nombre ha evolucionado de master a main en las versiones más recientes de Git y GitHub. Configurar correctamente la rama por defecto ayuda a evitar confusiones, mejora la organización del trabajo y garantiza un flujo de desarrollo más claro y profesional.


11. Creación de repositorios en GitHub
GitHub permite crear repositorios directamente desde su interfaz web, sin necesidad de utilizar herramientas locales en un primer momento. Este proceso es sencillo, pero muy importante, ya que define cómo se va a estructurar y organizar el proyecto desde el inicio. Al crear un repositorio en GitHub, se establecen las bases del trabajo futuro, tanto si se trata de un proyecto individual como de un proyecto colaborativo.
Durante la creación de un repositorio, GitHub solicita una serie de datos fundamentales. En primer lugar, se debe indicar el nombre del repositorio. Este nombre identifica al proyecto y debe ser claro, representativo y fácil de reconocer. Normalmente se recomienda que el nombre esté relacionado con el contenido o el objetivo del proyecto, ya que será visible para otros usuarios si el repositorio es público.
Otro aspecto clave es la visibilidad del repositorio. GitHub permite elegir entre repositorios públicos y privados. Un repositorio público puede ser visto por cualquier persona, aunque solo los colaboradores autorizados pueden modificarlo. Este tipo de repositorio es necesario si se quiere utilizar GitHub Pages para publicar un proyecto web. Por otro lado, un repositorio privado solo es accesible para el propietario y los usuarios a los que se les haya concedido permiso, lo que resulta útil para proyectos personales o trabajos en desarrollo que no se desean compartir públicamente.
Uno de los puntos más importantes al crear un repositorio es decidir si se desea incluir un archivo README inicial. El archivo README es un documento que suele contener una descripción general del proyecto, su finalidad y, en muchos casos, instrucciones básicas de uso. Aunque su contenido puede modificarse más adelante, la decisión de crearlo o no en el momento inicial afecta directamente al estado del repositorio.
Si el repositorio se crea incluyendo el archivo README, GitHub lo inicializa automáticamente como un repositorio Git completo. Esto significa que el repositorio ya contiene una rama principal, un primer commit y está listo para ser clonado directamente en un ordenador local. Este método es muy habitual cuando se empieza un proyecto desde cero directamente en GitHub o cuando se quiere trabajar a partir de una estructura ya creada en la plataforma.
En cambio, si el repositorio se crea sin archivo README, el repositorio queda vacío y no inicializado. Este tipo de repositorio se utiliza normalmente cuando ya existe un proyecto en local y se quiere subir a GitHub. En este caso, el repositorio de GitHub actúa únicamente como destino remoto, y será el repositorio local el que se inicialice y sincronice posteriormente.
GitHub, al crear un repositorio vacío, muestra una serie de indicaciones que explican los distintos escenarios posibles. Estas indicaciones sirven como guía para enlazar un repositorio local nuevo, sincronizar un proyecto ya existente o clonar un repositorio inicializado. De esta forma, GitHub se adapta a distintos flujos de trabajo y niveles de experiencia del usuario.
La elección entre crear un repositorio con README o vacío depende directamente del flujo de trabajo que se quiera seguir. Si el proyecto va a comenzar desde GitHub y luego continuar en local, lo más práctico es crear el repositorio inicializado. Si, por el contrario, el proyecto ya existe en el ordenador y se quiere subir tal como está, lo más adecuado es crear el repositorio vacío.
En entornos educativos y profesionales, comprender esta diferencia es fundamental. Una mala elección puede generar conflictos al sincronizar repositorios locales y remotos, mientras que una decisión correcta facilita enormemente el trabajo y evita errores innecesarios.
En resumen, la creación de repositorios en GitHub es un proceso sencillo pero clave. Elegir correctamente el nombre, la visibilidad y la inicialización del repositorio determina cómo se va a trabajar con Git y GitHub. Entender estas opciones permite adaptar el repositorio al flujo de trabajo deseado y garantiza una gestión del proyecto más clara, ordenada y eficiente.

12. Clonar repositorios y trabajar en local
Clonar un repositorio consiste en crear una copia local exacta de un repositorio remoto que se encuentra alojado en GitHub. Cuando se realiza una clonación, no solo se descargan los archivos actuales del proyecto, sino también todo su historial de versiones. Esto significa que el repositorio local contiene la información completa de todos los cambios que se han realizado desde que el proyecto fue creado.
Esta copia local se guarda en una carpeta del ordenador del usuario y pasa a ser un repositorio Git completamente funcional. A partir de ese momento, el usuario puede trabajar sobre los archivos como si se tratara de cualquier otro proyecto local, editando, añadiendo o eliminando archivos según sea necesario, pero con la ventaja de que Git registra todos los cambios.
Trabajar en local es una de las grandes ventajas de Git. El usuario no depende de una conexión constante a internet para avanzar en el proyecto. Puede modificar archivos, organizar el contenido, probar nuevas ideas o corregir errores sin que estos cambios afecten directamente al repositorio remoto. Todo el trabajo se realiza de forma segura en el entorno local.
Mientras se trabaja en local, los cambios quedan registrados en el repositorio local mediante commits. Estos commits permiten guardar versiones intermedias del proyecto, documentar el progreso y mantener un historial claro de lo que se va haciendo. Hasta que el usuario decide sincronizar, el repositorio remoto permanece sin cambios.
Este sistema resulta especialmente útil cuando se trabaja con archivos como hojas de estilo CSS, documentos HTML u otros recursos de un proyecto web. Por ejemplo, se pueden hacer múltiples ajustes de diseño, reorganizar estilos o probar diferentes configuraciones sin riesgo de estropear la versión publicada del proyecto. Solo cuando se está seguro de que los cambios son correctos, se sincronizan con el repositorio remoto.
Además, clonar un repositorio facilita enormemente el trabajo en equipo. Cada persona puede clonar el mismo repositorio y trabajar en su propia copia local. De este modo, cada desarrollador tiene su espacio de trabajo independiente, evitando conflictos directos y permitiendo que los cambios se integren de forma ordenada cuando estén listos.
Otra ventaja importante es que, al disponer del historial completo, el usuario puede consultar versiones anteriores del proyecto en cualquier momento. Esto permite analizar cómo ha evolucionado el código, entender por qué se tomaron ciertas decisiones o recuperar partes del trabajo si algo sale mal.
En resumen, clonar un repositorio y trabajar en local es una parte esencial del flujo de trabajo con Git y GitHub. Permite desarrollar proyectos de forma cómoda, segura y organizada, manteniendo siempre una separación clara entre el trabajo local y la versión compartida en la nube. Esta forma de trabajar aporta control, flexibilidad y confianza a la hora de gestionar cualquier proyecto informático.


13. Sincronización entre repositorio local y remoto
La sincronización entre el repositorio local y el repositorio remoto es el proceso que permite mantener ambos siempre actualizados y coherentes. Gracias a este sistema, el trabajo que se realiza en el ordenador del usuario puede compartirse con otras personas y almacenarse de forma segura en GitHub.
El repositorio local es donde el usuario trabaja directamente con los archivos del proyecto. Aquí se hacen modificaciones, se crean nuevas versiones mediante commits y se prueban los cambios sin afectar al proyecto compartido. El repositorio remoto, por su parte, es la copia del proyecto que se encuentra en GitHub y que sirve como punto común para todos los colaboradores.
Subir cambios consiste en enviar los commits que se han creado en el repositorio local al repositorio remoto. De esta forma, las modificaciones pasan a formar parte del proyecto compartido y quedan disponibles para el resto del equipo. Este paso suele realizarse cuando el trabajo está terminado o cuando se quiere guardar una versión estable del proyecto en la nube.
Descargar cambios significa actualizar la copia local con las modificaciones que se han realizado en el repositorio remoto. Esto es especialmente importante cuando se trabaja en equipo, ya que otros usuarios pueden haber añadido nuevas funciones, corregido errores o modificado archivos. Al descargar estos cambios, el usuario se asegura de estar trabajando siempre sobre la versión más reciente del proyecto.
La sincronización permite trabajar desde distintos ordenadores sin perder información. Por ejemplo, un usuario puede empezar un proyecto en un ordenador y continuar más tarde desde otro distinto, simplemente sincronizando el repositorio local con el remoto. Todo el historial de cambios se mantiene intacto, independientemente del dispositivo utilizado.
En entornos de trabajo colaborativos, la sincronización es clave para evitar conflictos. Cada persona trabaja en su repositorio local, realiza sus propios commits y luego sincroniza sus cambios. Git se encarga de integrar las modificaciones de forma ordenada y de avisar si existen conflictos que deban resolverse manualmente.
Este sistema también actúa como una copia de seguridad constante. Al subir los cambios a GitHub, el proyecto queda almacenado en la nube, reduciendo el riesgo de pérdida de datos por fallos del ordenador o errores accidentales. Incluso si el repositorio local se elimina, siempre se puede volver a clonar el proyecto desde el repositorio remoto.
En resumen, la sincronización entre repositorio local y remoto es un pilar fundamental del uso de Git y GitHub. Permite compartir el trabajo, colaborar de forma segura, trabajar desde cualquier lugar y mantener el proyecto siempre actualizado. Sin este proceso, el control de versiones perdería gran parte de su utilidad en proyectos reales y en equipos de desarrollo.
14. GitHub Pages
GitHub Pages es un servicio integrado dentro de GitHub que permite publicar un sitio web directamente a partir de un repositorio. Su principal ventaja es que no requiere servidores externos ni configuraciones complejas, ya que el propio GitHub se encarga de mostrar el contenido del proyecto en forma de página web accesible desde una URL pública.
Para poder utilizar GitHub Pages, el repositorio debe ser público. En los repositorios privados, GitHub solicita una ampliación de cuenta para poder activar esta funcionalidad. Esto hace que GitHub Pages sea especialmente adecuada para proyectos educativos, prácticas académicas y pequeños proyectos personales que se quieran mostrar de forma abierta.
El funcionamiento de GitHub Pages se basa en los archivos que contiene el repositorio. GitHub toma el contenido de una rama concreta, normalmente la rama principal, y lo publica tal cual como una página web. Por este motivo, el repositorio debe contener un archivo principal llamado index.html, ya que este archivo actúa como punto de entrada del sitio web. Si no existe este archivo, la web no se mostrará correctamente o será necesario especificarlo manualmente en la URL.
La configuración de GitHub Pages se realiza desde las opciones del repositorio. Dentro del apartado de configuración se elige la sección correspondiente a Pages, donde se puede indicar qué rama se va a utilizar para la publicación y desde qué carpeta del repositorio. De forma habitual, se utiliza la rama principal y la carpeta raíz del proyecto, lo que simplifica mucho el proceso.
Una vez aplicada la configuración, GitHub procesa automáticamente el contenido del repositorio y genera una URL pública. Esta dirección permite acceder al sitio web desde cualquier navegador sin necesidad de descargar el proyecto. Cada vez que se realicen cambios en los archivos y se sincronicen con el repositorio remoto, la página web se actualizará reflejando las nuevas modificaciones.
GitHub Pages es especialmente útil para proyectos que utilizan tecnologías básicas como HTML y CSS. Permite ver el resultado final del proyecto de forma inmediata y comprobar que los archivos funcionan correctamente en un entorno real. Esto resulta muy práctico en asignaturas relacionadas con desarrollo web, ya que facilita la evaluación y la presentación de los trabajos.
Además, GitHub Pages convierte el repositorio en una especie de escaparate del proyecto. No solo se puede acceder al código, sino también al resultado visual del mismo. Por este motivo, es recomendable añadir una descripción clara del repositorio y enlazar la URL de la página publicada, de forma que cualquier persona pueda entender rápidamente el objetivo del proyecto y acceder a su contenido.
En definitiva, GitHub Pages es una herramienta sencilla pero muy potente que permite transformar un repositorio en una página web funcional. Su facilidad de uso, junto con su integración directa con GitHub, la convierten en una opción ideal para aprender, practicar y mostrar proyectos web de manera profesional sin complicaciones técnicas.

15. Visual Studio Code y el trabajo con Git
Visual Studio Code es un editor de código muy utilizado en el desarrollo web y la programación en general. Una de sus grandes ventajas es la integración directa con Git, lo que permite trabajar con repositorios sin necesidad de usar constantemente la línea de comandos. Esta integración facilita mucho el aprendizaje y el uso del control de versiones, especialmente para principiantes.
Desde Visual Studio Code es posible detectar automáticamente los cambios realizados en los archivos del proyecto. El editor compara el estado actual de los archivos con la última versión confirmada y muestra de forma visual qué archivos han sido modificados, cuáles son nuevos y cuáles han sido eliminados. Esta información se presenta de manera clara y accesible, lo que ayuda a mantener el control del proyecto en todo momento.
El editor permite preparar archivos para una nueva versión de forma sencilla. El usuario puede seleccionar qué archivos quiere incluir y cuáles no, evitando así guardar cambios incompletos o innecesarios. Este sistema visual reproduce el funcionamiento interno de Git, pero de una forma más intuitiva, sin necesidad de memorizar órdenes.
También es posible crear commits directamente desde Visual Studio Code. El editor ofrece un espacio para escribir el mensaje descriptivo del commit, lo que fomenta la buena práctica de documentar cada cambio realizado en el proyecto. De este modo, el historial de versiones queda claro y ordenado, facilitando la comprensión de la evolución del proyecto.
La sincronización con GitHub también se puede realizar desde el propio editor. Visual Studio Code permite enviar los cambios al repositorio remoto y descargar las actualizaciones realizadas por otros usuarios. Esto resulta muy útil cuando se trabaja en equipo o desde distintos ordenadores, ya que todo el proceso se centraliza en una única herramienta.
Otra ventaja importante es que Visual Studio Code avisa de posibles problemas relacionados con el control de versiones. Por ejemplo, muestra alertas cuando existen cambios pendientes de guardar, cuando el repositorio no está sincronizado o cuando se intenta subir una versión que no incluye todos los archivos necesarios. Esto reduce errores y mejora la organización del trabajo.
El uso conjunto de Visual Studio Code y Git permite un flujo de trabajo más cómodo y eficiente. El usuario puede editar archivos, gestionar versiones y sincronizar el proyecto sin salir del entorno de desarrollo. Esto ahorra tiempo y reduce la complejidad, especialmente en proyectos educativos o de práctica.


16. Archivo .gitignore
El archivo .gitignore es un archivo especial que se utiliza para indicar a Git qué archivos o carpetas no deben formar parte del control de versiones. Su objetivo principal es evitar que ciertos elementos del proyecto se incluyan en el repositorio, aunque existan físicamente en el ordenador del usuario.
En muchos proyectos existen archivos que no es necesario compartir o que incluso pueden causar problemas si se suben al repositorio. Entre estos se encuentran configuraciones locales del sistema, archivos temporales generados automáticamente por programas, cachés o elementos que no forman parte real del código del proyecto. El archivo .gitignore permite excluir todos estos elementos de forma ordenada y controlada.
Aunque los archivos indicados en el archivo .gitignore estén presentes en el directorio de trabajo, Git los ignora por completo. Esto significa que no aparecen como archivos modificados, no se pueden preparar para un commit y no se suben al repositorio remoto. De esta manera, el repositorio se mantiene limpio y contiene únicamente los archivos realmente importantes del proyecto.
El uso del archivo .gitignore es especialmente importante cuando se trabaja en equipo. Cada usuario puede tener configuraciones distintas en su ordenador, pero gracias al .gitignore esas diferencias no afectan al repositorio común. Todos los colaboradores trabajan con la misma base de archivos, evitando conflictos innecesarios y manteniendo una estructura clara.
Este archivo se guarda normalmente en la raíz del repositorio, aunque también puede existir en subcarpetas si se desea aplicar reglas específicas a determinadas partes del proyecto. Una vez creado, Git tiene en cuenta sus indicaciones automáticamente sin necesidad de realizar configuraciones adicionales.
El archivo .gitignore forma parte del propio repositorio, por lo que se comparte con el resto del equipo. Esto garantiza que todos los usuarios ignoren los mismos archivos y carpetas, manteniendo un comportamiento coherente en el control de versiones.
En resumen, el archivo .gitignore es una herramienta fundamental para gestionar correctamente qué se incluye y qué no en un repositorio Git. Permite evitar archivos innecesarios, mejorar la organización del proyecto y asegurar que el repositorio remoto contenga únicamente información relevante y útil


17. Credenciales y seguridad
Cuando trabajamos con GitHub desde Visual Studio Code o desde Git en general, es normal que el sistema guarde nuestras credenciales para no tener que escribir el usuario y la contraseña cada vez. Esto hace el trabajo mucho más cómodo y rápido, sobre todo cuando estamos subiendo y bajando cambios constantemente.
El problema aparece cuando no estamos usando nuestro ordenador personal. En un ordenador de clase, de un amigo o compartido, las credenciales pueden quedarse guardadas sin que nos demos cuenta. Esto significa que otra persona podría acceder a nuestro GitHub, subir cambios, borrar repositorios o simplemente curiosear sin nuestro permiso.
Por eso es muy importante tener en cuenta la seguridad. Siempre que se trabaje en un equipo que no es propio, lo recomendable es eliminar las credenciales al terminar. De esta forma evitamos accesos no autorizados y posibles problemas más adelante.
GitHub contiene proyectos, trabajos y a veces incluso prácticas evaluables, por lo que proteger la cuenta es fundamental. No es solo una cuestión de comodidad, sino también de responsabilidad.
En resumen, guardar credenciales facilita mucho el trabajo diario, pero hay que ser consciente de dónde se está trabajando. En ordenadores compartidos, borrar las credenciales al acabar es una buena práctica básica para mantener la seguridad de la cuenta y del trabajo realizado.
MARKDOWN
1.MARKDOWN: evolución, función y uso
En los primeros años de la informática y del desarrollo web, la documentación se hacía casi siempre con procesadores de texto como Word o similares. Esto funcionaba para trabajos pequeños, pero tenía muchos problemas: los archivos pesaban mucho, dependían de versiones del programa y no se integraban bien con herramientas de programación ni con sistemas de control de versiones como Git.
Además, cuando se trabajaba en equipo, era muy complicado mantener una documentación ordenada. Los archivos se duplicaban, se perdían cambios y no quedaba claro quién había modificado qué parte del documento. Esto chocaba directamente con la filosofía del desarrollo moderno, donde todo debe poder versionarse y controlarse.
Para solucionar este problema apareció Markdown. Markdown es un lenguaje de marcado ligero pensado para escribir documentación de forma sencilla, clara y compatible con cualquier sistema. Su idea principal es que el texto sea perfectamente legible incluso sin aplicar ningún formato visual.
Markdown permite centrarse en el contenido, igual que CSS permitió separar el diseño del contenido en HTML. No hace falta usar menús ni botones, solo escribir texto con pequeños símbolos que indican la estructura del documento.
Con el tiempo, Markdown se convirtió en el estándar de facto para documentación técnica, sobre todo en plataformas como GitHub, donde todos los repositorios utilizan Markdown para sus archivos README.

2.Markdown y su relación con Git y GitHub
Markdown encaja perfectamente con Git porque ambos trabajan con texto plano. Esto significa que los archivos Markdown se pueden versionar sin problemas, comparar cambios línea a línea y recuperar versiones antiguas fácilmente.
Cuando se sube un archivo Markdown a GitHub, la plataforma lo interpreta automáticamente y lo muestra de forma estructurada y visual. Esto hace que un simple archivo de texto se convierta en una documentación clara, ordenada y profesional sin esfuerzo adicional.
Por esta razón, Markdown no es opcional en GitHub. Es la forma natural de explicar proyectos, prácticas y trabajos técnicos.

3.Ventajas e inconvenientes de Markdown
Las ventajas de usar Markdown son muchas:
Permite escribir documentación rápida sin distracciones.
 Es muy fácil de aprender, incluso para personas que no saben programar.
 Funciona perfectamente con Git y control de versiones.
 Los archivos ocupan muy poco espacio.
 Se pueden convertir fácilmente a HTML, PDF u otros formatos.
 Es el formato estándar en GitHub y en proyectos profesionales.
El principal inconveniente es que Markdown es limitado en comparación con HTML. No está pensado para diseños complejos ni para controlar estilos avanzados. Aun así, para documentación técnica, esta simplicidad es precisamente su mayor ventaja.

4.Jerarquía del documento en Markdown
Markdown no funciona con tamaños de letra como Word. Funciona con jerarquía. Esto significa que cada parte del documento tiene un nivel de importancia.
El encabezado principal se utiliza como título del documento. Solo debería haber uno, ya que representa el tema general del archivo.
Los encabezados de segundo nivel se usan para dividir el documento en grandes bloques, como apartados principales.
Los encabezados de tercer nivel se utilizan para subdividir esos apartados y explicar conceptos más concretos.
Este sistema permite que el documento tenga una estructura clara y lógica. GitHub incluso puede generar índices automáticos basándose en esta jerarquía.

5.Formato de texto en Markdown
Markdown permite dar énfasis al texto sin perder la simplicidad del documento.
La cursiva se usa para resaltar palabras clave o ideas secundarias.
 La negrita se utiliza para conceptos importantes o definiciones.
 El texto tachado sirve para indicar contenido obsoleto o descartado.
Este tipo de formato ayuda mucho a que los apuntes sean más fáciles de leer, sobre todo cuando el documento es largo.

6.Listas en Markdown
Las listas son fundamentales en documentación técnica.
Las listas ordenadas se utilizan cuando es importante seguir un orden, como en pasos o procesos. Markdown se encarga de numerarlas correctamente aunque el autor no lo haga de forma manual.
Las listas desordenadas se usan cuando solo se quiere enumerar elementos sin un orden específico, como características o ventajas.
Las sublistas permiten desarrollar ideas dentro de un mismo punto, evitando textos largos y confusos.
Este sistema hace que la información sea mucho más clara y visual.

7.Tablas en Markdown
Las tablas permiten organizar información compleja de forma clara.
En Markdown, las tablas se crean usando separadores simples. Aunque al escribirlas parecen básicas, al renderizarse en GitHub se ven limpias y ordenadas.
Las tablas son muy útiles para comparar conceptos, resumir información o mostrar datos técnicos de forma compacta.

8.Código en Markdown
Markdown permite mostrar código de manera clara y diferenciada del texto normal.
El código en línea se utiliza cuando se menciona un comando, un archivo o una palabra técnica dentro de una frase.
Los bloques de código se utilizan para mostrar fragmentos completos, comandos o ejemplos largos.
Además, se puede indicar el lenguaje del código para que GitHub lo muestre con colores, lo que facilita mucho la lectura y comprensión.

9.Markdown como herramienta profesional
Markdown no es solo un formato para estudiantes. Es una herramienta profesional utilizada en empresas, proyectos open source y documentación técnica real.
Su simplicidad, junto con su integración perfecta con Git y GitHub, lo convierten en una pieza clave del flujo de trabajo moderno.
Aprender Markdown no es aprender a dar formato a texto, es aprender a documentar correctamente proyectos informáticos de forma clara, ordenada y mantenible.
HTML
HTML: lenguaje base para crear páginas web
HTML es el lenguaje estándar que se utiliza para crear páginas web y es el encargado de mostrar el contenido en el navegador. Cuando accedemos a cualquier página web, el navegador lo primero que hace es leer el código HTML para saber qué tiene que mostrar y cómo está organizado. Todo lo que vemos en una web, como textos, imágenes, enlaces, listas, tablas o formularios, está definido de alguna manera con HTML, aunque luego su apariencia o comportamiento se controle con otros lenguajes.
Por este motivo, HTML es normalmente el primer lenguaje que se aprende en desarrollo web, ya que actúa como la base de todo el resto. Sin HTML no existiría una estructura sobre la que trabajar, por lo que ni CSS ni JavaScript tendrían sentido. Se puede decir que HTML es el esqueleto de la página web, sobre el cual se construye todo lo demás.
HTML define la estructura y el contenido de una página mediante etiquetas como <p>, <h1>, <body>, <html>, entre muchas otras. Estas etiquetas indican al navegador qué tipo de contenido es cada parte del documento y cómo debe interpretarlo. Por ejemplo, no es lo mismo un encabezado que un párrafo, aunque ambos contengan texto, y es HTML quien se encarga de marcar esa diferencia.
Aunque se le llame lenguaje, HTML no es un lenguaje de programación. No permite realizar cálculos, crear bucles, condiciones o funciones como otros lenguajes más avanzados. Su función no es tomar decisiones ni ejecutar lógica, sino describir contenido de forma estructurada para que el navegador pueda mostrarlo correctamente. Por este motivo se dice que HTML es un lenguaje de marcado y no de programación.
El estilo visual de la página, como colores, tamaños, márgenes o tipografías, se consigue con CSS, mientras que el comportamiento y la interacción con el usuario se controla con JavaScript. Aun así, sin HTML no existiría la página como tal, ya que es el lenguaje que define qué elementos existen y cómo se organizan dentro del documento.
Las siglas HTML significan:
HyperText, que hace referencia a textos que pueden enlazar con otros documentos o recursos. Gracias al hipertexto, es posible navegar entre diferentes páginas web mediante enlaces.
Markup, porque el contenido se organiza y se marca mediante etiquetas, indicando al navegador la función de cada elemento dentro de la página.
Language, porque HTML tiene unas reglas, una sintaxis y una estructura bien definidas que deben respetarse para que el navegador pueda interpretar correctamente el documento.

Elementos y etiquetas HTML
Un elemento HTML suele estar formado por tres partes principales que trabajan juntas para definir el contenido de una página web. En primer lugar está la etiqueta de apertura, que indica al navegador dónde empieza el elemento y qué tipo de contenido va a encontrar. A continuación se encuentra el contenido, que es la información visible que se mostrará en la página, como texto, imágenes u otros elementos. Por último, está la etiqueta de cierre, que sirve para indicar dónde termina ese elemento concreto.
Por ejemplo, un párrafo está compuesto por una etiqueta de apertura, un texto en su interior y una etiqueta de cierre. Gracias a este sistema, el navegador puede interpretar correctamente el documento y saber dónde empieza y acaba cada parte del contenido. Si las etiquetas no están bien cerradas o colocadas, la estructura de la página puede romperse o mostrarse de forma incorrecta.
Las etiquetas HTML pueden tener atributos, que añaden información extra al elemento y permiten darle más significado o funcionalidad. Algunos atributos muy comunes son class, id, src o alt. Estos atributos sirven, por ejemplo, para identificar elementos, aplicar estilos con CSS, añadir rutas a imágenes o mejorar la accesibilidad de la página. Los atributos siempre se escriben dentro de la etiqueta de apertura y siguen una estructura concreta, donde primero se indica el nombre del atributo y después su valor entre comillas.
HTML permite anidar elementos, es decir, colocar unas etiquetas dentro de otras. Esto es algo básico y muy importante para organizar correctamente el contenido de una página. Por ejemplo, un texto puede estar en negrita dentro de un párrafo, o un enlace puede estar dentro de una lista. La anidación debe hacerse siempre de forma correcta, cerrando primero la última etiqueta que se haya abierto, para mantener una estructura clara y lógica.
Además de los elementos normales, existen elementos que no tienen contenido ni etiqueta de cierre. Estos se conocen como elementos vacíos o elementos auto cerrados. Su función es realizar una acción concreta dentro del documento, como insertar una imagen o provocar un salto de línea. Algunos ejemplos muy comunes de este tipo de elementos son las imágenes o los saltos de línea, ya que no contienen texto en su interior, sino que simplemente cumplen una función específica dentro de la página.
Este sistema de elementos, etiquetas, atributos y anidación es la base de HTML y permite crear documentos web bien estructurados, legibles y fáciles de mantener, tanto para el navegador como para el desarrollador.


Estructura básica de un documento HTML
Toda página HTML sigue una estructura básica fija que siempre se repite, independientemente de si la web es muy simple o muy compleja. Esta estructura no es opcional, ya que es la forma que tiene el navegador de entender correctamente el documento y saber cómo debe interpretarlo. Si esta estructura no se respeta, la página puede funcionar mal o mostrarse de forma incorrecta.
Al principio del archivo HTML se encuentra la declaración DOCTYPE. Actualmente no se utiliza para dar estilo ni para añadir contenido a la página, pero sigue siendo un requisito técnico obligatorio. Su función principal es indicarle al navegador que el documento está escrito en HTML moderno y que debe interpretarlo siguiendo los estándares actuales. Gracias al DOCTYPE se evita que el navegador entre en modos antiguos de compatibilidad que pueden provocar errores de visualización.
Después de la declaración DOCTYPE aparece la etiqueta html, que engloba absolutamente todo el contenido de la página. Esta etiqueta se conoce como el elemento raíz, ya que todos los demás elementos del documento están contenidos dentro de ella. Es la base sobre la que se construye toda la estructura del documento HTML.
Dentro de la etiqueta html se encuentran dos partes fundamentales que dividen claramente el documento: head y body. Cada una tiene una función muy concreta y diferente.
El head contiene información que no se muestra directamente en la página web, pero que es esencial para su funcionamiento. En esta parte se incluyen los metadatos, que son datos sobre el propio documento. Aquí se define, por ejemplo, el tipo de codificación de caracteres que utiliza la página, lo cual es muy importante para que los textos se muestren correctamente. También se pueden añadir descripciones y palabras clave que ayudan a los buscadores a entender de qué trata la web, algo muy relacionado con el SEO.
Además, en el head se define el título de la página, que es el texto que aparece en la pestaña del navegador y en los resultados de búsqueda. También se pueden incluir enlaces a recursos externos, como hojas de estilo CSS, archivos JavaScript o el favicon, que es el pequeño icono que aparece junto al título en la pestaña del navegador. En algunos casos, también se pueden escribir estilos CSS directamente dentro del head, aunque lo más habitual es usar archivos externos.
El body contiene todo el contenido visible de la página web, es decir, todo aquello que el usuario ve y con lo que puede interactuar. Aquí se colocan los textos, encabezados, párrafos, imágenes, listas, enlaces, tablas, formularios y cualquier otro elemento que forme parte de la interfaz de la página. Todo lo que aparece en pantalla debe estar dentro del body para que el navegador lo muestre correctamente.
En resumen, la estructura básica de un documento HTML sirve para organizar la página de forma clara y ordenada, separando la información técnica y de configuración del contenido visible. Esta estructura es la base de cualquier página web y es lo primero que se debe entender y respetar al empezar a trabajar con HTML.

Tipos de elementos HTML
En HTML existen principalmente dos tipos de elementos, y entender esta diferencia es fundamental para poder estructurar bien una página web: los elementos de bloque y los elementos de línea. Aunque al principio puedan parecer parecidos, su comportamiento dentro de la página es muy diferente y afecta directamente a cómo se muestra el contenido en el navegador.
Los elementos de bloque ocupan todo el ancho disponible de la pantalla, independientemente de la cantidad de contenido que tengan dentro. Esto significa que, aunque el texto sea corto, el elemento se extiende de un lado a otro del contenedor. Además, estos elementos generan automáticamente un salto de línea antes y después de ellos, separándose visualmente del resto del contenido. Por este motivo, los elementos de bloque se utilizan para estructurar la página en grandes secciones o bloques de contenido.
Este tipo de elementos es ideal para organizar la información de la web de forma clara. Encabezados, párrafos, divisores o contenedores son ejemplos típicos de elementos de bloque. Gracias a ellos se pueden crear secciones, agrupar información relacionada y dar una estructura lógica al documento HTML. Normalmente, los elementos de bloque se utilizan como base para después aplicar estilos con CSS y definir el diseño de la página.
Por otro lado, los elementos de línea se comportan de una forma muy distinta. Estos elementos no ocupan todo el ancho disponible, sino únicamente el espacio necesario para mostrar su contenido. Además, no generan saltos de línea, por lo que se muestran dentro de la misma línea de texto junto a otros elementos. Su función principal no es estructurar la página, sino dar formato o significado a pequeñas partes del contenido.
Los elementos de línea se utilizan, por ejemplo, para resaltar palabras, dar énfasis a una parte del texto, crear enlaces o agrupar fragmentos pequeños de contenido sin romper el flujo del texto. Son muy útiles cuando se quiere modificar solo una parte concreta de una frase sin afectar al resto del contenido que la rodea.
Entender bien la diferencia entre elementos de bloque y elementos de línea es básico para trabajar correctamente con HTML. Saber cuándo usar cada tipo evita muchos errores de estructura y facilita tanto el diseño con CSS como el mantenimiento del código. Una buena combinación de ambos tipos permite crear páginas web claras, ordenadas y fáciles de entender tanto para el navegador como para el desarrollador.


Normas básicas al escribir HTML
Al escribir código HTML es muy importante seguir una serie de normas básicas. Aunque el navegador suele ser bastante “permisivo” y a veces muestra la página aunque el código no sea perfecto, no respetar estas normas puede provocar errores, comportamientos extraños o problemas más adelante cuando el proyecto crece.
La primera norma es que la mayoría de las etiquetas se escriben en pares, es decir, tienen una etiqueta de apertura y una etiqueta de cierre. La etiqueta de apertura indica dónde empieza el contenido y la etiqueta de cierre indica dónde termina. Esto permite al navegador saber exactamente qué parte del texto o contenido pertenece a cada elemento. Si una etiqueta no se cierra correctamente, el navegador puede interpretar mal el resto del documento.
Existen, sin embargo, algunas etiquetas que son vacías, lo que significa que no tienen contenido dentro y no necesitan etiqueta de cierre. Estas etiquetas cumplen una función concreta, como insertar una imagen o provocar un salto de línea. Aunque no tengan cierre, siguen siendo elementos HTML válidos y deben escribirse correctamente para que funcionen como se espera.
Otra norma fundamental es que las etiquetas deben anidarse correctamente. Esto significa que, si una etiqueta se abre dentro de otra, debe cerrarse antes de cerrar la etiqueta exterior. El orden de apertura y cierre debe respetarse siempre. Una mala anidación puede hacer que el contenido no se muestre como debería o que se rompa la estructura del documento.
Los atributos son otra parte clave del HTML y también tienen sus propias normas. Los atributos siempre se escriben en la etiqueta de apertura y sirven para añadir información extra al elemento. Siguen una estructura muy clara: primero el nombre del atributo, luego el signo igual y después el valor entre comillas. Respetar este formato es imprescindible para que el navegador pueda interpretar correctamente el atributo.
Cumplir todas estas normas básicas no solo evita errores visibles en la página, sino que también hace que el código sea más claro, más fácil de leer y más sencillo de mantener. Un HTML bien escrito ayuda al navegador a interpretar correctamente la página y facilita el trabajo cuando se combina con CSS, JavaScript o cuando el proyecto crece y se vuelve más complejo.


Legibilidad y organización del código
La legibilidad y la organización del código HTML son aspectos fundamentales a la hora de crear una página web. Aunque el navegador pueda interpretar un código desordenado, trabajar de esa manera no es nada recomendable. Un HTML claro y bien estructurado hace que el documento sea más fácil de entender, tanto para otras personas que puedan trabajar en el proyecto como para ti mismo cuando vuelvas a revisarlo pasado un tiempo.
Es muy habitual que, semanas o meses después, tengas que modificar una página web. Si el código está mal organizado, sin orden ni estructura, resulta muy complicado localizar errores o entender qué hace cada parte. En cambio, un código limpio y bien escrito permite identificar rápidamente cada sección del documento y facilita mucho el mantenimiento.
Para mejorar la legibilidad del HTML se utilizan varias técnicas básicas. Una de las más importantes es la sangría o indentación. Consiste en desplazar hacia la derecha las líneas de código que están dentro de otras etiquetas. Esto ayuda a ver claramente qué elementos están dentro de otros y a identificar la jerarquía del documento. Una buena indentación no cambia el resultado visual de la web, pero sí mejora enormemente la comprensión del código.
Otro aspecto clave es la organización de carpetas y archivos. Separar correctamente los archivos HTML, CSS, imágenes y otros recursos hace que el proyecto sea más ordenado y profesional. Aunque esta organización no afecta directamente al funcionamiento de la página, sí influye mucho en la calidad del trabajo y en la facilidad para ampliarlo o modificarlo en el futuro.
Los comentarios son otra herramienta muy útil para mejorar la legibilidad. Los comentarios permiten añadir anotaciones dentro del documento HTML que no se muestran en el navegador. Se utilizan para explicar qué hace una parte concreta del código, indicar secciones importantes o dejar recordatorios para futuras modificaciones. Esto es especialmente útil cuando el documento es largo o cuando varias personas trabajan sobre el mismo proyecto.
En resumen, escribir HTML de forma clara, ordenada y bien comentada no solo demuestra buenas prácticas, sino que también ahorra tiempo, evita errores y hace que el desarrollo web sea mucho más cómodo. Un código bien organizado es tan importante como que la página funcione correctamente.


Etiquetas básicas de HTML
Las etiquetas básicas de HTML son las más utilizadas y las primeras que se aprenden cuando se empieza a crear páginas web. Son las que permiten construir el contenido principal de una página, organizar la información y darle sentido a cada parte del documento. Sin estas etiquetas, una web sería solo texto plano sin estructura ni orden.
Los encabezados se utilizan para indicar títulos y subtítulos dentro del contenido. Existen varios niveles de encabezados, que van desde el más importante hasta el menos importante. El encabezado principal suele usarse para el título general de la página y normalmente solo debería haber uno. Los encabezados de niveles inferiores se usan para dividir el contenido en secciones y subsecciones, creando una jerarquía clara.
Por ejemplo, un título principal podría escribirse como:
<h1>Introducción a HTML</h1>
Y un subtítulo dentro de esa sección podría ser algo como:
<h2>Estructura básica de una página</h2>
Usar correctamente los encabezados no solo hace que la página sea más fácil de leer, sino que también mejora la accesibilidad y el posicionamiento en buscadores, ya que los motores de búsqueda utilizan estos elementos para entender la estructura del contenido.
Los párrafos se utilizan para agrupar textos que están relacionados entre sí. Un párrafo representa una idea completa o un conjunto de frases que hablan de un mismo tema. Cada vez que se crea un párrafo, el navegador lo separa visualmente del anterior, lo que hace que la lectura sea mucho más cómoda.
Un ejemplo sencillo de párrafo sería:
<p>HTML es el lenguaje base para crear páginas web y definir su contenido.</p>
Es una de las etiquetas más usadas en cualquier documento HTML, ya que prácticamente todo el texto visible suele ir dentro de párrafos.
El salto de línea permite forzar un cambio de línea dentro del texto sin crear un nuevo párrafo. Esto es útil cuando se quiere mantener el texto relacionado pero separar visualmente algunas líneas, como en direcciones, poemas o listados simples.
Por ejemplo, para escribir una dirección en varias líneas se podría usar algo como:
<p>Calle Mayor<br>Barcelona<br>España</p>
En este caso, el contenido sigue siendo un solo párrafo, pero con saltos de línea internos.
El separador de línea se utiliza para dividir visualmente distintas secciones del contenido. Añade una línea horizontal que ayuda al usuario a identificar claramente un cambio de tema o de bloque de información. Es muy útil en páginas largas o en documentos donde se quiere marcar una separación clara entre apartados.
Un ejemplo sería simplemente colocar:
<hr>
Esto hará que el navegador muestre una línea horizontal que separa el contenido de arriba con el de abajo.
Las etiquetas de énfasis sirven para destacar partes del texto y darles mayor importancia. No solo cambian el aspecto visual, sino que también aportan significado semántico, indicando que ese contenido es relevante. Esto es importante tanto para los buscadores como para las herramientas de accesibilidad.
Por ejemplo, para destacar una palabra importante dentro de un texto se podría escribir:
<p>HTML es un <strong>lenguaje fundamental</strong> en desarrollo web.</p>
O para dar un énfasis más suave:
<p>Es <em>muy importante</em> entender bien la estructura.</p>
El elemento span es un contenedor en línea que se utiliza para agrupar pequeñas partes de texto dentro de un bloque mayor. No crea una nueva línea ni rompe el flujo del texto, por lo que es ideal para aplicar estilos o marcar fragmentos concretos sin afectar al resto del contenido.
Por ejemplo:
<p>HTML es un lenguaje <span>muy utilizado</span> en la web.</p>
El elemento span se usa mucho junto con CSS para cambiar colores, tamaños o estilos solo de una palabra o parte concreta del texto.
En conjunto, todas estas etiquetas forman la base del contenido de cualquier página web. Saber utilizarlas correctamente permite crear documentos claros, bien estructurados y fáciles de leer, tanto para los usuarios que visitan la web como para los desarrolladores que trabajan en el código.



Listas en HTML
Las listas en HTML se utilizan para organizar información de forma clara y ordenada. Son muy habituales en páginas web porque permiten mostrar datos de manera estructurada y fácil de leer. Existen principalmente dos tipos de listas: las desordenadas y las ordenadas, y cada una se usa según el tipo de información que se quiera mostrar.
Las listas desordenadas se utilizan cuando el orden de los elementos no es importante. Se suelen usar para enumerar características, materiales, apartados o elementos que no siguen una secuencia concreta. Visualmente, el navegador muestra los elementos con símbolos como puntos, círculos o cuadrados.
 Por ejemplo, una lista desordenada podría escribirse así:
<ul> <li>HTML</li> <li>CSS</li> <li>JavaScript</li> </ul>
En este caso, el orden de los elementos no altera el significado de la lista, simplemente se están enumerando conceptos relacionados.
Las listas ordenadas se usan cuando el orden sí es relevante. Son muy comunes en instrucciones, recetas, pasos a seguir o procesos donde es importante respetar una secuencia. Por defecto, el navegador numera los elementos de forma automática, pero HTML permite personalizar este comportamiento.
 Un ejemplo de lista ordenada sería:
<ol> <li>Encender el ordenador</li> <li>Abrir el navegador</li> <li>Cargar la página web</li> </ol>
Además, HTML permite cambiar el tipo de numeración, por ejemplo usando letras en mayúscula, minúscula o números romanos. También se puede forzar que la lista empiece por un número concreto usando un valor inicial. Esto es útil cuando una lista continúa otra anterior o cuando se quiere un formato específico.
Cada elemento de una lista, tanto ordenada como desordenada, se define mediante un elemento de lista, que representa un ítem individual. Este elemento siempre va dentro de la lista principal y sirve para indicar cada punto de la enumeración. Sin estos elementos, la lista no tendría contenido.
Las listas también pueden anidarse, es decir, se puede colocar una lista dentro de otra para crear subapartados. Esto es muy útil cuando se quiere desglosar información más detallada dentro de un punto concreto.
En resumen, las listas en HTML son una herramienta básica pero muy potente para organizar información. Usarlas correctamente mejora la claridad del contenido y hace que la página sea más fácil de entender para el usuario.


Rutas absolutas y rutas relativas
Las rutas se utilizan en HTML para indicar dónde se encuentran los recursos que usamos en una página web, como imágenes, hojas de estilo o enlaces a otros documentos. Saber usar correctamente las rutas es fundamental para que la web funcione bien y para mantener una buena organización del proyecto.
Las rutas absolutas indican la ubicación completa de un recurso en la web, empezando siempre desde el dominio. Este tipo de rutas se usan principalmente cuando el archivo que queremos mostrar o enlazar no está dentro de nuestro propio proyecto, sino en un servidor externo. Al usar una ruta absoluta, el navegador sabe exactamente dónde buscar el recurso, independientemente de dónde esté el archivo HTML.
Por ejemplo, si queremos mostrar una imagen que está alojada en otra página web, usaríamos una ruta absoluta como esta:
 <img src="https://www.example.com/images/logo.png" alt="Logo externo">
Este tipo de ruta es muy útil cuando dependemos de recursos externos, pero también tiene el inconveniente de que, si ese recurso deja de existir o cambia de ubicación, la imagen o el enlace dejarán de funcionar.
Las rutas relativas indican la ubicación de un archivo en relación con el documento HTML que se está utilizando en ese momento. Son las más comunes en proyectos web, ya que permiten organizar los archivos en carpetas y subcarpetas de forma clara. Además, facilitan mucho el mantenimiento del proyecto, porque si se mueve todo el sitio web a otro servidor, las rutas siguen funcionando.
Por ejemplo, si tenemos un archivo index.html y una carpeta llamada images donde está guardada una imagen, la ruta relativa sería algo así:
 <img src="images/logo.png" alt="Logo del sitio">
En este caso, se indica que la imagen está dentro de una carpeta llamada images que se encuentra en el mismo directorio que el archivo HTML. También se pueden usar rutas relativas para enlazar a otras páginas del mismo sitio, como secciones internas o documentos adicionales.
Las rutas relativas hacen que el proyecto sea más flexible y fácil de mantener. Por eso, siempre que sea posible, se recomienda utilizarlas en lugar de rutas absolutas cuando se trabaja con archivos propios del sitio web.
En resumen, las rutas absolutas se usan para recursos externos y las rutas relativas para recursos internos del proyecto. Entender bien la diferencia entre ambas es clave para crear páginas web bien organizadas y sin errores de carga.


Imágenes en HTML
Las imágenes son un elemento fundamental en cualquier página web, ya que ayudan a transmitir información de forma visual y hacen que el contenido sea mucho más atractivo para el usuario. En HTML, las imágenes se insertan mediante una etiqueta específica que es un elemento vacío, es decir, no tiene contenido interno ni etiqueta de cierre.
Para indicar dónde se encuentra la imagen se utiliza un atributo que señala la ubicación del archivo. Esta ubicación puede ser una ruta local, cuando la imagen está dentro del propio proyecto, o una URL externa, cuando la imagen se carga desde otro servidor.
 Por ejemplo, para una imagen guardada en una carpeta del proyecto, se podría escribir algo así:
 <img src="media/logo.png" alt="Logo de la web">
Si la imagen está alojada en un servidor externo, se usaría una dirección completa:
 <img src="https://www.example.com/images/banner.jpg" alt="Banner externo">
El atributo alternativo es uno de los más importantes cuando se trabaja con imágenes. Este atributo permite mostrar un texto descriptivo en el caso de que la imagen no se pueda cargar, ya sea por un error en la ruta o por problemas de conexión. De esta forma, el usuario sigue teniendo información sobre lo que debería aparecer en la página.
Además, el texto alternativo es clave para la accesibilidad, ya que los lectores de pantalla lo utilizan para describir la imagen a personas con discapacidad visual. También influye en el posicionamiento en buscadores, ya que los motores de búsqueda no “ven” las imágenes, sino que interpretan el contenido a través de este texto.
Usar imágenes correctamente implica no solo mostrarlas, sino también describirlas de forma clara mediante el atributo alternativo. Esto mejora la experiencia del usuario y hace que la página web sea más profesional y completa.
En resumen, las imágenes en HTML se insertan con una etiqueta simple, pero su uso correcto requiere cuidar la ruta del archivo y escribir siempre un buen texto alternativo que explique el contenido visual que se está mostrando.

Enlaces e hipertexto
Los enlaces son uno de los elementos más importantes de HTML y, de hecho, son la base de la World Wide Web. Gracias a los enlaces es posible pasar de una página a otra con un solo clic, creando esa sensación de navegación continua entre documentos que caracteriza a internet. Sin enlaces, las páginas web estarían aisladas unas de otras y la web no tendría sentido tal y como la conocemos.
En HTML, los enlaces se crean mediante una etiqueta específica que permite asociar un texto o un elemento visual a una dirección de destino. Ese destino puede ser una página web externa, un archivo dentro del mismo proyecto o incluso una sección concreta de la propia página. El texto del enlace es lo que el usuario ve y sobre lo que hace clic, y es importante que sea claro y descriptivo.
Un ejemplo de enlace a una página externa podría ser algo como:
 <a href="https://www.google.com">Ir a Google</a>
En este caso, al hacer clic sobre el texto “Ir a Google”, el navegador llevará al usuario a esa web. Este tipo de enlaces se usan constantemente para referenciar recursos externos, documentación, redes sociales u otras páginas relacionadas.
Los enlaces también pueden dirigir a archivos locales dentro del mismo proyecto web. Esto es muy habitual en páginas con varias secciones, como una web con una página principal y varias subpáginas. Por ejemplo, un enlace a otra página del mismo sitio podría verse así:
 <a href="contacto.html">Página de contacto</a>
Aquí el navegador busca el archivo indicado dentro del proyecto y lo carga sin necesidad de salir del sitio web.
Además, HTML permite crear enlaces que llevan a partes concretas de una misma página mediante el uso de anclas. Esto es especialmente útil en documentos largos, donde el usuario puede saltar directamente a la sección que le interesa sin tener que hacer scroll manualmente.
Para crear una ancla, primero se asigna un identificador único a un elemento de la página. Por ejemplo, a un encabezado:
<h2 id="seccion-html">HTML básico</h2>
Después, se crea un enlace que apunte a ese identificador:
 <a href="#seccion-html">Ir a la sección de HTML</a>
Cuando el usuario hace clic en ese enlace, el navegador se desplaza automáticamente hasta la parte de la página que tiene ese identificador. Este sistema mejora mucho la experiencia de usuario y hace más cómoda la navegación en textos largos o apuntes extensos.
Los enlaces no solo pueden contener texto, también pueden envolver imágenes u otros elementos. Por ejemplo, una imagen que al hacer clic lleve a otra página es algo muy común en banners o logotipos.
En resumen, los enlaces son el corazón del hipertexto y uno de los pilares fundamentales de HTML. Permiten conectar información, organizar contenidos y facilitar la navegación tanto dentro de una misma web como hacia recursos externos. Saber usarlos bien es clave para crear páginas web útiles, accesibles y bien estructuradas.


Contenedores y división del contenido
En HTML, los contenedores son fundamentales para organizar correctamente el contenido de una página web. El más utilizado de todos es el contenedor div, que sirve para agrupar distintos elementos y darles una estructura lógica dentro del documento. Por sí mismo, el div no tiene ningún significado visual ni semántico, es decir, no cambia cómo se ve la página, pero es una pieza clave a nivel de organización interna.
El div actúa como una “caja” invisible que permite meter dentro otros elementos como textos, imágenes, listas, enlaces o incluso otros div. Gracias a esto, el desarrollador puede dividir la página en partes claras y manejables, lo que facilita tanto el diseño como el mantenimiento del código.
Un ejemplo sencillo de un contenedor div podría ser algo como:
<div>Contenido de la página</div>
Aunque visualmente no haga nada especial, este contenedor permite aplicar estilos con CSS o comportamientos con JavaScript a todo lo que haya dentro.
Uno de los usos más habituales del div es dividir la web en secciones, como por ejemplo una cabecera, un área de contenido principal y un pie de página. Esto ayuda a estructurar la página de forma clara y coherente. Por ejemplo:
<div class="cabecera">Aquí iría el logo y el menú</div> <div class="contenido">Aquí va el contenido principal</div> <div class="pie">Aquí va la información del pie de página</div>
En este caso, aunque el navegador no interpreta automáticamente qué es cada parte, el uso de clases permite identificar cada sección y darle estilos distintos, como colores, tamaños o posiciones.
El div también es muy importante cuando se trabaja con CSS, ya que permite aplicar estilos a grupos completos de elementos sin tener que hacerlo uno por uno. Por ejemplo, se puede usar un div para centrar todo el contenido de la página, crear columnas, separar bloques o controlar el diseño general del sitio.
Además, el div es clave cuando se trabaja con JavaScript, ya que sirve como punto de referencia para manipular partes concretas del documento. A través de identificadores o clases, se puede acceder a un div concreto y cambiar su contenido, ocultarlo, mostrarlo o modificar su estilo de forma dinámica.
Es importante no abusar del uso de div sin sentido. Aunque es muy flexible, un exceso de contenedores puede hacer que el código sea difícil de leer y mantener. Por eso, se recomienda usar div cuando realmente sea necesario para agrupar contenido o estructurar la página.

Formularios web
Los formularios web son uno de los elementos más importantes en cualquier página interactiva, ya que permiten que el usuario envíe información a una web. Gracias a los formularios, una página deja de ser solo algo que se mira y pasa a ser algo con lo que se interactúa. Ejemplos claros de formularios son los inicios de sesión, los registros, los formularios de contacto, encuestas o buscadores.
Toda la información que introduce el usuario en un formulario puede ser enviada a un servidor para ser procesada o utilizada por la propia aplicación web. Sin formularios, no existirían cosas tan básicas hoy en día como crear una cuenta, enviar un mensaje o realizar una compra online.
Un formulario se crea usando una etiqueta específica que actúa como contenedor de todos los campos. Dentro de este contenedor se colocan los distintos campos de entrada, que son los elementos donde el usuario escribe o selecciona información. Por ejemplo, un formulario puede contener campos de texto para el nombre, un campo de contraseña, un botón para enviar los datos, casillas de verificación o listas desplegables.
Un ejemplo sencillo de estructura de formulario sería algo como:
<form> campos del formulario </form>
Dentro de ese formulario se pueden añadir distintos tipos de campos, como por ejemplo:
 <input type="text" name="usuario">
 <input type="password" name="clave">
Cada campo debe tener un nombre, ya que ese nombre es el que se utiliza para identificar el dato que el usuario está enviando. Si un campo no tiene nombre, su información no se envía correctamente, lo cual es un error muy común cuando se empieza a trabajar con formularios.
El formulario también define a dónde se envían los datos y cómo se envían. Esto se hace mediante atributos que indican el destino de la información y el método de envío. El método puede ser, por ejemplo, uno que envía los datos de forma visible en la URL o uno que los envía de forma más segura. Elegir el método correcto es muy importante, sobre todo cuando se trabaja con contraseñas o datos personales.
Además, el formulario define cómo se codifica la información, algo especialmente importante cuando se incluyen archivos, como imágenes o documentos. En esos casos, el formulario necesita una configuración especial para que los datos se envíen correctamente y no se pierdan.
Los campos de entrada pueden configurarse para controlar cómo interactúa el usuario con ellos. Por ejemplo, se puede indicar que un campo sea obligatorio, de forma que el formulario no se pueda enviar si no se rellena. Esto es muy útil para asegurarse de que el usuario introduce información básica como un correo o una contraseña.
También existen campos que pueden ser de solo lectura, lo que significa que el usuario puede ver el contenido pero no modificarlo. Esto se usa cuando se quiere mostrar información fija dentro de un formulario. Por otro lado, un campo puede estar desactivado, lo que hace que no se pueda interactuar con él y que su valor no se envíe junto al resto de datos.
Los formularios también suelen incluir botones para enviar o resetear la información. El botón de envío es el que manda todos los datos al destino configurado, mientras que el botón de reinicio permite borrar todo lo que el usuario ha escrito y dejar el formulario como al principio.



Tablas en HTML
Las tablas en HTML se utilizan para representar datos estructurados en filas y columnas, de una forma clara y ordenada. Son muy comunes cuando se quiere mostrar información comparativa, listados, horarios, precios, usuarios, notas o cualquier tipo de datos que tengan relación entre sí. Aunque hoy en día no se usan para maquetar páginas (eso se hace con CSS), siguen siendo fundamentales para mostrar datos.
Una tabla se construye a partir de un contenedor principal que engloba toda la información. Dentro de ese contenedor se organizan las filas y, dentro de cada fila, las celdas. Esta estructura permite que el navegador entienda perfectamente cómo debe distribuir los datos en pantalla.
Una tabla puede dividirse en tres partes principales, lo que mejora mucho la organización y la legibilidad:
El encabezado de la tabla, donde se suelen colocar los títulos de cada columna.


El cuerpo de la tabla, donde van los datos principales.


El pie de la tabla, que se puede usar para totales, notas o información adicional.


Un ejemplo muy básico de tabla sería algo así:
<table> <tr> <th>Nombre</th> <th>Edad</th> </tr> <tr> <td>Ana</td> <td>20</td> </tr> <tr> <td>Carlos</td> <td>22</td> </tr> </table>
En este ejemplo se puede ver claramente la estructura: primero se define una fila y dentro de ella se colocan las celdas. Las celdas del encabezado se usan para indicar qué significa cada columna, mientras que las celdas normales contienen los datos.
Las filas representan registros completos, por ejemplo una persona, un producto o una asignatura. Cada fila contiene varias celdas, y cada celda corresponde a una columna concreta. De esta forma, todos los datos quedan alineados y son fáciles de leer.
HTML también permite combinar columnas o filas, algo muy útil cuando un dato ocupa más espacio o cuando se quiere crear títulos que abarquen varias columnas. Por ejemplo, se puede hacer que una celda ocupe dos columnas en lugar de una:
<td colspan="2">Total</td>
También se pueden combinar filas para que una celda ocupe varias filas seguidas:
<td rowspan="2">Grupo A</td>
Además, las tablas pueden tener títulos descriptivos que explican qué información contienen. Esto es muy importante para la accesibilidad, ya que ayuda a los lectores de pantalla a entender el propósito de la tabla. Un ejemplo sería:
<caption>Listado de alumnos</caption>
El contenido de las celdas también se puede alinear de distintas formas, por ejemplo a la izquierda, al centro o a la derecha, dependiendo del tipo de información que se esté mostrando. Los números, por ejemplo, suelen alinearse a la derecha para que sean más fáciles de comparar.
Aunque visualmente una tabla puede parecer simple, por dentro tiene una estructura muy clara y estricta. Respetar esta estructura hace que la información sea más comprensible, más accesible y más fácil de mantener.
CSS
¿Qué es CSS?
CSS (Cascading Style Sheets, u Hojas de Estilo en Cascada) es un lenguaje que se utiliza para definir el diseño, la apariencia visual y la presentación de los documentos HTML o XHTML. Es decir, CSS se encarga de todo lo relacionado con cómo se ve una página web, mientras que HTML se encarga de qué contenido tiene y cómo está estructurado.
Mientras HTML define elementos como títulos, párrafos, imágenes, enlaces o formularios, CSS decide aspectos visuales como el color del texto, el tamaño de las letras, los espacios entre los elementos, la colocación de cada bloque en la pantalla o incluso cómo se adapta la web a distintos tamaños de pantalla. Ambos lenguajes trabajan juntos, pero cada uno tiene una función muy clara y diferenciada.
Por ejemplo, HTML puede definir un párrafo de texto, pero CSS es el que decide si ese párrafo se verá en color rojo, centrado, con letra grande o pequeña, con un fondo de color o separado del resto del contenido mediante espacios. Sin CSS, todas las páginas web tendrían un aspecto muy básico y similar entre sí.
Gracias a CSS podemos controlar muchos aspectos del diseño de una página web, como por ejemplo:
Los colores del texto y del fondo, permitiendo diferenciar secciones, resaltar información importante o mantener una estética coherente en toda la web. Por ejemplo, se puede hacer que todos los títulos sean de color azul y que el fondo de la página sea claro para facilitar la lectura.
La tipografía y los tamaños de letra, eligiendo el tipo de fuente, su tamaño, su grosor o su estilo. Esto permite que el texto sea más legible y que la web tenga una identidad visual concreta. Por ejemplo, se puede usar una letra grande para los títulos y una más pequeña para los párrafos.
Los espacios entre elementos, controlando la distancia entre textos, imágenes o bloques de contenido. Gracias a esto, la página no se ve saturada y resulta más cómoda de leer. Se pueden separar secciones, agrupar información relacionada o evitar que los elementos estén demasiado juntos.
Los bordes, márgenes y rellenos, que permiten crear cajas visuales alrededor del contenido. Con estos elementos se pueden destacar zonas concretas de la página, crear tarjetas, menús o contenedores visuales bien definidos.
La distribución de los elementos en la pantalla, organizando el contenido en columnas, filas o secciones. CSS permite decidir si los elementos se colocan uno debajo de otro, uno al lado del otro o si se adaptan automáticamente al tamaño de la pantalla.
La adaptación a distintos dispositivos, como ordenadores, tabletas o teléfonos móviles. Gracias a CSS, una misma página web puede verse correctamente en pantallas grandes y pequeñas, reorganizando el contenido para que siga siendo usable y legible en cualquier dispositivo.
Separar HTML y CSS permite que el código sea más limpio, más ordenado y más fácil de mantener. Si el diseño está separado del contenido, es posible cambiar completamente el aspecto de una web modificando solo el archivo CSS, sin tocar el HTML. Esto hace que el trabajo sea más profesional y facilita tanto el desarrollo como el mantenimiento de la página a largo plazo.


Ubicación de los estilos CSS
Los estilos CSS se pueden colocar en diferentes ubicaciones, y dependiendo de dónde se escriban, afectan de una forma u otra al documento HTML y tienen distinta prioridad. Esto es muy importante entenderlo bien, porque muchas veces un estilo no se aplica y el problema no es el CSS en sí, sino dónde está escrito.
Existen tres formas principales de aplicar estilos CSS a una página web: estilo inline, estilo interno y estilo externo. Cada una tiene sus ventajas, sus inconvenientes y su uso recomendado según el tipo de proyecto.
Estilo inline
El estilo inline es la forma más directa de aplicar CSS. Se escribe dentro de la propia etiqueta HTML, utilizando el atributo style. Es decir, el estilo se aplica directamente sobre el elemento concreto al que queremos dar formato.
Este tipo de estilo tiene varias características importantes. Solo afecta al elemento donde se escribe, no al resto del documento. Además, tiene mucha prioridad, ya que si ese mismo elemento tiene estilos definidos en otros sitios, el inline suele imponerse. Por otro lado, no es nada recomendable para proyectos grandes, porque ensucia mucho el HTML y hace que el código sea difícil de leer y mantener.
Por ejemplo, si queremos que un párrafo esté centrado y en color rojo usando estilo inline, lo escribiríamos directamente en la etiqueta del párrafo, indicando dentro de style propiedades como text-align centrado y color rojo. Ese párrafo se verá centrado y rojo, pero solo ese, no los demás.
Este método se suele usar únicamente para pruebas rápidas, para comprobar cómo quedaría algo visualmente o en casos muy concretos donde se necesita modificar un elemento puntual sin afectar a nada más. En proyectos reales y medianos no se suele usar casi nunca.
Estilo interno
El estilo interno se escribe dentro del propio documento HTML, pero no en cada etiqueta, sino en la cabecera del documento, usando la etiqueta style dentro del head. De esta forma, los estilos se aplican a todos los elementos que coincidan con las reglas definidas dentro de ese bloque.
Este tipo de estilo afecta a todos los elementos del documento HTML actual que cumplan las condiciones del selector. Permite separar mejor el contenido del diseño, ya que el HTML del body queda más limpio. Es bastante útil para páginas pequeñas, prácticas o ejercicios donde no merece la pena crear un archivo CSS aparte.
Por ejemplo, en la cabecera del documento se puede definir que todos los párrafos tengan el texto centrado y de color rojo. Luego, en el body, simplemente se escriben varios párrafos normales. Automáticamente, todos ellos heredarán ese estilo sin necesidad de repetirlo en cada etiqueta.
Este método es mucho más ordenado que el inline, pero sigue teniendo una limitación importante: solo sirve para ese documento HTML. Si tenemos varias páginas, habría que repetir los estilos en cada una, lo cual no es nada práctico a largo plazo.
Estilo externo
El estilo externo es la forma más correcta, profesional y recomendada de trabajar con CSS. Consiste en escribir todos los estilos en un archivo independiente con extensión .css y luego enlazar ese archivo desde el documento HTML mediante la etiqueta link dentro del head.
Con este método, los estilos no están mezclados con el HTML, lo que hace que el código sea mucho más limpio y fácil de entender. Además, una misma hoja de estilos puede reutilizarse en muchas páginas diferentes, manteniendo una apariencia uniforme en todo el sitio web.
Por ejemplo, se puede tener un archivo llamado estilos.css donde se define que los párrafos estén centrados y en color rojo. Luego, desde el documento HTML, se enlaza ese archivo en la cabecera. A partir de ese momento, todos los párrafos de la página, y de cualquier otra página que use esa hoja de estilos, tendrán ese mismo diseño.
Este sistema facilita muchísimo el mantenimiento. Si en algún momento se quiere cambiar el color de los párrafos o su alineación, basta con modificar una sola vez el archivo CSS, y el cambio se aplicará automáticamente a todas las páginas que lo usen.
En resumen, el estilo inline es rápido pero poco recomendable, el estilo interno es útil para documentos pequeños o prácticas, y el estilo externo es el más usado en proyectos reales, ya que permite trabajar de forma ordenada, reutilizable y profesional.



Estilo externo
El estilo externo es la forma más correcta y profesional de trabajar con CSS. Consiste en escribir todos los estilos en un archivo independiente con extensión .css y luego enlazar ese archivo desde el documento HTML utilizando la etiqueta link dentro del head. De esta manera, el HTML se encarga solo del contenido y la estructura, y el CSS se encarga únicamente del diseño.
Este método es el más recomendado porque separa claramente el contenido de la presentación. Cuando se trabaja así, el código queda mucho más limpio, más fácil de leer y también más sencillo de modificar con el paso del tiempo. Es la forma que se utiliza prácticamente siempre en proyectos reales y páginas web profesionales.
Una de las grandes ventajas del estilo externo es que permite reutilizar los mismos estilos en varias páginas. Por ejemplo, si tenemos una web con varias páginas HTML (inicio, contacto, información, etc.), todas pueden usar el mismo archivo estilos.css. Así, toda la web tendrá el mismo aspecto visual sin necesidad de repetir código.
Además, el mantenimiento del código se vuelve mucho más sencillo. Si en algún momento queremos cambiar el color del texto, el tipo de letra o la alineación de los párrafos, solo hay que modificar el archivo CSS una vez. Automáticamente, todas las páginas que estén enlazadas a esa hoja de estilos reflejarán el cambio. Esto ahorra tiempo y evita errores.
El funcionamiento es bastante simple. En la cabecera del documento HTML se añade una línea con la etiqueta link, indicando que se va a usar una hoja de estilos externa y especificando la ruta del archivo CSS, por ejemplo estilos.css. Ese archivo debe estar bien ubicado en la carpeta del proyecto para que el navegador pueda encontrarlo.
Después, en el archivo estilos.css se escriben las reglas CSS normalmente. Siguiendo el ejemplo de siempre, se puede definir que todos los párrafos tengan el texto centrado y de color rojo. En ese archivo se escribiría el selector del párrafo y dentro las propiedades text-align con valor center y color con valor red. A partir de ese momento, cualquier párrafo que aparezca en el HTML se mostrará centrado y rojo sin necesidad de añadir nada más en el código HTML.
Otra ventaja importante es que este método hace que el trabajo en equipo sea mucho más cómodo. Una persona puede encargarse del HTML y otra del CSS sin interferirse mutuamente. Además, facilita detectar errores, ya que el diseño está todo centralizado en un solo archivo.
En resumen, el estilo externo es la mejor opción cuando se quiere trabajar de forma ordenada, limpia y profesional. Es el método ideal para proyectos medianos y grandes, para webs con varias páginas y para cualquier trabajo que se quiera mantener y mejorar con el tiempo. Por eso es el sistema más utilizado en el desarrollo web actual.


Ventajas e inconvenientes de CSS
El uso de CSS supuso un cambio muy importante en la forma de crear páginas web. Antes, el diseño se hacía directamente con etiquetas HTML, lo que provocaba códigos largos, desordenados y difíciles de mantener. Con la aparición de las hojas de estilo, el diseño y la estructura pasaron a estar claramente separados, mejorando tanto el trabajo del desarrollador como el resultado final de la web.
Ventajas de usar CSS
El uso de hojas de estilo aporta muchas ventajas en el desarrollo web moderno.
Una de las ventajas más importantes es que el código es mucho más fácil de mantener. Al tener el diseño separado del contenido, cualquier cambio visual se puede realizar directamente en el archivo CSS sin necesidad de modificar el HTML. Esto ahorra tiempo y reduce la posibilidad de cometer errores.
CSS permite modificar completamente el diseño de una página sin tocar el HTML. Por ejemplo, se puede cambiar el color de fondo, el tamaño de los textos o la distribución de los elementos sin alterar ni una sola línea del contenido. Esto es especialmente útil cuando una web crece o necesita renovarse visualmente.
Otra ventaja clave es que CSS es mucho más potente que las etiquetas de diseño de HTML. Mientras que HTML solo ofrece opciones básicas, CSS permite controlar con precisión colores, fuentes, tamaños, márgenes, animaciones, posicionamiento y diseño responsive. Gracias a CSS se pueden crear diseños complejos y adaptados a distintos dispositivos.
Además, CSS es un lenguaje sencillo y fácil de aprender. Su sintaxis es clara y lógica: se selecciona un elemento y se le aplican propiedades con valores concretos. Esto hace que sea accesible incluso para personas que están empezando en el desarrollo web.
CSS también permite definir varios estilos para un mismo documento. Por ejemplo, se puede crear un estilo para mostrar la web en pantalla y otro diferente para cuando se imprime. De esta forma, una misma página puede adaptarse a distintos contextos sin duplicar contenido.
Otra gran ventaja es que las hojas de estilo pueden reutilizarse en distintos documentos HTML. Un mismo archivo CSS puede aplicarse a muchas páginas, manteniendo una apariencia uniforme en toda la web. Esto es fundamental para crear sitios web coherentes y profesionales.
En conjunto, todas estas ventajas hacen que CSS sea una herramienta imprescindible en el desarrollo web actual.
Inconvenientes de CSS
A pesar de todas sus ventajas, CSS también presenta algunos inconvenientes que es importante conocer.
El principal inconveniente de CSS es que no todos los navegadores interpretan las hojas de estilo de la misma forma. Aunque hoy en día la compatibilidad es mucho mejor que en el pasado, todavía pueden existir pequeñas diferencias entre navegadores.
Algunos navegadores no cumplen totalmente los estándares establecidos, lo que puede provocar que un diseño se vea correctamente en un navegador pero de forma diferente en otro. Esto puede afectar a tamaños, posiciones o efectos visuales.
Debido a esto, en ocasiones el programador se ve obligado a ajustar los estilos para que funcionen correctamente en todos los navegadores. Esto puede implicar escribir reglas adicionales o usar técnicas específicas para asegurar la compatibilidad.
También es necesario probar la web en varios navegadores y dispositivos, lo que aumenta el tiempo de desarrollo. No basta con que la página se vea bien en un solo navegador, sino que debe funcionar correctamente en todos los más utilizados.
En algunos casos, incluso es necesario crear soluciones alternativas para navegadores concretos, especialmente cuando se utilizan propiedades CSS modernas que no están soportadas por versiones antiguas.
A pesar de estos inconvenientes, las ventajas de CSS superan ampliamente a sus problemas. Con buenas prácticas, pruebas adecuadas y un uso correcto de los estándares, CSS permite crear páginas web atractivas, funcionales y profesionales.



Evolución y función de CSS
CSS apareció como respuesta a un problema muy claro en los inicios de la web: el HTML se estaba usando tanto para estructura como para diseño, lo que provocaba documentos difíciles de leer, mantener y modificar. Cada cambio visual obligaba a tocar muchas partes del código, mezclando contenido y presentación en un mismo sitio.
Ante esta situación, el W3C (World Wide Web Consortium) recibió varias propuestas para crear un sistema de hojas de estilo que permitiera controlar el diseño de las páginas web de una forma más limpia y organizada. De todas esas propuestas, se seleccionaron dos como base principal.
La primera fue Cascading HTML Style Sheets (CHSS), propuesta por Håkon Wium Lie en 1994. Esta propuesta introducía la idea de estilos en cascada, es decir, que varias reglas pudieran aplicarse a un mismo elemento siguiendo un orden de prioridad.
 La segunda fue Stream-based Style Sheet Proposal (SSP), que también buscaba separar claramente el diseño del contenido.
A partir de estas ideas surgieron las Cascading Style Sheets (CSS), que con el tiempo se convirtieron en el estándar para el diseño web. CSS permitió por primera vez definir colores, tamaños, márgenes, fuentes y disposición de los elementos sin necesidad de ensuciar el HTML.
Evolución del estándar CSS
La evolución de CSS ha sido progresiva y muy importante para el desarrollo web.
La primera versión, CSS Level 1, se propuso como estándar en 1996. Esta versión permitía definir aspectos básicos como colores, tipos de letra, tamaños de texto, alineación y algunos márgenes. Aunque era limitada, supuso un gran avance respecto al uso de etiquetas HTML para el diseño.
En 1998 se publicó CSS Level 2, que amplió enormemente las posibilidades. Se añadieron conceptos como el posicionamiento de elementos, el control de capas, mejoras en los estilos para impresión y más opciones de maquetación. Esto permitió crear páginas más complejas y estructuradas.
Más adelante, en 2008, apareció CSS 2.1, que no fue una versión completamente nueva, sino una revisión de CSS2. Su objetivo principal fue corregir errores, aclarar comportamientos y mejorar la compatibilidad entre navegadores. CSS 2.1 se centró en estabilizar el estándar para que todos los navegadores lo interpretaran de forma más similar.
Actualmente se trabaja con CSS3, que no es una versión cerrada como las anteriores. En lugar de eso, CSS3 está dividido en módulos. Cada módulo se encarga de una parte concreta del lenguaje, como colores, animaciones, flexbox, grid, sombras, bordes redondeados o transiciones.
Esto significa que algunos módulos de CSS3 ya son estándares completos y ampliamente utilizados, mientras que otros siguen en desarrollo o evolución constante. Gracias a este sistema modular, CSS puede avanzar de forma más flexible sin necesidad de esperar a una versión única y cerrada.
Función actual de CSS
Hoy en día, CSS no solo sirve para dar color o tamaño al texto. Su función es controlar completamente el diseño y la presentación de una web. Con CSS se puede decidir cómo se distribuyen los elementos, cómo se adaptan a móviles, cómo reaccionan a la interacción del usuario e incluso cómo se animan.
Por ejemplo, con CSS se puede hacer que una página se vea en columnas en un ordenador, pero en una sola columna en un móvil. También se pueden crear efectos visuales al pasar el ratón por encima de un botón, cambiar colores dinámicamente o animar elementos sin necesidad de JavaScript.
En resumen, la evolución de CSS ha permitido pasar de páginas simples y estáticas a sitios web modernos, adaptables y visualmente atractivos, manteniendo siempre la separación entre contenido y diseño. CSS se ha convertido en una pieza clave del desarrollo web y sigue evolucionando para adaptarse a las nuevas necesidades de la web actual.


Sintaxis básica de CSS
Una hoja de estilos CSS está formada por reglas CSS. Cada regla indica qué elemento HTML se quiere modificar y cómo se quiere que se vea. Es la base de todo CSS, y entender bien esta sintaxis es fundamental para poder trabajar con estilos más avanzados.
Estructura de una regla CSS
Cada regla CSS se compone de dos partes principales:
Un selector


Un conjunto de declaraciones


El selector indica a qué elementos HTML se va a aplicar el estilo, mientras que el conjunto de declaraciones define qué cambios visuales se van a realizar sobre esos elementos.
La estructura general de una regla CSS sería:
selector {
 propiedad: valor;
 propiedad: valor;
 }
El selector
El selector es la parte inicial de la regla CSS. Sirve para indicar qué elementos del documento HTML serán afectados por el estilo.
 Por ejemplo, si se usa el selector p, se aplicará el estilo a todos los párrafos del documento.
Otros ejemplos habituales de selectores serían:
body → afecta a toda la página


h1 → afecta a todos los títulos h1


div → afecta a todos los contenedores div


Ejemplo escrito como texto:
p {
 font-size: 10pt;
 background-color: gray;
 }
En este caso, el selector es p, por lo que el estilo se aplicará a todos los elementos p del HTML.
Declaraciones CSS
Dentro de las llaves se escriben las declaraciones CSS. Cada declaración indica una característica visual concreta que se quiere modificar.
 Una regla puede tener una o varias declaraciones, separadas por punto y coma.
Cada declaración está formada por dos partes:
Una propiedad


Un valor


La sintaxis es siempre:
 propiedad: valor;
Propiedades
La propiedad indica qué aspecto del elemento se quiere cambiar. Existen muchas propiedades CSS, entre las más comunes están:
font-size → tamaño del texto


color → color del texto


background-color → color de fondo


margin → margen exterior


padding → espacio interior


border → borde del elemento


text-align → alineación del texto


Siguiendo el ejemplo anterior:
font-size: 10pt;
 background-color: gray;
Aquí, font-size y background-color son las propiedades.
Valores
El valor indica cómo se quiere que sea esa propiedad. Dependiendo de la propiedad, el valor puede ser un número, un color, una medida o una palabra clave.
En el ejemplo:
font-size: 10pt;
 background-color: gray;
Los valores son:
10pt → indica el tamaño del texto


gray → indica el color de fondo


Ejemplo explicado paso a paso
Regla CSS escrita como texto:
p {
 font-size: 10pt;
 background-color: gray;
 }
Explicación detallada:
p es el selector, por lo tanto el estilo se aplica a todos los párrafos


font-size es una propiedad que controla el tamaño de la letra


10pt es el valor que define el tamaño del texto


background-color es una propiedad que controla el color de fondo


gray es el valor que establece el fondo en color gris


Si en el HTML hay varios párrafos, todos ellos se mostrarán con texto pequeño y fondo gris, sin necesidad de añadir nada especial en cada etiqueta.
Varias declaraciones en una misma regla
Una regla CSS puede tener muchas declaraciones, lo que permite definir varios estilos a la vez para un mismo elemento.
Ejemplo:
p {
 font-size: 12px;
 color: blue;
 text-align: center;
 background-color: lightgray;
 }
En este caso, todos los párrafos tendrían:
Texto de tamaño 12px


Texto de color azul


Texto centrado


Fondo gris claro


Importancia de la sintaxis
Es muy importante respetar la sintaxis de CSS:
Las declaraciones deben ir entre llaves


Cada propiedad debe ir seguida de dos puntos


Cada declaración termina con punto y coma


Si hay un error de sintaxis, el navegador puede ignorar esa regla o parte de ella


En resumen, la sintaxis básica de CSS se basa en reglas formadas por selectores, propiedades y valores. Dominar esta estructura es esencial, ya que todas las técnicas avanzadas de CSS parten de esta base. Si esto se entiende bien, el resto de CSS resulta mucho más fácil de aprender y aplicar.


Comentarios en CSS
Los comentarios en CSS se utilizan para explicar el código, dejar anotaciones o facilitar la comprensión del diseño, tanto para uno mismo como para otros programadores que puedan trabajar en el mismo proyecto. No afectan al funcionamiento de la página, ya que el navegador los ignora completamente.
Usar comentarios es una buena práctica, sobre todo en hojas de estilo largas o complejas, porque ayudan a organizar el código y a entender rápidamente qué hace cada parte.
Sintaxis de los comentarios en CSS
En CSS, los comentarios se escriben siempre entre los símbolos:
/* comentario */
Todo lo que esté dentro de /* y */ será considerado un comentario y no será interpretado como código CSS.
A diferencia de otros lenguajes, CSS solo tiene un tipo de comentario, pero este puede ocupar una o varias líneas.
Comentarios de una sola línea
Aunque no existe un comentario “de una sola línea” como tal, se puede usar el mismo formato para comentar una línea concreta.
Ejemplo escrito como texto:
/* Color del texto de los párrafos */
 p {
 color: red;
 }
En este caso, el comentario indica que el estilo que viene a continuación se aplica al color del texto de los párrafos.
Comentarios de varias líneas
Los comentarios pueden ocupar varias líneas, lo que es muy útil para hacer explicaciones más largas o separar secciones de la hoja de estilos.
Ejemplo:
/*
 Estilos generales del sitio web
 Se aplican a todos los párrafos
 y definen el color del texto
 */
 p {
 color: red;
 }
Este comentario explica de forma clara qué hace la regla CSS que viene después.
Uso de comentarios para organizar el CSS
Es muy común utilizar comentarios para dividir la hoja de estilos en bloques, por ejemplo: estilos generales, estilos del encabezado, del contenido principal o del pie de página.
Ejemplo:
/* Estilos generales */
 body {
 background-color: white;
 color: black;
 }
/* Estilos de los títulos */
 h1 {
 color: blue;
 }
/* Estilos de los párrafos */
 p {
 font-size: 14px;
 }
Gracias a estos comentarios, es mucho más fácil localizar cada parte del código.
Comentarios para desactivar código temporalmente
Los comentarios también se pueden usar para desactivar una regla o una propiedad sin borrarla, lo que resulta muy útil durante pruebas o modificaciones.
Ejemplo:
p {
 color: red;
 /* background-color: yellow; */
 }
En este caso, el color de fondo no se aplicará porque está comentado, pero el código se conserva por si se quiere volver a usar más adelante.
Comentarios y visualización en el navegador
Es importante recordar que:
Los comentarios no se muestran en la página web


El navegador los ignora completamente


No afectan al rendimiento ni al diseño final


Por ejemplo, aunque el CSS tenga comentarios como:
/* Este texto no se verá nunca en la web */
El usuario no verá nada relacionado con ese comentario al cargar la página.
Importancia de usar comentarios
Usar comentarios en CSS ayuda a:
Entender mejor el código


Mantener el CSS ordenado


Facilitar el trabajo en equipo


Ahorrar tiempo al hacer cambios en el futuro


En resumen, los comentarios en CSS son una herramienta sencilla pero muy importante para escribir hojas de estilo claras, organizadas y fáciles de mantener, especialmente cuando el proyecto crece y el número de reglas aumenta.


Agrupar selectores en CSS
En CSS es muy habitual que varios elementos compartan los mismos estilos. Cuando esto ocurre, no es necesario repetir las mismas propiedades una y otra vez. Para evitar duplicar código, CSS permite agrupar selectores dentro de una misma regla.
Agrupar selectores consiste en escribir varios selectores separados por comas y aplicarles el mismo conjunto de propiedades. De esta forma, todos los elementos indicados recibirán exactamente el mismo estilo.
¿Por qué agrupar selectores?
Agrupar selectores tiene varias ventajas importantes:
Reduce la cantidad de código


Hace la hoja de estilos más limpia y ordenada


Facilita el mantenimiento


Evita errores por duplicar estilos


Si en algún momento hay que cambiar un estilo, solo habrá que hacerlo en un único lugar.
Ejemplo sin agrupar selectores
Si queremos que los títulos y los párrafos tengan el texto de color rojo, podríamos escribir lo siguiente:
h1 {
 color: red;
 }
p {
 color: red;
 }
Este código funciona correctamente, pero estamos repitiendo la misma propiedad y el mismo valor en dos reglas distintas.
Ejemplo agrupando selectores
Para hacer el código más eficiente, se pueden agrupar los selectores:
h1, p {
 color: red;
 }
En este caso:
h1 y p son los selectores


La coma indica que ambos comparten el mismo estilo


La propiedad color con valor red se aplica a los dos elementos


El resultado visual será exactamente el mismo, pero el código es más corto y claro.
Agrupar más de dos selectores
No existe un límite en el número de selectores que se pueden agrupar. Se pueden incluir tantos como sea necesario, siempre separados por comas.
Ejemplo:
h1, h2, h3, p {
 color: blue;
 font-family: Arial;
 }
Con esta regla:
Todos los encabezados h1, h2 y h3 tendrán el mismo color y tipografía


Los párrafos también compartirán ese estilo


Se evita escribir cuatro reglas distintas


Agrupar distintos tipos de selectores
También se pueden agrupar selectores de distinto tipo, como etiquetas, clases o identificadores.
Ejemplo:
p, .destacado, #principal {
 font-size: 16px;
 }
En este caso:
p selecciona todos los párrafos


.destacado selecciona los elementos con esa clase


#principal selecciona el elemento con ese identificador


Todos recibirán el mismo tamaño de letra


Errores comunes al agrupar selectores
Un error frecuente es olvidar la coma entre los selectores. Sin la coma, CSS interpreta otra cosa diferente.
Por ejemplo, escribir:
h1 p {
 color: red;
 }
No significa lo mismo que:
h1, p {
 color: red;
 }
En el primer caso, solo se aplicarían los estilos a los párrafos que estén dentro de un h1, mientras que en el segundo caso se aplican a todos los h1 y a todos los p.
Cuándo es recomendable agrupar selectores
Agrupar selectores es recomendable cuando:
Varios elementos comparten exactamente el mismo estilo


Se quiere simplificar el CSS


Se busca un código más limpio y profesional


Sin embargo, si los estilos van a ser diferentes en el futuro, puede ser mejor separarlos para evitar confusión.


Tipos de selectores básicos en CSS
Los selectores son una parte fundamental de CSS, ya que indican a qué elementos HTML se les van a aplicar los estilos. Sin selectores, CSS no sabría qué modificar dentro del documento.
 Existen muchos tipos de selectores, pero los selectores básicos son los más importantes y los primeros que se aprenden, porque se usan constantemente en cualquier página web.
Los tres selectores básicos principales son:
Selector de elementos


Selector de id


Selector de clase



Selector de elementos
El selector de elementos selecciona todos los elementos HTML de un mismo tipo dentro del documento. Es decir, aplica el estilo a todas las etiquetas iguales que encuentre el navegador.
Este selector se escribe usando directamente el nombre de la etiqueta HTML.
Ejemplo:
 a {
 color: red;
 }
Este estilo afecta a todos los enlaces de la página, ya que selecciona todas las etiquetas a. No importa dónde estén colocadas ni cuántas haya, todas tendrán el texto de color rojo.
Otro ejemplo común sería aplicar estilos a todos los párrafos:
p {
 font-size: 16px;
 color: black;
 }
En este caso, todos los párrafos del documento tendrán ese tamaño de letra y ese color.
Este tipo de selector es muy útil cuando se quiere dar un estilo general a un tipo de contenido, como todos los títulos, todos los enlaces o todos los párrafos.

Selector de id
El selector de id se utiliza para seleccionar un único elemento concreto del documento.
 Un id debe ser único, lo que significa que no puede repetirse en la misma página. Cada id identifica a un solo elemento.
El selector de id se escribe usando el símbolo # seguido del nombre del id.
Ejemplo:
 #example {
 color: blue;
 }
Este estilo solo afectará al elemento que tenga ese id concreto.
Por ejemplo, en HTML:
 p id="example"
Ese párrafo será el único que tendrá el texto de color azul. Ningún otro elemento se verá afectado, aunque sea también un párrafo.
Los selectores de id se suelen usar cuando se necesita aplicar un estilo muy específico a un elemento concreto, como una cabecera principal, un contenedor especial o una sección única de la página.

Selector de clase
El selector de clase permite seleccionar todos los elementos que tengan una misma clase, sin importar el tipo de etiqueta que sean.
 A diferencia del id, una clase puede repetirse tantas veces como sea necesario.
El selector de clase se escribe usando el símbolo punto seguido del nombre de la clase.
Ejemplo:
 .example {
 font-size: 18px;
 }
Este estilo afectará a todos los elementos que tengan esa clase.
Por ejemplo, en HTML:
 p class="example"
 div class="example"
 li class="example"
Todos estos elementos, aunque sean distintos (p, div y li), tendrán el mismo tamaño de letra, porque comparten la misma clase.
Las clases son muy utilizadas porque permiten aplicar estilos reutilizables a varios elementos diferentes, lo que hace el código más flexible y organizado.

Diferencia entre id y clase
Es muy importante no confundir estos dos selectores:
El id se usa para un solo elemento y no se repite


La clase se puede usar en muchos elementos


Un mismo elemento puede tener varias clases


Un elemento solo puede tener un id


Por ejemplo, un elemento puede tener:
 div id="principal" class="example destacado"
Pero no debería haber otro elemento con el mismo id "principal".

Selectores avanzados en CSS
Además de los selectores básicos (elementos, id y clase), CSS dispone de selectores avanzados que permiten seleccionar elementos de forma mucho más precisa.
 Estos selectores son muy útiles cuando el HTML es más complejo y se necesita aplicar estilos según la estructura, los atributos o la relación entre elementos.
Los selectores avanzados permiten:
Reducir el uso excesivo de clases e id


Aplicar estilos según la jerarquía del documento


Crear diseños más limpios y profesionales



Selector universal
El selector universal selecciona todos los elementos de la página, sin excepción.
 Se representa con el símbolo *.
Ejemplo:
{
 border: 1px solid black;
 }


Este estilo aplica un borde negro de 1 píxel a absolutamente todos los elementos del documento HTML: párrafos, títulos, imágenes, listas, divs, etc.
Este selector se usa normalmente para:
Pruebas visuales


Resetear estilos por defecto del navegador


Aplicar propiedades generales como box-sizing


Un uso muy habitual es:
{
 box-sizing: border-box;
 }


Esto ayuda a simplificar el cálculo de tamaños de los elementos.

Selectores de atributos
Los selectores de atributos permiten seleccionar elementos en función de los atributos que contienen, independientemente de su tipo.
Ejemplo:
 img[alt] {
 border: 1px solid black;
 }
Este selector afecta solo a las imágenes que tengan el atributo alt, ignorando las que no lo tengan.
También se puede seleccionar un atributo con un valor concreto.
Ejemplo:
 img[src="alert.gif"] {
 border: 1px solid red;
 }
Este estilo se aplica únicamente a las imágenes cuyo atributo src tenga exactamente el valor "alert.gif".
Estos selectores son muy útiles cuando:
No se quiere añadir clases al HTML


Se quiere aplicar estilo según el contenido o función del elemento


Se trabaja con formularios (por ejemplo, inputs según su tipo)



Selectores de hijos
Los selectores de hijos permiten seleccionar solo los elementos que son hijos directos de otro elemento.
 Se utiliza el símbolo > para indicar esta relación.
Ejemplo:
 div > strong {
 color: blue;
 }
Este selector aplica el color azul solo a los elementos strong que estén directamente dentro de un div.
Si un strong está dentro de otro elemento intermedio (por ejemplo un p), no se verá afectado.
Esto es muy importante cuando se quiere controlar exactamente la jerarquía del HTML y evitar que el estilo se aplique a más elementos de los necesarios.

Selectores de descendientes
Los selectores de descendientes son similares a los de hijos, pero mucho más amplios.
 Seleccionan todos los elementos indicados que estén en cualquier nivel dentro de otro elemento, no solo como hijos directos.
Ejemplo:
 div em {
 color: red;
 }
Este selector aplica el color rojo a todos los elementos em que estén dentro de un div, sin importar si están directamente dentro o anidados en otros elementos.
Por ejemplo, afectará tanto a:
 div > em
 como a:
 div > p > em
Este tipo de selector se usa mucho para dar estilo a textos internos, listas, enlaces o etiquetas específicas dentro de secciones concretas.

Selectores de hermanos adyacentes
Los selectores de hermanos adyacentes permiten seleccionar un elemento que aparece justo después de otro, siempre que estén al mismo nivel en el HTML.
Se utiliza el símbolo +.
Ejemplo:
 h1 + h2 {
 margin-top: -5mm;
 }
Este selector afecta solo al primer h2 que aparezca inmediatamente después de un h1.
Si hay más h2 después, pero no están justo a continuación, no se verán afectados.
Este selector es muy útil para:
Ajustar espacios entre títulos


Modificar el estilo del primer elemento que sigue a otro


Crear efectos visuales controlados sin añadir clases extra



Resumen
Los selectores avanzados permiten un control mucho más preciso del diseño:
El selector universal afecta a todos los elementos


Los selectores de atributos dependen de los atributos HTML


Los selectores de hijos afectan solo a hijos directos


Los selectores de descendientes afectan a cualquier nivel interno


Los selectores de hermanos adyacentes afectan al elemento inmediatamente posterior




Pseudoclases en CSS
Las pseudoclases se utilizan para definir estilos según el estado de un elemento, no según el elemento en sí.
 Es decir, permiten aplicar estilos cuando un elemento está en una situación concreta: cuando el usuario pasa el ratón por encima, cuando un enlace ya ha sido visitado, cuando un campo tiene el foco, etc.
Las pseudoclases son muy importantes para mejorar:
La interacción con el usuario


La usabilidad


La experiencia visual de la página


Se escriben añadiendo dos puntos después del selector.

Pseudoclases más comunes en enlaces
Las pseudoclases más utilizadas suelen aplicarse a los enlaces, ya que estos cambian de estado constantemente según la interacción del usuario.
Las más importantes son:
:link
 Selecciona los enlaces que aún no han sido visitados por el usuario.
 Es el estado inicial del enlace cuando se muestra por primera vez.
Ejemplo:
 a:link {
 color: blue;
 }
Todos los enlaces nuevos se mostrarán en color azul.

:visited
 Selecciona los enlaces que ya han sido visitados anteriormente en ese navegador.
Ejemplo:
 a:visited {
 color: purple;
 }
Esto permite al usuario identificar qué enlaces ya ha visitado.

:hover
 Selecciona un elemento cuando el usuario pasa el puntero del ratón por encima.
Ejemplo:
 a:hover {
 color: red;
 }
Cuando el ratón se coloca sobre el enlace, este cambia a color rojo.
 Es una de las pseudoclases más usadas porque da feedback visual inmediato al usuario.

:focus
 Selecciona un elemento cuando tiene el foco, es decir, cuando está seleccionado mediante teclado, ratón o táctil.
Ejemplo:
 a:focus {
 background-color: yellow;
 }
Esta pseudoclase es muy importante para:
Accesibilidad


Navegación con teclado


Formularios


También se usa mucho en campos input y textarea.

Orden recomendado de pseudoclases en enlaces
Cuando se usan varias pseudoclases en enlaces, es importante respetar el orden correcto para evitar errores:
:link
 :visited
 :hover
 :focus
De esta forma, el navegador interpreta correctamente los estilos.

Pseudoelementos en CSS
Los pseudoelementos permiten aplicar estilos a una parte concreta de un elemento, no al elemento completo.
 A diferencia de las pseudoclases, que dependen del estado, los pseudoelementos dependen de una porción específica del contenido.
Se escriben usando dos puntos dobles :: en CSS moderno, aunque algunos navegadores antiguos aceptan un solo :.

Ejemplo de pseudoelemento ::first-line
El pseudoelemento ::first-line selecciona solo la primera línea de texto de un elemento.
Ejemplo:
 p::first-line {
 color: red;
 }
En este caso:
Solo la primera línea del párrafo se verá de color rojo


El resto del texto mantendrá su estilo normal


Esto es útil para:
Destacar el inicio de un texto


Mejorar la legibilidad


Crear efectos tipográficos



Otros pseudoelementos habituales
Aunque el ejemplo más común es ::first-line, existen otros pseudoelementos muy usados, como:
Permite aplicar estilo solo a la primera letra de un texto, muy usado en diseños tipo revista.
Ejemplo:
 p::first-letter {
 font-size: 40px;
 color: red;
 }

::before y ::after
 Permiten insertar contenido antes o después de un elemento sin modificar el HTML.
Ejemplo:
 p::before {
 content: "→ ";
 }
Este contenido no existe en el HTML, pero sí aparece visualmente gracias al CSS.

Diferencia entre pseudoclases y pseudoelementos
Las pseudoclases:
Dependen del estado del elemento


Cambian según la interacción del usuario


Ejemplo: hover, focus, visited


Los pseudoelementos:
Afectan a una parte concreta del elemento


No dependen del estado


Ejemplo: first-line, first-letter



Modelo de caja en CSS
En CSS, todos los elementos HTML se representan como cajas rectangulares.
 Este concepto se conoce como modelo de caja (box model) y es uno de los pilares fundamentales de la maquetación web.
Entender bien el modelo de caja es imprescindible para:
Colocar correctamente los elementos en la página


Controlar espacios y alineaciones


Evitar problemas de tamaño y desbordamiento


Cada caja está formada por cuatro partes, que se organizan desde el interior hacia el exterior.

Partes del modelo de caja
El modelo de caja está compuesto por:
Contenido
 Relleno (padding)
 Borde (border)
 Margen (margin)
Estas capas rodean al elemento y determinan cuánto espacio ocupa realmente en la página.

Contenido (content)
El contenido es la parte interior de la caja.
 Aquí se muestra el texto, las imágenes o cualquier contenido del elemento.
Ejemplo:
 Un párrafo con texto tiene como contenido ese texto.
 Una imagen tiene como contenido la propia imagen.
El tamaño del contenido puede controlarse con propiedades como:
 width
 height
Ejemplo:
 Un div con width: 200px y height: 100px tendrá un área de contenido de ese tamaño, antes de aplicar padding, borde o margen.

Relleno (padding)
El relleno es el espacio entre el contenido y el borde.
 Sirve para separar el contenido del borde y darle “aire” al interior de la caja.
Características del padding:
Es transparente


Aumenta el tamaño visual del elemento


Nunca puede tener valores negativos


Ejemplo:
 Si un div tiene padding: 20px, el contenido se separará 20 píxeles del borde por todos los lados.
También se puede controlar por lados:
 padding-top
 padding-right
 padding-bottom
 padding-left
Ejemplo:
 padding: 10px 20px
 Arriba y abajo habrá 10px de relleno y a izquierda y derecha 20px.

Borde (border)
El borde rodea el padding y el contenido.
 Es la línea visible que delimita la caja.
El borde se define con tres valores:
 Grosor
 Estilo
 Color
Ejemplo:
 border: 2px solid black
Esto crea un borde:
De 2 píxeles


Sólido


De color negro


El borde:
Aumenta el tamaño total del elemento


No puede tener grosor negativo


Puede definirse por cada lado de forma independiente


Ejemplo:
 border-top
 border-right
 border-bottom
 border-left

Margen (margin)
El margen es el espacio exterior de la caja, es decir, la separación entre un elemento y los elementos que lo rodean.
Características del margen:
Es transparente


Se utiliza para separar elementos entre sí


Puede tener valores negativos (a diferencia del padding)


Ejemplo:
 margin: 20px
El elemento se separará 20 píxeles de los elementos de alrededor.
También se puede definir por lados:
 margin-top
 margin-right
 margin-bottom
 margin-left
Ejemplo:
 margin: 10px 0
 Habrá 10px arriba y abajo y 0 a izquierda y derecha.

Tamaño real de una caja
Uno de los errores más comunes al empezar con CSS es pensar que el tamaño de un elemento es solo su width y height.
En realidad, el tamaño total de una caja es la suma de:
 Contenido
 Padding
 Borde
 Margen
Ejemplo práctico:
 Un div con:
 width: 100px
 padding: 10px
 border: 5px solid
 margin: 20px
No ocupa solo 100px, sino mucho más, porque se suman todas las capas.

Importancia del modelo de caja en la maquetación
Controlar el modelo de caja es esencial para:
Alinear elementos correctamente


Evitar que se salgan del contenedor


Crear diseños ordenados y coherentes


Por eso, en muchos proyectos se ajusta el comportamiento del modelo de caja usando propiedades como box-sizing, para que el cálculo de tamaños sea más predecible.


Margen (margin)
El margen es el espacio externo de un elemento HTML.
 Sirve para separar una caja de otras cajas, es decir, crea distancia entre un elemento y los elementos que tiene alrededor.
A diferencia del padding, el margen no forma parte del interior del elemento, sino que actúa hacia fuera. Por eso es la herramienta principal para organizar el espacio entre bloques de contenido en una página web.

¿Para qué se usa el margin?
El margen se utiliza para:
Separar párrafos entre sí


Crear espacio entre secciones


Centrar elementos horizontalmente


Evitar que los elementos estén demasiado juntos


Un uso muy común es añadir margen inferior a los párrafos para que el texto sea más legible.

Ejemplo básico
Un div con un margen de 20 píxeles se escribiría así:
div {
 margin: 20px;
 }
Esto significa que el elemento tendrá 20 píxeles de separación por todos los lados respecto a otros elementos.

Márgenes por cada lado
El margen se puede controlar de forma individual en cada lado del elemento, lo que permite un ajuste mucho más preciso del diseño.
Las propiedades disponibles son:
 margin-top → margen superior
 margin-right → margen derecho
 margin-bottom → margen inferior
 margin-left → margen izquierdo
Ejemplo:
 Un elemento con 10px arriba, 30px abajo y sin margen a los lados:
div {
 margin-top: 10px;
 margin-bottom: 30px;
 margin-left: 0;
 margin-right: 0;
 }

Forma abreviada del margin
CSS permite usar una forma corta para definir varios márgenes a la vez.
Ejemplos:
 margin: 10px;
 Aplica 10px en todos los lados.
margin: 10px 20px;
 10px arriba y abajo, 20px izquierda y derecha.
margin: 10px 15px 20px;
 10px arriba, 15px a los lados, 20px abajo.
margin: 5px 10px 15px 20px;
 Arriba 5px, derecha 10px, abajo 15px, izquierda 20px.

Valores posibles del margin
El margen admite distintos tipos de valores, lo que lo hace muy flexible.
px
 Valor fijo en píxeles. Es el más usado y el más sencillo de entender.
Ejemplo:
 margin: 20px;
em
 Se basa en el tamaño de letra del elemento actual.
 Si el texto es grande, el margen también lo será.
Ejemplo:
 margin: 2em;
rem
 Se basa en el tamaño de letra del elemento html.
 Es muy útil para diseños coherentes y escalables.
Ejemplo:
 margin: 1.5rem;
%
 Se calcula en función del ancho del contenedor padre.
 Se usa mucho en diseños responsive.
Ejemplo:
 margin: 5%;
auto
 Permite que el navegador calcule el margen automáticamente.
 Se utiliza sobre todo para centrar elementos horizontalmente.
Ejemplo típico:
 Un div centrado horizontalmente:
div {
 width: 300px;
 margin: auto;
 }

Detalles importantes sobre el margin
El margen no tiene color ni fondo, siempre es transparente


Puede aceptar valores negativos, lo que permite solapar elementos


En elementos en línea, los márgenes superior e inferior suelen ignorarse


Los márgenes verticales entre elementos de bloque pueden colapsar


Estos detalles son importantes porque explican muchos comportamientos “raros” al maquetar.

Bordes (border)
El borde define el contorno de un elemento HTML.
 Se sitúa entre el margen (margin) y el relleno (padding) y sirve para remarcar visualmente una caja, delimitar su espacio o simplemente darle un estilo decorativo.
Los bordes son muy importantes tanto a nivel visual como a nivel de maquetación, ya que forman parte del tamaño total del elemento (a no ser que se use box-sizing: border-box).

Estructura básica de un borde
Un borde se define mediante tres partes principales:
El grosor del borde


El estilo del borde


El color del borde


Ejemplo básico:
 Un div con un borde rojo, sólido y de 2 píxeles:
div {
 border: 2px solid red;
 }
En este caso:
 2px es el grosor
 solid es el estilo
 red es el color

Grosor del borde (border-width)
El grosor indica qué tan ancho es el borde.
 No puede ser negativo y normalmente se expresa en píxeles.
Ejemplos:
 border: 1px solid black;
 border: 5px solid blue;
También se puede definir por separado:
div {
 border-width: 3px;
 border-style: solid;
 border-color: green;
 }

Estilos de borde disponibles
CSS ofrece varios estilos de borde que cambian completamente la apariencia visual del elemento.
Los estilos más comunes son:
none
 No se muestra ningún borde.
solid
 Borde continuo y sólido. Es el más utilizado.
dotted
 Borde punteado, formado por pequeños puntos.
dashed
 Borde discontinuo, formado por guiones.
double
 Borde doble, con dos líneas paralelas.
groove
 Da un efecto de borde hundido, con apariencia 3D.
ridge
 Efecto contrario a groove, parece sobresalir.
inset
 Da la sensación de que el elemento está metido hacia dentro.
outset
 Da la sensación de que el elemento sobresale.
Ejemplo con distintos estilos:
div {
 border: 4px dashed blue;
 }
Otro ejemplo:
div {
 border: 6px double black;
 }

Bordes por cada lado
Al igual que con el margin y el padding, los bordes se pueden definir por separado en cada lado.
Propiedades disponibles:
 border-top
 border-right
 border-bottom
 border-left
Ejemplo:
 Un borde solo en la parte inferior:
div {
 border-bottom: 2px solid gray;
 }
Esto se usa mucho para separar secciones o crear líneas divisorias elegantes.

Bordes en elementos en línea
En elementos en línea, como span o a:
El borde izquierdo y derecho siempre se muestran


El borde superior e inferior puede solaparse dependiendo del line-height


Ejemplo:
 Un enlace con borde:
a {
 border: 1px solid red;
 padding: 5px;
 }

Bordes y colapso
A diferencia de los márgenes, los bordes no colapsan.
 Si dos elementos tienen borde, cada uno mantiene el suyo.
Esto es importante para entender por qué a veces aparecen líneas dobles entre bloques.

Uso práctico de los bordes
Los bordes se usan para:
Delimitar cajas


Crear botones


Marcar errores en formularios


Separar visualmente contenidos


Ayudar a depurar maquetaciones (borde temporal para ver cajas)


Ejemplo típico de depuración:
{
 border: 1px solid red;
 }


Esto permite ver todas las cajas de la página y entender mejor la estructura.

Resumen de border
El border define el contorno del elemento
 Se sitúa entre el margin y el padding
 Tiene grosor, estilo y color
 Puede aplicarse por lados
 Aporta tanto diseño como control visual


Relleno (padding)
El padding es el espacio que hay entre el contenido del elemento y su borde.
 Es decir, separa el texto, imágenes u otros elementos internos del borde que rodea la caja.
Mientras que el margin separa un elemento de otros elementos, el padding afecta solo al interior del propio elemento.
Es una parte fundamental del modelo de caja, junto con el contenido, el borde y el margen.

¿Para qué sirve el padding?
El padding se utiliza principalmente para:
Evitar que el contenido quede pegado al borde


Mejorar la legibilidad del texto


Crear espacios internos más agradables


Dar sensación de “aire” dentro de botones, cajas o secciones


Un elemento sin padding suele verse muy “apretado” y poco profesional.

Ejemplo básico de padding
Un div con espacio interno de 10 píxeles:
div {
 padding: 10px;
 }
Esto significa que:
El texto estará separado 10px del borde por todos los lados


El contenido no tocará el borde



Padding por cada lado
Al igual que con margin y border, el padding se puede definir de forma individual en cada lado.
Propiedades disponibles:
 padding-top
 padding-right
 padding-bottom
 padding-left
Ejemplo:
 Más espacio arriba y abajo que a los lados:
div {
 padding-top: 20px;
 padding-bottom: 20px;
 padding-left: 10px;
 padding-right: 10px;
 }
Esto se usa mucho en cajas de contenido o secciones.

Formas abreviadas de padding
CSS permite escribir el padding de forma abreviada para ahorrar código.
Un solo valor:
 padding: 10px;
 Se aplica a los cuatro lados.
Dos valores:
 padding: 10px 20px;
 Arriba y abajo 10px, izquierda y derecha 20px.
Tres valores:
 padding: 10px 15px 20px;
 Arriba 10px, izquierda y derecha 15px, abajo 20px.
Cuatro valores:
 padding: 5px 10px 15px 20px;
 Arriba 5px, derecha 10px, abajo 15px, izquierda 20px.
Este orden siempre se sigue en sentido de las agujas del reloj.

Valores permitidos en padding
El padding nunca puede ser negativo, esto es muy importante.
Valores más comunes:
 px → píxeles
 em → relativo al tamaño de letra del elemento
 rem → relativo al tamaño de letra del html
 % → porcentaje respecto al ancho del contenedor
Ejemplo con em:
 div {
 padding: 1em;
 }
Ejemplo con porcentaje:
 div {
 padding: 5%;
 }

Padding y tamaño del elemento
Por defecto, el padding aumenta el tamaño total del elemento.
Ejemplo:
 Un div con width 100px y padding 20px tendrá:
 100px de contenido
20px izquierda


20px derecha


Resultado: 140px de ancho total (sin contar bordes).
Esto puede causar problemas si no se tiene en cuenta.

Padding y box-sizing
Para evitar que el padding altere el tamaño final, se suele usar:
{
 box-sizing: border-box;
 }


Con esto:
 El padding se incluye dentro del ancho y alto definidos
 El tamaño final del elemento se mantiene estable
Es una práctica muy común en maquetación moderna.

Padding en elementos en línea
En elementos en línea como span o a:
El padding horizontal funciona siempre


El padding vertical puede afectar a la altura visual, pero no rompe la línea


Ejemplo típico:
 Un enlace con padding para parecer un botón:
a {
 padding: 10px 15px;
 border: 1px solid black;
 }
Esto hace que el enlace sea más grande y fácil de clicar.

Uso práctico del padding
El padding se usa constantemente para:
Botones


Tarjetas de contenido


Formularios


Menús


Secciones de texto


Un buen uso del padding mejora muchísimo la experiencia del usuario.


Formas de acortar valores en CSS
En CSS, muchas propiedades como padding, margin o border permiten escribir sus valores de forma abreviada.
 Esto sirve para ahorrar líneas de código, hacer el CSS más limpio y que sea más fácil de leer y mantener.
En lugar de escribir cada lado por separado (top, right, bottom, left), se pueden usar atajos con 1, 2, 3 o 4 valores.
Este sistema sigue siempre el mismo orden:
 arriba → derecha → abajo → izquierda
 (es decir, en el sentido de las agujas del reloj).

Un solo valor
Cuando se escribe un solo valor, se aplica a los cuatro lados por igual.
Ejemplo:
 padding: 10px
Esto significa:
padding-top: 10px


padding-right: 10px


padding-bottom: 10px


padding-left: 10px


Es muy común cuando se quiere un espacio uniforme en todos los lados.

Dos valores
Cuando se usan dos valores, el primero se aplica arriba y abajo, y el segundo izquierda y derecha.
Ejemplo:
 padding: 10px 20px
Esto significa:
Arriba: 10px


Abajo: 10px


Izquierda: 20px


Derecha: 20px


Este formato se usa muchísimo en botones, tarjetas y cajas de texto.

Tres valores
Con tres valores, el reparto es:
Primer valor: arriba


Segundo valor: izquierda y derecha


Tercer valor: abajo


Ejemplo:
 padding: 10px 3% 20px
Esto significa:
Arriba: 10px


Izquierda y derecha: 3%


Abajo: 20px


Es menos común, pero muy útil cuando se quiere más espacio abajo que arriba.

Cuatro valores
Cuando se usan cuatro valores, cada uno corresponde a un lado concreto siguiendo el orden clásico.
Ejemplo:
 padding: 1px 3px 30px 5px
Esto significa:
Arriba: 1px


Derecha: 3px


Abajo: 30px


Izquierda: 5px


Este formato da el máximo control sobre el espacio interior del elemento.

Aplicable a otras propiedades
Este sistema de abreviación no es exclusivo del padding.
 También se usa en:
margin


border-width


border-style


border-color


Ejemplo con margin:
 margin: 20px 10px
Ejemplo con border-width:
 border-width: 1px 2px 3px 4px

Ventajas de usar valores abreviados
Usar esta forma:
Reduce la cantidad de código


Hace el CSS más limpio


Facilita modificaciones rápidas


Evita repetir propiedades innecesarias


Eso sí, es importante entender bien el orden, porque un error puede provocar espacios raros difíciles de detectar.

Display y box-sizing en CSS
Las propiedades display y box-sizing son fundamentales para entender cómo se comportan los elementos en una página web y cómo se calculan sus tamaños. Conocerlas bien facilita muchísimo la maquetación y evita muchos problemas comunes al diseñar con CSS.
Por defecto, los navegadores aplican ciertos valores automáticamente, aunque muchas veces no son los más cómodos para trabajar.

Propiedad display
La propiedad display define cómo se muestra un elemento en la página y cómo ocupa el espacio.
Por defecto, muchos elementos HTML se comportan como:
 display: block
Un elemento con display block:
Ocupa todo el ancho disponible


Empieza en una nueva línea


Empuja al siguiente elemento hacia abajo


Ejemplos típicos de elementos block:
 div, p, h1, h2, section, article
Ejemplo:
 Un div con display block ocupará toda la fila aunque su contenido sea pequeño.
También existen otros valores importantes de display, como:
inline


inline-block


none


flex


grid


Pero el comportamiento inicial más común es block, que explica por qué muchos elementos aparecen uno debajo de otro.

box-sizing por defecto: content-box
Por defecto, los navegadores usan:
 box-sizing: content-box
Esto significa que:
El ancho y alto que se asignan a un elemento solo afectan al contenido


El padding y el borde se suman al tamaño total


Ejemplo:
 Si se define:
 width: 200px
 padding: 20px
 border: 5px
El tamaño real del elemento será:
 200px de contenido
40px de padding (20 a cada lado)


10px de borde (5 a cada lado)


Resultado: 250px de ancho total
Este comportamiento suele ser confuso, sobre todo cuando se intenta ajustar elementos exactamente dentro de un contenedor.

box-sizing: border-box
Para facilitar la maquetación, es muy común cambiar el comportamiento por defecto y usar:
 box-sizing: border-box
Con este valor:
El ancho y alto incluyen contenido, padding y borde


El tamaño total del elemento es exactamente el indicado


Ejemplo:
 Si se define:
 width: 200px
 padding: 20px
 border: 5px
El elemento seguirá midiendo 200px en total, y el navegador ajustará el espacio del contenido automáticamente.
Esto hace que:
Los cálculos sean más sencillos


Las cajas encajen mejor


La maquetación sea más predecible



Uso global de box-sizing
Por esta razón, es muy habitual aplicar box-sizing a todos los elementos del documento.
Ejemplo habitual:
{
 box-sizing: border-box;
 }


De esta forma:
Todos los elementos usan el mismo modelo de caja


Se evitan inconsistencias


El diseño es más fácil de controlar


Este ajuste es casi un estándar en proyectos modernos.

El margen por defecto del body
Otro comportamiento por defecto de los navegadores es que el elemento body tiene un margen automático.
Por defecto:
 body {
 margin: 8px;
 }
Esto provoca que el contenido no empiece exactamente desde el borde de la ventana, algo que muchas veces no se desea.
Por eso, es muy común escribir:
 body {
 margin: 0;
 }
Así:
El contenido ocupa toda la pantalla


Se elimina el espacio blanco exterior


Se tiene un control total del diseño desde cero



Resumen final
Por defecto:
display: block en muchos elementos


box-sizing: content-box


body con margen automático


Para facilitar la maquetación se suele usar:
box-sizing: border-box en todos los elementos


margin: 0 en el body


Desbordamiento (overflow)
Controla qué ocurre cuando el contenido no cabe.
Valores:
 visible, hidden, scroll, auto
Ejemplo:
 div {
 overflow: hidden;
 }


text-overflow
La propiedad text-overflow se utiliza para controlar cómo se comporta un texto cuando no cabe dentro de su contenedor. Es muy común cuando tenemos cajas con un tamaño fijo y textos largos.
Por defecto, si un texto no cabe, simplemente se sale del contenedor o se corta de forma brusca. Con text-overflow podemos decidir qué pasa con ese texto que sobra.
Esta propiedad no funciona sola, necesita ir acompañada de otras propiedades para que tenga efecto:
overflow con valor hidden


normalmente un ancho fijo


en textos de una sola línea, también white-space: nowrap



Valores más usados
clip
 Es el valor por defecto. El texto se corta y la parte que no cabe no se muestra, sin avisar.
ellipsis
 Corta el texto y añade puntos suspensivos (...) al final para indicar que hay más contenido.

Ejemplo explicado
Imagina un div con un tamaño fijo y un texto largo dentro.
Si escribimos:
 div {
 overflow: hidden;
 text-overflow: ellipsis;
 }
Lo que ocurre es:
El texto que no cabe se oculta


En lugar de cortarse de golpe, aparece "..." al final


El usuario entiende que hay más texto del que se ve


Esto es muy usado en:
Tarjetas de productos


Títulos largos


Listados


Menús


Diseños responsive



Ejemplo típico completo
Un contenedor con un ancho fijo y una sola línea de texto:
div {
 width: 150px;
 overflow: hidden;
 white-space: nowrap;
 text-overflow: ellipsis;
 }
Resultado:
 El texto se muestra en una sola línea y, si es demasiado largo, se corta con puntos suspensivos.

Importante
text-overflow no reduce el tamaño del texto, solo controla cómo se muestra cuando no cabe.
 Si no se usa overflow: hidden, la propiedad no funciona.


Flexbox
Flexbox (Flexible Box Layout) es un sistema moderno de maquetación en CSS que permite organizar y distribuir los elementos de una página de forma flexible y eficiente. Su principal ventaja es que facilita la creación de diseños adaptables sin necesidad de usar trucos antiguos como floats o posicionamiento complejo.
Flexbox está pensado para trabajar con una dimensión a la vez (filas o columnas) y es ideal para alinear elementos, repartir espacios y adaptar el diseño a distintos tamaños de pantalla.
Para empezar a usar Flexbox, basta con convertir un elemento en contenedor flex, y automáticamente sus hijos pasan a comportarse como ítems flexibles.
Ejemplo básico:
 Un div con clase container se define con:
 display: flex;
A partir de ese momento, todos los elementos que estén dentro de ese contenedor se organizan siguiendo las reglas de Flexbox.

Conceptos básicos de Flexbox
Contenedor (flex container)
El contenedor es el elemento padre al que se le aplica la propiedad display: flex.
 Es el elemento que controla el comportamiento de todos los elementos que contiene.
En Flexbox, la mayoría de las propiedades importantes se aplican al contenedor, no a los elementos hijos.
Ejemplo:
 Un div llamado container contiene tres div internos.
 Al aplicar display: flex al container, los tres div hijos pasan a organizarse automáticamente en una fila.
El contenedor define:
La dirección de los elementos


La alineación


El reparto del espacio


El comportamiento cuando no hay espacio suficiente



Ítems (flex items)
Los ítems son los elementos hijos directos del contenedor flex.
 Solo los hijos directos se consideran ítems flex; los elementos más internos no lo son.
Ejemplo:
 Si un div container tiene dentro tres div:
 Cada uno de esos div es un ítem flex.
Los ítems se adaptan automáticamente al espacio disponible y pueden:
Crecer


Reducirse


Cambiar de orden


Alinearse individualmente


Flexbox permite controlar cada ítem de forma independiente si es necesario.

Eje principal
El eje principal es la dirección principal en la que se colocan los ítems dentro del contenedor.
 Por defecto, el eje principal es horizontal, es decir, los elementos se colocan en fila, de izquierda a derecha.
Ejemplo por defecto:
 Los ítems aparecen uno al lado del otro formando una fila.
El eje principal se puede cambiar usando la propiedad flex-direction.
Ejemplos de eje principal:
row → eje principal horizontal (por defecto)


column → eje principal vertical


row-reverse → horizontal pero al revés


column-reverse → vertical pero al revés


Cuando el eje principal es horizontal:
El ancho es la dimensión principal


justify-content actúa sobre este eje



Eje secundario (o eje transversal)
El eje secundario es perpendicular al eje principal.
 Si el eje principal es horizontal, el eje secundario es vertical.
 Si el eje principal es vertical, el eje secundario es horizontal.
Ejemplo:
 Si los ítems están en una fila (row):
Eje principal → horizontal


Eje secundario → vertical


El eje secundario se usa para:
Alinear elementos verticalmente


Controlar la altura de los ítems


Ajustar el contenido cuando hay varias filas


La propiedad más usada para este eje es align-items.

Ejemplo práctico completo
Imagina un contenedor con tres cajas:
 Caja 1
 Caja 2
 Caja 3
Si el contenedor tiene:
 display: flex;
El resultado será:
 Las tres cajas aparecen en una fila horizontal, alineadas automáticamente.
Si además se define:
 justify-content: space-between;
Las cajas se separan ocupando todo el ancho del contenedor.
Si se define:
 align-items: center;
Las cajas se alinean verticalmente en el centro del contenedor.
Todo esto se consigue sin usar posiciones absolutas ni floats, solo con Flexbox.

Ventajas de Flexbox
Flexbox permite:
Alinear elementos fácilmente


Crear diseños adaptables


Reordenar elementos sin tocar el HTML


Ajustar tamaños automáticamente


Simplificar mucho la maquetación


Es especialmente útil para:
Menús de navegación


Cabeceras


Tarjetas


Distribución de columnas


Diseños responsive


Diseño responsive
El diseño responsive es una técnica de diseño web que permite que una página se adapte automáticamente a diferentes tamaños de pantalla y dispositivos, como ordenadores, tablets y teléfonos móviles. El objetivo principal es que la web sea cómoda de usar y fácil de leer en cualquier contexto, sin necesidad de hacer zoom ni desplazarse horizontalmente.
Hoy en día, el diseño responsive es imprescindible, ya que los usuarios acceden a las páginas web desde dispositivos muy variados, con resoluciones y orientaciones distintas. Una web que no se adapta correctamente puede resultar incómoda y provocar que el usuario la abandone.
El diseño responsive no consiste en hacer varias webs diferentes, sino en una sola web que se ajusta dinámicamente según el tamaño de la pantalla.

Características del diseño responsive
Diseños flexibles
Los diseños flexibles se basan en usar unidades relativas en lugar de valores fijos. En vez de definir anchos con píxeles exactos, se utilizan porcentajes, em, rem o unidades relativas al viewport.
Esto permite que los elementos se adapten al tamaño disponible y se redimensionen automáticamente cuando cambia la pantalla.
Ejemplo:
 Un contenedor que ocupa el 80% del ancho de la pantalla se ajustará tanto en un monitor grande como en un móvil pequeño.
En lugar de definir:
 Un div con ancho 800px
Se define:
 Un div con width: 80%
Así, el diseño fluye y no se rompe al cambiar de dispositivo.

Media queries
Las media queries son una de las herramientas más importantes del diseño responsive. Permiten aplicar estilos CSS solo cuando se cumplen ciertas condiciones, como el ancho de la pantalla, la orientación o el tipo de dispositivo.
Gracias a las media queries se pueden crear distintos estilos para móvil, tablet y escritorio dentro del mismo archivo CSS.
Ejemplo:
 Cuando la pantalla es pequeña, el texto puede ser más grande y los elementos colocarse en columna.
 Cuando la pantalla es grande, los elementos pueden colocarse en filas y aprovechar mejor el espacio.
Ejemplo escrito:
 @media (max-width: 600px)
 El body cambia el tamaño de letra y los div pasan a ocupar el 100% del ancho.
Esto hace que la web se adapte de forma inteligente al dispositivo del usuario.

Rejillas fluidas
Las rejillas fluidas permiten organizar el contenido en columnas que se ajustan automáticamente al tamaño de la pantalla. En lugar de usar columnas con ancho fijo, se utilizan porcentajes o sistemas flexibles.
Este tipo de rejillas es muy común en diseños modernos, donde el contenido se reorganiza según el espacio disponible.
Ejemplo:
 En un ordenador:
 Tres columnas ocupando cada una un 33%
En un móvil:
 Las mismas columnas pasan a mostrarse una debajo de otra, ocupando el 100% del ancho.
Esto se consigue combinando:
Anchos relativos


Flexbox o grid


Media queries


Las rejillas fluidas hacen que el diseño sea adaptable y mucho más natural.

Imágenes escalables
Las imágenes escalables son fundamentales en el diseño responsive. Una imagen con tamaño fijo puede romper el diseño en pantallas pequeñas o verse borrosa en pantallas grandes.
Para evitar esto, las imágenes deben adaptarse al contenedor que las rodea.
Ejemplo típico:
 img {
 max-width: 100%;
 height: auto;
 }
Con este comportamiento:
La imagen nunca será más grande que su contenedor


Mantiene su proporción original


Se adapta automáticamente al tamaño de la pantalla


Esto garantiza que las imágenes se vean bien en cualquier dispositivo sin deformarse.

Importancia del diseño responsive
Un diseño responsive:
Mejora la experiencia del usuario


Facilita la lectura y la navegación


Reduce la necesidad de zoom y desplazamientos


Mejora el posicionamiento en buscadores


Permite mantener una sola web para todos los dispositivos


Hoy en día, el diseño responsive no es una opción, sino un estándar en el desarrollo web moderno.

Conclusión
El diseño responsive combina varias técnicas para lograr una web adaptable:
Diseños flexibles


Media queries


Rejillas fluidas


Imágenes escalables


Media queries
Las media queries son una herramienta fundamental del diseño responsive. Permiten aplicar estilos CSS dependiendo de las características del dispositivo, principalmente el tamaño de la pantalla.
Gracias a las media queries, una misma página web puede verse bien en:
Ordenadores


Portátiles


Tablets


Teléfonos móviles


Sin necesidad de crear varias versiones de la web.

¿Para qué sirven las media queries?
Las media queries sirven para:
Cambiar colores, tamaños y distribución


Reorganizar el contenido


Ocultar o mostrar elementos


Mejorar la legibilidad en pantallas pequeñas


En lugar de que la web sea rígida, se adapta automáticamente al dispositivo del usuario.

Cómo funcionan
Una media query evalúa una condición, por ejemplo:
Ancho máximo de la pantalla


Ancho mínimo


Orientación (vertical u horizontal)


Si la condición se cumple, se aplican los estilos que hay dentro de la media query.

Ejemplo explicado paso a paso
Estilos generales (por defecto, pantallas grandes):
body {
 background-color: blue;
 color: white;
 }
Esto significa:
El fondo será azul


El texto será blanco


Estos estilos se aplican a pantallas grandes, como ordenadores



Media query para tablets
@media (max-width: 768px) {
 body {
 background-color: green;
 }
 }
Qué ocurre aquí:
Si la pantalla mide 768 píxeles o menos


El fondo pasa a ser verde


Se mantienen los demás estilos que no se cambien


Esto suele corresponder a tablets o pantallas medianas.

Media query para móviles
@media (max-width: 480px) {
 body {
 background-color: yellow;
 }
 }
En este caso:
Si la pantalla es de 480 píxeles o menos


El fondo se vuelve amarillo


Pensado para teléfonos móviles



Orden de las media queries
El orden es importante.
 Normalmente se escriben:
Estilos generales primero


Luego media queries de pantallas más pequeñas


Así, los estilos se van sobrescribiendo según el tamaño del dispositivo.

Mobile First (idea importante)
Una forma moderna de trabajar con media queries es el enfoque Mobile First:
Primero se diseñan los estilos para móviles


Luego se añaden media queries con min-width para pantallas más grandes


Esto mejora:
Rendimiento


Usabilidad


Experiencia en móviles



Qué se suele cambiar con media queries
Algunos ejemplos muy comunes:
Tamaño de letra


Número de columnas


Menús horizontales que pasan a verticales


Imágenes más pequeñas


Ocultar elementos secundarios en móvil



Ejemplo típico de uso real
En un ordenador:
Tres columnas de contenido


En una tablet:
Dos columnas


En un móvil:
Una sola columna para facilitar la lectura


Todo esto se consigue solo con CSS, usando media queries.




