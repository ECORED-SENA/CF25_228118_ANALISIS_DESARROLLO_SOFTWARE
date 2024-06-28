<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 3
      h1 #[i Machine learning]

    .row.bg12.align-items-center
      .col-lg-12.col-12.px-lg-5.px-4.pb-4 
        .row.justify-content-center.align-items-center          
          .col-lg-12  
            .row.justify-content-center.mb-4          
              .col-lg-7.my-3
                .bg10.p-3
                  p(data-aos="fade-down").mb-0 El #[i machine learning] es una rama de la AI (Inteligencia Artificial), que consiste en lograr que las máquinas aprendan automáticamente sin necesidad de ser programadas. El inicio de #[i machine learning] se da en el año 1943, cuando el neurofisiólogo Warren McCulloch y el matemático Walter Pitts, dan a conocer el concepto de inteligencia artificial y en el trabajo que presentaron, plantearon que se analizaría el cerebro como un ente computacional y la creación de supercomputadoras capaces de funcionar mucho mejor que la red neuronal humana, es aquí donde el mundo comenzaría a inquietarse sobre qué tanta inteligencia llegará a tener una máquina y qué implicaciones traería. (Hinestroza, 2018)

              .col-lg-5.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/50.png', alt='')   


            h5(data-aos="fade-down").mb-5 Conozcamos la evolución del #[i machine learning]:  

            .row.justify-content-center.mb-3
              .col-lg-10
                .bgw.p-4.h-100.brad
                  LineaTiempoE.color-secundario
                    div(titulo="1950 ")
                      p El científico Alan Mathison Turing crea el “Test de Turing”, cuyo objetivo principal consistía en determinar la inteligencia de una computadora por medio de una conversación con un humano, la idea era imitar el comportamiento del ser humano sin que se diera cuenta que estaba conversando con una máquina.      
                    div(titulo="1952 ")
                      p El informático y profesor Arthur Samuel lanza el primer programa para computadores preparado para aprender. El software consistía en un juego de damas que almacenaba información y estrategias de juego y que entre más partidas se jugaba, había un mayor mejoramiento en el juego.  
                    div(titulo="1956  ")
                      p Con el apoyo de Minsky, John McCarthy, Claude Shannon y Nathan Rochester, dan nacimiento a la inteligencia artificial.   
                    div(titulo="1958 ")
                      p Rosenblat da a conocer la primera red neuronal artificial.
                    div(titulo="Años 70 ")
                      p Se crea el robot “Stanford Car”, un robot móvil que tenía la capacidad de moverse de manera autónoma en un cuarto sin chocar con obstáculos y también Neighbor implementa el reconocimiento de patrones en computadores, dando inicio al #[i machine learning], debido a que cuando se le daba la posibilidad a una máquina el aprendizaje de patrones, la solución de respuesta era muy efectiva.  
                    div(titulo="Años 80 ")
                      p La revolución se enfoca en el campo del procesamiento de datos cuando Gerald Dejong incorpora el concepto de “Explanation Based Learning” (EBL), que se trataba de una especie de aprendizaje automático, el computador realiza el análisis de datos entrenados y genera reglas, cuyo objetivo es filtrar los datos que tienen menos importancia.
                    div(titulo="2003")
                      p Se hace la publicación de un estudio referente a un sistema distribuido de ficheros que recibe el nombre de “Google File System” (GFS), y toma más fuerza el año 2004, debido a que Google muestra la creación de un nuevo paradigma llamado “Map & Reduce”, enfocado al procesamiento distribuido.   
                    div(titulo="2006")
                      p Sigue el crecimiento y apoyando Google este progreso, crea “Cloud Bigtable”, servicio de bases de datos NoSQL de Big Data, culminando con Hadoop que es una plataforma “Big Data Open Source”.  
                    div(titulo="2010 en adelante ")
                      p Sigue el crecimiento y apoyando Google este progreso, crea “Cloud Bigtable”, servicio de bases de datos NoSQL de Big Data, culminando con Hadoop que es una plataforma “Big Data Open Source”.    
                    div(titulo="Actualidad")
                      p No paran los grandes avances relacionándose con aplicaciones del mundo empresarial que se benefician del #[i machine learning], logrando crear estrategias para la creación de completos mercados, incorporando cada vez más sectores. 

    Separador 
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.1 Conceptos

    p(data-aos="fade-down").mb-5 Existen muchos conceptos alrededor del #[i machine learning]. A continuación, se describen los más importantes.  

    .row.justify-content-start.mb-4
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/icon.svg', alt='')
          .list__txt.bgicon.p-0.px-4.text-white
            h3.mb-0 Inteligencia artificial 

    .row.justify-content-center.mb-4          
      .col-lg-7.my-3
        .bg3.p-3
          p(data-aos="fade-down").mb-0 Consiste en aplicar técnicas sistematizadas que proporcionan a las computadoras recibir algunas características que tiene la inteligencia humana, como por ejemplo, reconocer el significado de objetos y poder identificarlos, resolución de problemas autónomamente, aprendizaje de tareas nuevas, procesamiento de lenguaje natural, reconocimiento de imágenes, entre otros. 

      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/51.png', alt='')        

    .row.justify-content-center.mb-4 
      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/52.png', alt='')               
      .col-lg-7.my-3
        .bg4.p-3
          p(data-aos="fade-down").mb-0 Se tiende a confundir mucho el concepto de inteligencia artificial con #[i machine learning], pero son diferentes, #[b #[i machine learning]] es una rama de la inteligencia artificial que se fundamenta en el potencial que tienen las máquinas para recoger un grupo de datos y aprender por sí mismo, apropiando los algoritmos a medida que se va aprendiendo de la información procesada. #[b La siguiente figura muestra otras de las características que diferencian los dos conceptos.] 

    .titulo-sexto.color-acento-contenido
      h5 Figura 4.
      span Inteligencia artificial vs. #[i machine learning] 
    .bg9.p-4.mb-1
      img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/53.svg', alt='La imagen presenta la relación entre inteligencia artificial, entendida como la combinación de algoritmos, con el propósito de crear máquinas que presenten las mismas capacidades que el ser humano; este es el concepto más amplio que el machine learning; sus funciones se centran en imitar las funciones cognitivas de los humanos, haciendo uso de la computación; en cuanto a los algoritmos, se trata de realizar tareas basadas en algoritmos de una manera “inteligente”. Machine learning que es la disciplina científica del ámbito de la inteligencia artificial que crea sistemas que aprenden automáticamente, es un subconjunto de la inteligencia artificial; en cuanto a los algoritmos, se adaptan a medida que aprenden más sobre la información que procesan. Es de aprendizaje automático, se trata de la capacidad de las máquinas para recibir un conjunto de datos y aprender por sí mismos.') 
    figcaption.mb-5 #[b Nota.] Tomado de Future space 
      a(href="https://www.futurespace.es/machine-learning-los-origenes-y-la-evolucion/" target="_blank") https://www.futurespace.es/machine-learning-los-origenes-y-la-evolucion/

    h5(data-aos="fade-down") También encontramos varios tipos de #[i machine learning]. 

    .titulo-sexto.color-acento-contenido
      h5 Figura 5.
      span Tipos de #[i machine learning] 
    .bg9.p-4.mb-5
      img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/54.svg', alt='Imagen que presenta los tipos de machine learning; entre ellos los supervisados, que son de clasificación, porque detectan spam en un correo y de regresión, porque permiten las predicciones de bolsa. Otro tipo son los conocidos como por refuerzo, porque permiten aprender a jugar diferentes juegos e identificación de coches autónomos. Finalmente, los no supervisados, con autocodificadores y clustering, estos últimos que permiten el reconocimiento de patrones.') 

    .row.justify-content-start.mb-4
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/icon.svg', alt='')
          .list__txt.bgicon.p-0.px-4.text-white
            h3.mb-0 Aprendizaje supervisado   

    .bg3.p-3.mb-5
      p(data-aos="fade-down").mb-0 En este tipo de aprendizaje se utiliza información de entrenamiento llamada #[i dataset], en donde lo que se hace es entrenar con muchas imágenes (#[i labels]) un modelo, para que finalmente pueda determinar de cuál label se trata. Básicamente es un grupo de técnicas, cuya función es permitir hacer predicciones fundamentadas en conductas que son analizadas en datos que han sido históricamente etiquetados.  

    .titulo-sexto.color-acento-contenido
      h5 Figura 6.
      span Aprendizaje supervisado 
    .bg9.p-4.mb-5
      img.img-a.img-t.d-none.d-lg-block(data-aos="zoom-in")(src='@/assets/curso/temas/55.svg', alt='Imagen que ilustra la manera como un conjunto de entrenamiento establece vectores de características que da como resultado el algoritmo de aprendizaje automático y la forma como un conjunto de test establece vector de características que arroja el modelo predictivo (que es proporcional al algoritmo de aprendizaje automático), que lleva a un resultado.')

      img.img-a.img-t.d-block.d-lg-none(data-aos="zoom-in")(src='@/assets/curso/temas/56.svg', alt='Imagen que ilustra la manera como un conjunto de entrenamiento establece vectores de características que da como resultado el algoritmo de aprendizaje automático y la forma como un conjunto de test establece vector de características que arroja el modelo predictivo (que es proporcional al algoritmo de aprendizaje automático), que lleva a un resultado.') 

    p(data-aos="fade-down").mb-5 La figura 6 muestra un ejemplo que contiene un grupo de datos que están etiquetados a propósito: 1 manzana, 2 cítricos, 3 sandías y 4 plátanos. Después, por medio de un vector, son extraídas las características de todo el grupo y con esta información se realiza el entrenamiento al algoritmo de aprendizaje automático. Lo que hace el algoritmo es crear un modelo al que se le pueden agregar nuevos grupos de datos para que sean clasificados nuevos elementos nunca vistos, aplicando lo aprendido en el entrenamiento inicial. 

    .row.justify-content-center.mb-5           
      .col-lg-10
        .bg13.brad
          .row.justify-content-center     
            .col-lg-8
              .p-4
                h5 El aprendizaje supervisado se clasifica en dos tipos de métodos:  
                ul.lista-ul--color.fa-ul.mb-0.ms-0
                  li 
                    i.fas.fa-cube.color1
                    span El método de clasificación consiste, como su nombre lo dice, en hacer una clasificación en un grupo, reconociendo datos que ya han sido etiquetados anteriormente.  

                  li.mb-0 
                    i.fas.fa-cube.color1
                    span El método de regresión realiza la predicción de datos continuos, partiendo de datos etiquetados históricamente, un ejemplo es predecir lluvias o el cambio del valor de un producto.                  
            .col-lg-4
              img.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/57.png', alt='')  

    .row.justify-content-start.mb-4
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/icon.svg', alt='')
          .list__txt.bgicon.p-0.px-4.text-white
            h3.mb-0 Aprendizaje no supervisado 

    .bg3.p-3.mb-5
      p(data-aos="fade-down").mb-0 Al contrario del aprendizaje supervisado, el no supervisado no tiene etiquetas, su objetivo es entender y abstraer patrones de información; se clasifica en clustering y en reducción. La siguiente figura muestra el proceso de aprendizaje no supervisado.  

    .titulo-sexto.color-acento-contenido
      h5 Figura 7.
      span Aprendizaje supervisado 
    .bg9.p-4.mb-5
      img.img-a.img-t.d-none.d-lg-block(data-aos="zoom-in")(src='@/assets/curso/temas/58.svg', alt='La imagen presenta la forma como se lleva a cabo un proceso aprendizaje no supervisado; iniciando datos, seguido de la extracción/selección de características, luego refinamiento del algoritmo de agrupación, pasando a la validación de agrupación, luego a la interpretación de resultados, llegando al tuneo del algoritmo de agrupación y el retorno de este proceso.') 

      img.img-a.img-t.d-block.d-lg-none(data-aos="zoom-in")(src='@/assets/curso/temas/59.svg', alt='La imagen presenta la forma como se lleva a cabo un proceso aprendizaje no supervisado; iniciando datos, seguido de la extracción/selección de características, luego refinamiento del algoritmo de agrupación, pasando a la validación de agrupación, luego a la interpretación de resultados, llegando al tuneo del algoritmo de agrupación y el retorno de este proceso.') 

    .row.justify-content-start.mb-4
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/icon.svg', alt='')
          .list__txt.bgicon.p-0.px-4.text-white
            h3.mb-0 Aprendizaje por refuerzo

    .bg3.p-3.mb-5
      p(data-aos="fade-down").mb-0 Se trata de realizar el entrenamiento de un algoritmo para crear un modelo que esté capacitado para obtener una salida con el resultado más óptimo. El entrenamiento del modelo se hace programando que cada acción tenga sus premios o penalidades, así por cada prueba y error logrará encontrar el resultado que propague los premios.   
    .row.justify-content-center.mb-4
      .col-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 8.
          span Aprendizaje supervisado 
        .bg9.p-4.mb-1
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/60.svg', alt='La imagen representa el aprendizaje por refuerzo, como un agente que toma una acción y obtiene una recompensa, inmerso en un ambiente, a través de sus acciones logran obtener o un premio o una penalización.') 
        figcaption.mb-5 #[b Nota.] Nota. Tomado y adaptado de  
          a(href="https://www.aprendemachinelearning.com" target="_blank") https://www.aprendemachinelearning.com      

    Separador 
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.2 Aplicaciones 

    p(data-aos="fade-down") El #[b #[i machine learning]] se aplica en muchas cosas de nuestra vida cotidiana, a continuación, se nombrarán algunos de los ejemplos donde se aplica y que hacen un gran aporte:       
    .row.bg15.align-items-center
      .col-lg-12.col-12.px-lg-5.px-4 
        .row.justify-content-center.align-items-center          
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7.my-3                           
                AcordionA(tipo="a" clase-tarjeta="tarjeta bg14")
                  div(titulo="Reconocimiento de imágenes ")
                    p Para este proceso existen aplicaciones que comparan las letras, las agrupan y descifran aquellos textos que contienen imágenes. Un ejemplo más claro es el reconocimiento facial que realizan aplicaciones como Nequi o Facebook por medio de redes neuronales complejas.   
                  div(titulo="Reconocimientos de voz ")
                    p Los modelos entrenados para el reconocimiento de voz detectan el sonido y pueden entender las órdenes dadas desde nuestro celular o computador y un ejemplo de estos son Cortana y Siri.    
                  div(titulo="Predicción de datos ")
                    p #[i machine learning] facilita predecir efectivamente datos que se obtienen a través del ingreso de estos a un sistema, se utilizan normalmente en estrategias de comercialización.    
                  div(titulo="Autos autónomos ")
                    p Se aplican los modelos que realizan reconocimiento en tiempo real, los cuales permiten que los carros se desplacen de forma autónoma. Uno de los ejemplos de la actualidad son los carros Tesla.     
                  div(titulo="Sistemas de recomendación ")
                    p Es uno de los ejemplos que aplica #[i machine learning] con el que se interactúa en la cotidianidad, porque aplica algoritmos que siguen patrones de comportamiento según lo que se vea, por ejemplo, las plataformas de películas como Netflix o las aplicaciones de música como YouTube y Spotify.    
                  div(titulo="Watson ")
                    p #[i Software] de inteligencia artificial creado por IBM que puede dar respuesta a preguntas realizadas en un lenguaje natural.    
                  div(titulo="DeepFace ")
                    p Algoritmo creado por Facebook que reconoce personas en fotos.
              .col-lg-5.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/62.png', alt='')        

    Separador 
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.3 #[i Deep learning]  

    .row.justify-content-center.mb-4          
      .col-lg-7.my-3
        .bg3.brad.p-3
          p(data-aos="fade-down").mb-0 El #[i deep learning] se fundamenta también en la inteligencia artificial (AI), es traducido del inglés como aprendizaje profundo y está compuesto por redes neuronales profundas. Su objetivo es tratar de hacer modelos muy similares al aprendizaje que utilizan los humanos para adquirir conocimiento de algo. Aunque se tiende a pensar que el #[i machine learning] y el #[i deep learning] son lo mismo, no es así, porque los algoritmos que utiliza el #[i machine learning] son tradicionales y lineales, mientras que los del #[i deep learning] son fuertemente complejos. 

      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/51.png', alt='') 
    .row.justify-content-center.mb-4
      .col-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 8.
          span #[i Machine learning] y #[i deep learning]

        img.img-a.img-t.d-none.d-lg-block(data-aos="zoom-in")(src='@/assets/curso/temas/62.svg', alt='Imagen que presenta la diferencia entre el funcionamiento del machine learning y el deep learning.') 

        img.img-a.img-t.d-block.d-lg-none(data-aos="zoom-in")(src='@/assets/curso/temas/63.svg', alt='Imagen que presenta la diferencia entre el funcionamiento del machine learning y el deep learning.')             

    .row.justify-content-center.mb-5           
      .col-lg-10
        .bg16.brad.p-4
          .row.justify-content-center     
            .col-lg-8           
              h5 Algunos objetivos del deep learning son:  
              ul.lista-ul--color.fa-ul.mb-0.ms-0
                li 
                  i.fas.fa-cube.color1
                  span Lograr que los computadores se instruyan para poder clasificar sonidos, imágenes y textos, sin que un humano intervenga. 
                li 
                  i.fas.fa-cube.color1
                  span Perfeccionar los procesos pesados, respondiendo a necesidades de los humanos, resolviendo problemas de la sociedad. 
                li 
                  i.fas.fa-cube.color1
                  span Exactitud, lograr un comportamiento que supere al del humano.                
            .col-lg-4
              img.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/64.png', alt='')                                  
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
