<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-md-0
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 1
      h1 Internet de las cosas (loT)

    .row.bg2.align-items-center
      .col-lg-12.col-12.px-lg-5.px-4.pb-4 
        .row.justify-content-center.align-items-center          
          .col-lg-12  
            .row.justify-content-center.mb-4          
              .col-lg-8.my-3
                .bg3.p-3
                  p(data-aos="fade-down").mb-0 Gracias a su relevancia y avance significativo, la IoT se considera una de las tecnologías con mayor influencia para el año 2025. Se prevé que una amplia gama de objetos incorporará diversos tipos de sensores conectados a Internet, lo que generará un enorme volumen de datos. Estos datos deberán ser gestionados, almacenados y presentados de manera accesible y comprensible.

              .col-lg-4.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/4.png', alt='')   

            .row.justify-content-center.mb-4
              .col-lg-4.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/5.png', alt='')                        
              .col-lg-8.my-3
                .bg4.p-3
                  p(data-aos="fade-down").mb-0 #[b El concepto de IoT] (Internet de las cosas), fue presentado por primera vez en Procter y Gamble en el año de 1999 por Kevin Ashton, describiendo que consistía en la generalización de una variedad de diferentes cosas, objetos o elementos de tipo cotidiano, integrados como etiquetas de identificación por medio de radiofrecuencias (RFID), los cuales eran controlados por Internet, generando una gran cantidad de datos que necesitaban ser recolectados y almacenados, razón por la cual IoT se integra con Cloud Computing para que estos datos se alojen en Internet, facilitando que estén en continua disponibilidad, para que las empresas y usuarios puedan acceder desde cualquier lugar.            
                   
            h5(data-aos="fade-down") En resumen, se puede decir que IoT es la agrupación de sensores y equipos electrónicos conectados entre sí, con el objetivo de calcular, recolectar y mandar datos a un servicio de almacenamiento en la nube.                    
      
            .row.justify-content-center.align-items-center
              .col.my-3
                p(data-aos="fade-down") El IoT en la actualidad, está organizado por una recolección extendida de diferentes redes y con propósitos distintos, por ejemplo, los carros modernos cuentan con una cantidad variada de redes para moderar la puesta en marcha del motor, el monitoreo de comunicación, los sistemas de seguridad. De esta manera parecida, los centros comerciales, las oficinas, los apartamentos manejan diferentes sistemas que permiten controlar la calefacción, el aire acondicionado, los sistemas de seguridad, etc. En tanto que el IoT avanza, todas estas redes quedarán conectadas incorporando medidas de análisis, administración y seguridad, haciendo del IoT una herramienta todavía más poderosa.                
              .col-lg-auto.my-3                  
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/6.png', alt='')   

            .row.justify-content-center
              .col-auto
                .titulo-sexto.color-acento-contenido
                  h5 Figura 1.
                  span Internet de las cosas red de redes 
                .bg5.p-4
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/7.svg', alt='Figura que representa la relación de los elementos del Internet de las cosas en el contexto de la empresa, compuesta por: educación, transporte, página de inicio, empresa, ecológico, energía y otros; y la manera como cada uno de ellos se define como red individual, el vínculo entre ellas, como conectadas y finalmente el todo de la red, se caracteriza con seguridad, análisis y administración.')   

    h5(data-aos="fade-down").mb-5 Entre las diferentes áreas de aplicación que tiene el mundo del IoT, se destacan las siguientes: 


    .row.bg6.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.p-5 
        .row.justify-content-center.align-items-center          
          .col-lg-12 
            .tarjeta.bgw.p-4(data-aos="fade-left")
              SlyderA(tipo="b")
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Domótica 
                    p Consiste en la sistematización de una edificación, casa, o inmueble, conectando entre sí diferentes tipos de servicios como energía, agua, ventilación y dispositivos como cerrojos, electrodomésticos, optimizando la seguridad y eficiencia energética, garantizando un mejor bienestar para el usuario.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/9.png', alt="")  
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Automatización y control de procesos de producción
                    p Se emplea la tecnología de IoT para incrementar la eficiencia en la fabricación de los productos, así como su fiabilidad y el continuo seguimiento del producto en la fábrica.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/10.png', alt="")     
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Transporte y logística 
                    p Consiste en monitorizar medios de transporte y el proceso de envío de productos, validar estados de conservación y ubicación, evitando robos o pérdidas, logrando realizar un análisis de mejores rutas o administración de tráfico. Unos ejemplos donde son utilizados son en las empresas de envíos o en las plataformas de servicios de carros, gestión de tiempos de traslados, gestión y control de vehículos.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/11.png', alt="")  
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Agricultura, ganadería y silvicultura 
                    p Al igual que en las fábricas, IoT es utilizado para la automatización de trabajos primordiales en lo relacionado con el agro, como por ejemplo, sistema de riego, sistema de detector de temperatura para siembra, detección de enfermedades de los animales, entre otros.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/12.png', alt="")  
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Videovigilancia y seguridad  
                    p Consiste en la configuración y control de una variedad de equipos de seguridad, tales como sensores de movimiento, alarmas inteligentes, detección de amenazas para proteger la seguridad de edificaciones, casas y así contar con una prevención cuando se presenten situaciones de riesgo.   
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/13.png', alt="")  
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Medicina 
                    p Sus objetivos son detectar en una persona sus signos vitales, así como las variaciones para el suministro de medicinas. Aunque la orientación es más a los humanos, es posible también monitorear el estado de salud de los animales domésticos. La incorporación de IoT en el sector de la salud transformará el cuidado médico, porque los centros de atención serán mucho más eficientes, brindando al personal de la salud datos muy importantes de los pacientes en tiempos más cortos, para poder agilizar los procesos médicos.   
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/14.png', alt="") 

    p(data-aos="fade-down") En la actualidad, existen muchos desarrollos que incorporan IoT en sus diferentes áreas de aplicación. 
    h5(data-aos="fade-down") A continuación, se nombran unos de los más novedosos y curiosos.    

    .row.bg8.align-items-center
      .col-lg-12.col-12.px-lg-5.p-5 
        .row.justify-content-center.align-items-center          
          .col-lg-12
            .row.justify-content-center
              .col-lg-3.my-3
                img.img-a.img-t(data-aos="fade-left")(src='@/assets/curso/temas/15.png', alt="")      
              .col-lg-9.my-3
                .bg7.p-3.brad.h-100(data-aos="fade-down")
                  h5 Hidrate Spark   
                  p.mb-0 Se trata de un termo para el agua que tiene colores metálicos muy llamativos, el cual informa el tiempo en que se debe tomar agua y reporta la cantidad de agua tomada según lo que se configure, este funciona por medio de un sensor que recolecta cada trago de agua y lo envía al celular por medio de bluetooth.   

              .col-lg-3.my-3
                img.img-a.img-t(data-aos="fade-left")(src='@/assets/curso/temas/16.png', alt="")      
              .col-lg-9.my-3
                .bg7.p-3.brad.h-100(data-aos="fade-down")
                  h5 Ability MyCite   
                  p.mb-0 Es una pastilla inteligente que fue creada por Otsuka Pharmacutical Co y Proteus Digital, utilizada para tratar a las personas que sufren de trastorno bipolar o esquizofrenia. La pastilla incluye un sensor que envía señales a una aplicación, el sensor es activado cuando la pastilla se disuelve con los ácidos gástricos del estómago, permitiendo así realizar un seguimiento al paciente, verificando la hora de toma del medicamento y si en efecto se lo está tomando. 

              .col-lg-3.my-3
                img.img-a.img-t(data-aos="fade-left")(src='@/assets/curso/temas/17.png', alt="")      
              .col-lg-9.my-3
                .bg7.p-3.brad.h-100(data-aos="fade-down")
                  h5 Waymo 
                  p.mb-0 Es el primer carro autónomo creado por Google, que permite a un automóvil conducirse autónomamente por carreteras, detecta señales de tráfico, peatones y otros carros; inicialmente el nombre del proyecto era Google self-driving car project y luego recibió el nombre de Waymo.   

              .col-lg-3.my-3
                img.img-a.img-t(data-aos="fade-left")(src='@/assets/curso/temas/18.png', alt="")      
              .col-lg-9.my-3
                .bg7.p-3.brad.h-100(data-aos="fade-down")
                  h5 Google Glass 
                  p.mb-0 Son unas gafas desarrolladas por Google para realidad aumentada, su función principal es poder manejar aplicaciones sin utilizar las manos, solo con comandos de voz; estas gafas incorporan un miniproyector que muestra una imagen virtual al ojo. Estas gafas son usadas en diferentes áreas como la educación, la industria y la medicina.                                 

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
