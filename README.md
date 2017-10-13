# Agrega.la en Visualizar17

## Resumen
Uno de los proyectos seleccionados para Visualizar17, [Agrega.la](http://www.agrega.la) es una red presente en Brasil, Argentina, Colombia y México, que tiene como objetivo promover la visibilización de contenidos y acciones entre medios independientes, libres o comunitarios. Con 4 años desde su primero concepto, Agrega tiene hoy más de 10 mil posts de casi 40 colectivos de 5 regiones.

Su plataforma digital constantemente hace copias de los posts publicados en blogs y también Facebook (FB) de los grupos registrados; así reúne sus contenidos en un mismo espacio común y realiza continuamente una migración de datos de una plataforma cerrada y privativa para otra abierta y libre. En ella los usuarios que no tienen registro en FB pueden acceder a los contenidos de los medios libres. Además, Agrega.la también reúne contenidos de blogs por medio de RSS y Twitter.

## Equipo en Visualizar17
- [Adriano Belisário](http://github.com/belisards/)
- Daniel Santinho
- Daniela Camacho
- Henrique Parra
- Nataly Fandiño
- [Rolando Druailet](https://github.com/rdrouaillet)

## Referências
- [Plataforma web](http://agrega.la)
- [Github](http://github.com/agregala)
- [Fotos de Henrique Parra](http://henriqueparra.net/photo/index.php/nggallery/madrid-imargens/visualizar?p=1535)
- [Fotos de Nataly Fandiño](https://drive.google.com/open?id=0B_OdLmOhX6bmSHlId3hWbDJDNlk)

## Visualizar17
Visualizar17 fue un momento fundamental para la manutención y continuidad del proyecto. El trabajo fue baseado en 3 grandes retos, identificados cuando empezamos las actividades, después del Simpósio: 

1) **Como crear nuevas formas de visualizar los datos?** El formato anterior, totalmente baseado en una timeline informativa, no alcanzava realmente mostrar lo que pasa en cada región. Como implementar una visualización más afectiva, sexy y impactante? Como transmitir emoción con los datos?

2) **Como fortalecer y hacer más visible la plataforma?** Transmitir más directamente el concepto de la plataforma y su potencialidad, así como de los medios que hacen parte, además de arreglar bugs críticos en el software y servidor.

3) **Como crear reconocimiento entre las regiones?** Inventar modos de estimular que el usuario conozca contenidos de otros medios que no solo de su región.

Así, durante los 15 dias de trabajo en Medialab Prado, identificamos y completamos las seguintes tareas, descritas de forma muy resumida:

 - **Nuevo layout**: creamos una nueva interfaz donde en la portada principal ya se ve claramente el total de posts y colectivos agregados, sus regiones y un mosaico de imagenes, donde el usuário puede de una sola vez captar visualmente las narrativas y contenidos de los grupos. En la página interior, creamos uma nueva seción donde es posible ver contenidos de otras regiones y destacamos la diversidad de medios de cada región, dando más detalles sobre cada organización y visibilizando sus contenidos en la timeline. 
  
- **Nueva región**: fue inserida, aun que con pocos medios, una nueva región: São Paulo (Brasil). El proceso de inclusión de nuevos medios es permanente.

- **Primera versión de la API de Agrega**: Desarrollamos una primera versión de nuestra propia API: así, otros servicios pueden conectarse a Agrega.la y facilmente automatizar procesos que utilizen las informaciones de la plataforma.

- **Publicación del código de la plataforma** : Baseado en WordPress, Agrega.la consiste en un conjunto de templates y plugin que trabajan juntos. Durante Visualizar17, todo el código utilizado y la documentacción técnica de la plataforma fue organizado en [Github](http://github.com/agregala)

- **Correción de bugs críticos**: arreglamos problemas críticos y urgentes en el servidor y en el código del plugin. Sin eso, en pocas semanas, el sítio no seria más posible aceder a la plataforma. También actualizamos el sistema para utilizar la última versión de WordPress y de la API de Facebook. Con 4 años desde su primero concepto, Agrega tiene hoy más de 10 mil posts de casi 40 colectivos de 5 regiones.

Y otras tareas fueran identificadas y desarrolladas pero todavia siguen pendentes de finalización: 

- **Difusión de contenidos**: difusión automática de contenidos de la plataforma en canal de Telegram y perfil de Twitter, uno para cada región.

- **Backup automático**: parceria con Pimentalab para backup automático de los datos de la plataforma.

[![Agrega.la](http://agrega.la/wp-content/themes/agregala-home/img/logo.png)](http://agrega.la)

## Relato de talleres, mentorias y reunión

En la primera jornada de trabajo se identificaron los aspectos a mejorar y las nuevas implementaciones en la plataforma, todo esto de cara a la visualización de datos sobre Agrega.la. Inicialmente, se asignaron tareas relacionadas con la estructura, diseño, experiencia del usuario y la visualización de datos; las labores se organizaron de acuerdo a su importancia y el grado de complejidad de las mismas. 
Con el propósito de tener un manejo amplio del sitio web y de las herramientas necesarias para su funcionamiento, se impartirán algunos talleres sobre GibHub ó Google Analytics, entre otras temáticas que vayan apareciendo según las necesidades que se presenten. 

Curaduría: es necesario revisar cómo se organiza, jerarquiza y muestra la información en la plataforma; tanto para facilitar la búsqueda/lectura del usuario, como para la identificación de información desde otros sistemas. Al integrar diferentes colectivos en una misma plataforma, también se estimula una interacción entre esos medios, al mismo tiempo que se presenta a los lectores un conjunto de medios con afinidades. Además de la selección de los medios alternativos, la elección de algunas temáticas específicas (a través de tags o categorías) es fruto de un trabajo editorial. Esto implica crear algún tipo de organización, clasificación y jerarquización entre diferentes contenidos. 

En el primero dia, organizamos asi algunas tareas, utilizando una metodologia propia. En un grafo, donde el eje Y significa *urgencia* y ele X significa *complexidad*, inserimos un postit por tarefa en su ubicacción adequada. 

MÁS IMPORTANCIA: vaciar el disco lleno, publicar el código en GitHub, revisar el algoritmo de las categorías respecto a su calidad y redundancia, review de funcionalidades respecto a la imágenes y vídeos importados, review layout, ajustes de diseño para una apariencia más atractiva en pro de mejorar la experiencia del usuario. 

MENOS IMPORTANCIA: Newsletter, difusión de los posts, publicitar a través de rebotes, publicitar la plataforma tanto para los lectores como para los medios interesados (en vídeo es una opción), organización de las publicaciones por tópicos, 
. 
Algunas ideas resultado de esta primera reunión: en esta nueva etapa del proyecto, principalmente se busca hacer una plataforma más llamativa, atractiva, que el usuario disfrute navegar por Agrega.la. 

Para la visualización de datos, habíamos pensado analizar los tags  y la manera en que las categorías se entrelazan; puede ser por país/región, el tipo de información o los gustos de los usuarios. No es posible llevar a cabo esta labor porque no tenemos un sistema/aplicativo que automatice la información; y hacerlo de forma manual por colectivo/noticia, no es efectivo. 

En ese sentido, para la visualización de datos es más sencillo exponer la información de los colectivos (dónde se ubican, quiénes son ,qué contenido producen), es decir la caracterización de los medios con lo que contamos. Además, podemos visualizar los datos sobre el número de publicaciones y el número de colectivos. 

### Mentoría con Hannah Williams 
Reunión con Hanna  por parte de Adriano, Daniel y Daniela. Le hemos contado nuestras ideas de organización y visualización de contenido de la plataforma, en búsqueda de mejorar los aspectos existentes, potenciarlo visualmente e incluir interactividad de usuarios.
Luego del intercambio de ideas hemos llegado  a la conclusión de que debemos estructurar los contenidos, ésto para responder funcionalmente al uso de la página con elementos que ya se tienen, también para contemplar los nuevos cambios y posteriormente encontrar la forma de representaciones gráficas, las que se pre conceptualizan bajo conceptos de dinamismo y formas orgánicas.


### Taller Agrega.la - Adriano Belisário

El taller se centró en la exploración de esta herramienta que sirve como repositorio del código y contenido interno de Agrega.la. El propósito de esta actividad fue compartir los conceptos básicos del lenguaje informativo con los miembros del equipo que no tienen conocimiento en programación o desarrollo web.   

Opinión de Nataly Fandiño 

La información fue útil para entender cómo se desarrolla y diseña la página web desde el sistema operativo, para conocer algunos conceptos básicos de programación y para la exploración intuitiva del Github. Esta metodología favorece el fortalecimiento del proyecto, porque todos conocemos las diferentes áreas de trabajo y su funcionamiento; especialmente favorece la libre circulación del conocimiento. 


Opinión de Daniela Camacho 

El taller nos ha acercado al lenguaje informático y nos ha hecho comprender a los que venimos de diferentes ramas, cómo todas las ideas luego se pueden materializar a la web, y cómo está funcionando la plataforma existente. Realmente era muy necesario recibir esta información de parte de los colaboradores para comprender el panorama que tenemos de frente y plantear nuestros objetivos.

### Taller GitHub - Adolfo Bravo  

Opinión de Daniela Camacho 

El taller ha sido de gran utilidad para compartir información de softwares y plataformas, así como de continuar con la aclaración de lenguajes informáticos. Sin embargo, ha sido un poco de extrañar el uso práctico de la herramienta,  pues aunque se entiende que habrá tiempo para ésto en el proceso y la práctica personal, quienes no estamos nada familiarizados con la plataforma, no podemos valorar con cuantía los datos recibidos a falta del factor de integración.

### ACCESO Y FUNCIONALIDAD 

El equipo de trabajo se concentró en identificar puntualmente las fallas en accesibilidad, funcionalidad, diseño y posicionamiento de Agrega.la.  

- Posible fallo en la reproducción de las radios de Meso México 
En Safari me abre el icono de reproducir.  No consigo que suene. Pienso que debería de haber una forma de notificar al usuario que esta escuchando la radio.
En Chrome no me abre el icono de reproducir. Al abrir la pestaña para reproducir surge un contratiempo de funcionalidad: La pestaña se abre hacia el lado izquierdo y apenas se ve. Consigo que suene.

-En el protocolo de agregación de medios deberíamos sustituir "Otras mensajes" Por: Etiquetas, Hashtags o Tags. Tal vez proponiendo varias opciones de etiquetado. También deberíamos poner una categoría donde se pueda subir el logo del medio. Con una serie de exigencias de formato. Para que al agregarse un medio el administrador de la región no tenga que hacer todo manualmente sino que simplemente modere y decida si el medio es apropiado y ya copie y pegue toda la información del medio al wp.

-Cambiaría el nombre de publicaciones relacionadas por otros posts

-Botón ver publicaciones agregadas no funciona: 

-Cuando se ingresa como ´´admin´´ la barra de opciones cubre los encabezados (dejar mayor espacio en diseños futuros o problema de la plataforma) 

-Identificar aquellos medios que pueden estar activos durante la navegación ( radio, que más? ) con un ícono claro que invite a la escucha y que pueda funcionar ésta aunque se esté navegando por la página, pop-up?
Ejemplo: quiero escuchar música de la región de méxico y leer noticias de la región caribe.

-Me encantan las publicaciones relacionadas. Cómo hacer evidente y funcional las segmentación de éstas en las diferentes regiones? 

Ejemplo: Si leo sobre convocatorias en México, que bien tener a la derecha convocatorias en otros países, ya que algunas ( pueden, no sé ) en algún momento ser abiertas a artistas o colectivos de otros países, y ésto también es otra forma de conectar medios.

- Información de los medios/colectivos/radios:  Al clicar en un colectivo (medio) sería muy bien encontrar todos los post de ese colectivo, categorizados con los hashtags según el tema, o mostrando los hashtags arriba si el medio se dedica solo a la publicación de un tema específico . Si es posible, agregar a la derecha un pop up que cuente a que se dedica el colectivo en un breve texto, con el nombre/logo/o foto.

### DISEÑO 

-Se reconoce la necesidad de generar un concepto visual sobre el pilar de información de libre acceso de la plataforma, el cual debe ser visualmente identificable y atractivo

-Redefinir una paleta de colores ligada al concepto que se desarrolle clara en en toda la interfaz

-Revisar el logotipo y las tipografías en función de concepto y paleta de colores

- Botón de AGREGA.TE : Encontrar el sitio idóneo dentro de la interfaz para su colocación, englobarlo en una forma que se incluya al diseño y que invite a su vez a clicar.  
-Respecto a la página a la que redirige, también se puede intervenir con alguna lúdica y hacer el espacio mayor para  (contactar desde ahí?, formulario de correo, nombre, mensaje?)

-Es confuso ahí encontrar el mail de contacto@ y el de región@ , se puede establecer la diferencia clara u optar por uno o el otro. 

- Revisitar las opciones de nombramiento de las regiones para dejarlas claras , ( aprovechar la bandera de cada país para situarla y animarla en los saltos de página?

-Deberíamos de unificar la pestaña de home, acerca, medios etc, que está en el header a la derecha. Queda muy extraño que en unos sitios haya y en otros no.

- Buton ver publicaciones agregadas no funciona

### POSICIONAMIENTO 

-Este análisis va desde octubre de 2016, hasta septiembre del presente año. Según las cifras, en total han habido 962 sesiones, pero los datos varían según cada interacción del usuario. Primera (245 s), Segunda (157 s) y Tercera (88s). En este flujo se puede evidenciar que se han perdido 472 s (casi el 50 %), es decir, el interés de continuar la navegación. 

El recorrido del usuario inicia en la página principal, por ser la más visitada, luego hay un desplazamiento a Río y al Caribe, hecho que se vincula a que, por un lado, los contenidos de Brasil tienen una mayor trayectoria, y por otro lado, porque el año pasado se creó Agrega.la Caribe. 

- Según los datos de Google Analytics, hay 65 usuarios en promedio y 582 nuevos, y de esta muestra anterior, el porcentaje de los que sale de la página es del 66,21 %; lo cual quiere decir que los usuarios nuevos no se están sintiendo atraídos por el contenido de la página  pierden el interés muy rápido. 

-La mayoría de los usuarios ingresan a la plataforma desde la URL de Agregala directamente en la barra del navegador. Otros usuarios llegan por referencia desde otros sitios web .Y en la misma proporción que el anterior grupo, los usuarios se enteran de Agrega.la de forma natural, porque Google nos tiene ubicados en el cuarto lugar.   


### Mentoría Carlos  Gil Bellosta
Nataly se reunió con Carlos para recibir asesoría sobre el análisis de los datos de Google Analytics, pasando desde conceptos, interpretación de las cifras, hasta la revisión de la página. Según los anterior, Carlos sugirió el uso de herramientas como Seoptimer y Análisis SEO de Google para hacer una identificación más precisa de las fallas en la plataforma. Además, el mentor precisó que el botón de “Entrar” no es funcional porque de inmediato no dirige al usuario a alguna opción para su navegación; lo cual es un motivo para que el  usuarios salga de la página. Carlos sugiere que  al dar “Entrar” se despliegen de inmediato las regiones, o bien se las regiones se visualicen con con íconos o recursos visuales que guíen al usuario.  

Con base en la información anterior, se sugiere al equipo mejorar la apariencia y estructura de la página principal, ya que desde allí es donde se puede acceder al resto de páginas de Agrega.la. 

     

