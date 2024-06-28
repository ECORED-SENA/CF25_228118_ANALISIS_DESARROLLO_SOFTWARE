<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 2
      h1 #[i Blockchain]

    .row.bg2.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.p-5 
        .row.justify-content-center.align-items-center          
          .col-lg-12 
            p(data-aos="fade-down").mb-5 Para conocer qué es el #[i blockchain], lo invitamos a revisar la siguiente figura. 
            .row.justify-content-center
              .col-auto
                .titulo-sexto.color-acento-contenido
                  h5 Figura 2.
                  span.fst-italic Blockchain 
                .bg9.p-4
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/20.svg', alt='Mapa mental en el que se muestra cómo el blockchain, es una de las tecnologías más innovadoras del siglo XXI, debido a la importancia obtenida en varios sectores como la educación, áreas financieras y manufactura; su historia inicia a principio de los noventa y ha logrado un crecimiento con la aparición de una serie de aplicaciones que generan un importante impacto en la economía digital; el concepto blockchain, surge en 2009 con la aparición de bitcoin.')                   

    h5(data-aos="fade-down").mb-5 El problema que quiere solucionar esta tecnología se puede explicar en el siguiente ejemplo: 
    
    .row.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/21.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Cuando una persona llamada Pepito quiere realizar un envío de un millón de pesos a otra persona llamada Mario, normalmente se hace por medio de un banco, donde el banco actúa como intermediario de esta transacción, haciendo una centralización efectiva para hacer el movimiento de un lado al otro. En este proceso, ni Pepito ni Mario intervienen, son totalmente dependientes del banco y a las condiciones de este como comisiones, por ejemplo, es aquí donde el #[i blockchain] o cadena de bloques interviene, porque su principal objetivo es eliminar los intermediarios, haciendo una gestión totalmente descentralizada, donde el control ya no va a ser de los bancos sino de los usuarios, convirtiéndose estos en una conexión de muchos nodos del banco.   

    p(data-aos="fade-down") En resumen, se puede decir que el #[b #[i blockchain]] o cadena de bloques, es un gran libro digital de cuentas en donde sus bloques (registros), se encuentran conectados y cifrados, con el objetivo de proteger la privacidad y la seguridad de cualquier tipo de transacciones. 

    h5(data-aos="fade-down").mb-5 En la siguiente figura se muestra gráficamente la comparación entre un sistema tradicional y un sistema #[i blockchain].  
    .titulo-sexto.color-acento-contenido
      h5 Figura 3.
      span Sistema tradicional vs. Sistema #[i blockchain]  
    .row.justify-content-center
      .col-lg-6
        .bg5.p-4.h-100
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/22.svg', alt='La imagen representa el sistema tradicional, en el que las transacciones de cualquier tipo debían ser mediadas por el banco, versus, el sistema blockchain, en el que ya no se requiere intermediación bancaria, si no que las transacciones se hacen de manera directa.') 
      .col-lg-6
        .bg9.p-4.h-100  
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/23.svg', alt='La imagen representa el sistema tradicional, en el que las transacciones de cualquier tipo debían ser mediadas por el banco, versus, el sistema blockchain, en el que ya no se requiere intermediación bancaria, si no que las transacciones se hacen de manera directa.')    

    Separador 
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.1 Historia   

    p(data-aos="fade-down") A continuación, conozcamos un poco sobre la historia del #[i blockchain]:       
    
    .row.bg6.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.p-5 
        .row.justify-content-center.align-items-center          
          .col-lg-12 
            .tarjeta.bgw.p-4(data-aos="fade-left")
              SlyderA(tipo="b")
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Historia del #[i blockchain]:  
                    p El #[i blockchain] tuvo su inicio en los años de 1991-2008, donde en un primer trabajo, Stuart Haber y Scott realizaron tareas en una cadena de bloques que era protegida criptográficamente, esto quería decir que no se podía realizar ningún tipo de manipulación en las marcas de tiempo de los documentos.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/24.png', alt="")     
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Árboles de Merkle
                    p En el año 1991 se añadieron árboles de Merkle que lograron una mejor eficiencia, permitiendo que en un solo bloque se recopilara más de un documento. Pero es en el año 2008 que el #[i blockchain] inicia su crecimiento, cuando Satoshi Nakamoto y un grupo de personas lanzan su trabajo con bitcoin, creando la primera aplicación de registro digital que permitía administrar la red del bitcoin, permitiendo la interacción por medio de foros, entre los interesados. 
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/25.png', alt="") 
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Nacimiento del Bitcoin
                    p Desde los años 2008 al 2013 emerge el bitcoin y las transacciones, es importante aclarar que no hay que confundir el concepto de #[i blockchain] y bitcoin, porque muchas personas piensan que es lo mismo, y no es así, debido a que #[i blockchain] es la tecnología en que se fundamentan las aplicaciones y una de ellas es la criptomoneda. El nacimiento del bitcoin fue en 2008 y fue la primera aplicación que incluía la tecnología #[i blockchain], la definición dada por Satoshi Nakamoto en su artículo fue que se trataba de un sistema eléctrico peer to peer (punto a punto). 
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/26.png', alt="") 
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Se establece el bloque de origen
                    p Desde el momento en que el bitcoin, que es una aplicación de #[i blockchain], se puso en conocimiento, han surgido una gran variedad de aplicaciones que tienen como objetivo el aprovechamiento de la tecnología digital. 

                    p Satoshi estableció el bloque origen de donde salieron otros bloques, los cuales se interconectaban, obteniendo como resultado una gran cadena de bloques que enviaban varios fragmentos de información y transacciones.  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/27.png', alt="")     
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Surgimiento de los contratos inteligentes
                    p Para los años 2013-2015, #[i blockchain] evolucionó a su versión 2.0 y trajo los llamados contratos inteligentes (smart contracts), desarrollo realizado por Vitalik Butterin y al que llamaron Ethereum, que incorporaba una función que ofrece a los individuos registrar otro tipo de activos como lo son los contratos, ampliando a una plataforma que también desarrolla aplicaciones descentralizadas. Un contrato inteligente es un conjunto de instrucciones que se almacenan en un #[i blockchain], las cuales se ejecutan automáticamente, dependiendo de los parámetros programados, esta ejecución se realiza de forma segura e inmutable. 
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/28.png', alt="") 
                .row.justify-content-center.p-2
                  .col-lg-4.my-3.col-md-auto
                    h4.t2 Revolución de las aplicaciones del #[i blockchain] 
                    p A partir del 2018 surgen una serie de proyectos, explotando la gran capacidad de la tecnología #[i blockchain], estos proyectos buscaban tratar las fallas de Ethereum y bitcoin, incluyendo también nuevas características. Una de las aplicaciones más representativas fueron IOTA y NEO, enfocadas en proporcionar más seguridad y escalabilidad que las aplicaciones iniciales de #[i blockchain].  
                  .col-lg-7.my-3.mb-4.mb-md-0
                    img.img-a.img-t(src='@/assets/curso/temas/29.png', alt="") 

    h5(data-aos="fade-down").mb-5 Ahora, revise la siguiente línea de tiempo, la cual resume la historia del #[i blockchain]: 
    .row.justify-content-center.mb-5
      .col-lg-10
        .bg10.p-4.h-100
          LineaTiempoE.color-secundario
            div(titulo="1991 – 2008")
              p Stuar Haber y Scott Stornetta trabajan en el primer #[i blockchain]. 
            div(titulo="2009")
              p Satoshi Nakamoto lanza el whitepaper de bitcoin. 
            div(titulo="2010")
              p La primera compra de bitcoin tiene lugar 10.000 BTC.  
            div(titulo="2013")
              p El mercado de bitcoin supera los $1 mil millones. Vitalik Buterín lanza el whitepaper de Ethereum.      
            div(titulo="2014")
              p Ethereum #[i blockchain] es financiado por crowdsale. La tecnología #[i blockchain] R3 se forma e inicia un consorcio de más de 40 compañías financieras legadas para implementar la tecnología #[i blockchain].  
            div(titulo="2015")
              p El bloque Génesis de Ethereum es creado. Linux Foundation presenta hyperledger para mejorar.  
            div(titulo="2016")
              p Error en el código de Ethereum DAO explotado y atacado. 
            div(titulo="2017")
              p EOS es presentado por Blockone como un nuevo protocolo de #[i blockchain] para el despliegue de aplicaciones descentralizadas.
    
    p(data-aos="fade-down") Es así como podemos concluir que el #[i blockchain] se define como un tipo de comercio, donde interactúan criptomonedas y transacciones, aunque la realidad es que es más que un seguro sistema bancario en línea, porque permite, además, el fácil intercambio de objetos e ideas. 

    h5(data-aos="fade-down").mb-5 Sus características principales son:    

    .row.bg11.align-items-center.pt-3.mb-5
      .col-lg-12.col-12.px-lg-5.px-4.up
        .row.justify-content-center.align-items-center
          .col-md-6.col-lg-4.mb-4.mb-md-0.up.d-none.d-lg-block(data-aos="fade-right")
            img.img-a.img-t(src='@/assets/curso/temas/31.png', alt='')
          .col-md-11.col-lg-8.mb-4.mb-md-0.up(data-aos="fade-left")
            SlyderF.text-center.mb-3(columnas="col-lg-6")
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/32.png' alt='')
                h5.code2 Inmutabilidad 
                p.mb-0.code Los datos grabados en las cadenas son irreversibles.   
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/33.png' alt='')
                h5.code2 Transparencia  
                p.mb-0.code Cada uno de los bloques se pueden consultar y son visibles.     
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/34.png' alt='')
                h5.code2 Sin intermediarios 
                p.mb-0.code Se sostiene con una cantidad de computadores en el mundo, no existe ninguna entidad o empresa intermediaria.    
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/35.png' alt='')
                h5.code2 Distribuido 
                p.mb-0.code La información se transmite por un conjunto de computadores que comparten información, donde todos están de acuerdo con esta.  
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/36.png' alt='')
                h5.code2 Veloz 
                p.mb-0.code Solo se necesitan unos pocos minutos para realizar transacciones internacionales.    
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/37.png' alt='')
                h5.code2 Global 
                p.mb-0.code Solo es necesario Internet para que la información pueda ser vista. 

    p(data-aos="fade-down") Lo invitamos a consultar el siguiente video, el cual  presenta cómo funciona #[b #[i bitcoin]]: 

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-12(data-aos="fade-left")     
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

    .row.justify-content-center.mb-5           
      .col-lg-10
        .bg3.p-4.brad 
          .row.justify-content-center         
            .col-lg-9
              h5(data-aos="fade-down") A continuación, se describen unos puntos de funcionamiento del #[b #[i bitcoin]]:

              ul.lista-ul--color.fa-ul.mb-0.ms-0
                li 
                  i.fas.fa-cube.color1
                  span Los bloques pueden ser creados por cualquier persona desde su computador. 
                li 
                  i.fas.fa-cube.color1
                  span Los bloques se crean utilizando un software especial. 
                li 
                  i.fas.fa-cube.color1
                  span La capacidad de registro de un bloque está entre 2000 y 2400 transacciones. 
                li 
                  i.fas.fa-cube.color1
                  span La recompensa que gana el primero que realice la validación, es de 50 bitcoins. 
                li 
                  i.fas.fa-cube.color1
                  span Para agregar un bloque nuevo ,la persona que lo genere lo debe enviar al resto de la red. 
                li 
                  i.fas.fa-cube.color1
                  span No se pueden modificar ni borrar los bloques, estos son permanentes.                  
            .col-lg-3 
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/38.png', alt="") 

    Separador 
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.2 Aplicaciones 

    p(data-aos="fade-down").mb-5 Son muchas las aplicaciones que en la actualidad proporciona #[b #[i blockchain]], y que son utilizadas por empresas o instituciones. A continuación, se nombran unos ejemplos:       
    .row.bg11.align-items-center.pt-3.mb-5
      .col-lg-12.col-12.px-lg-5.px-4.up
        .row.justify-content-center.align-items-center          
          .col-lg-12       
            SlyderF.text-center.mb-3(columnas="col-lg-4")
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/39.png' alt='')
                h5.code2 Industria alimentaria  
                p.mb-0.code Por medio de la tecnología #[i blockchain], la industria alimentaria puede realizar un seguimiento a cada uno de los productos, partiendo desde donde nacen hasta su destino final. 
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/40.png' alt='')
                h5.code2 Sector energético  
                p.mb-0.code Por medio del #[i blockchain] se puede pensar en una red entre varias casas para vender y comprar energía.     
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/41.png' alt='')
                h5.code2 Sector bancario  
                p.mb-0.code Por medio de las criptodivisas, los bancos pueden realizar transacciones a un costo menor ,con una mayor eficiencia, segura y sin intermediarios.    
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/42.png' alt='')
                h5.code2 Agricultura   
                p.mb-0.code Al igual que la industria alimentaria, en la agricultura el #[i blockchain] se enfoca en optimizar la calidad de los alimentos, con aplicaciones que monitorean en tiempo real el estado de las hortalizas y verduras.      
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/44.png' alt='')
                h5.code2 Sector inmobiliario   
                p.mb-0.code Gracias a los contratos inteligentes, se pueden formalizar acuerdos con tal solo ingresar las condiciones y almacenarlas en #[i blockchain], una vez se cumplan las condiciones, se ejecuta el contrato de forma automática.  
              .tarjeta.bgcard.ts.h-100.p-4
                .row.justify-content-center.mb-3
                  .col-12
                    img.img-t(src='@/assets/curso/temas/45.png' alt='')
                h5.code2 Sistemas de votación   
                p.mb-0.code La aplicación de #[i blockchain] en los sistemas de votación, facilita la regulación de estas empresas norteamericanas, debido a que han utilizado estas metodologías para garantizar la votación electrónica. 

    Separador 
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.3 Desarrollos 

    p(data-aos="fade-down").mb-5 En la actualidad, existen muchos desarrollos que incorporan #[i blockchain]. Conozcamos algunos de los más novedosos:   

    .row.justify-content-center       
      .col-lg-6.my-3(data-aos="fade-left")
        .bg3.p-4.brad.h-100   
          .row.justify-content-center       
            .col-lg-auto
              img.img-t.img-a(src='@/assets/curso/temas/46.png' alt='')
            .col
              h5 IBM Food Trust
              p.mb-0 Es una plataforma de intercambio soportado en #[i blockchain] ,que favorece a los usuarios participantes de una red de alimentos para mayoristas, productores y distribuidores, la cual permite administrar datos de transacciones, procesamientos y procedencia de los alimentos, entre otros, logrando reducir la pérdida de los alimentos.      

      .col-lg-6.my-3(data-aos="fade-right")
        .bg3.p-4.brad.h-100   
          .row.justify-content-center       
            .col-lg-auto
              img.img-t.img-a(src='@/assets/curso/temas/47.png' alt='')
            .col
              h5 Pylon Network 
              p.mb-0 Desarrollado por una empresa española, permite la venta y compra de energía renovable sin intermediarios, este desarrollo lanzó su proyecto de código abierto (open-source), concretamente para las condiciones del sector energético.    

      .col-lg-6.my-3(data-aos="fade-left")
        .bg3.p-4.brad.h-100   
          .row.justify-content-center       
            .col-lg-auto
              img.img-t.img-a(src='@/assets/curso/temas/48.png' alt='')
            .col
              h5 Steemit 
              p.mb-0 Consiste en una red social no centralizada que incorpora la tecnología steemit #[i blockchain], su principal función es premiar a todos los usuarios bitcoin que estén activos, esto se consigue realizando publicaciones, comentarios, etc.      

      .col-lg-6.my-3(data-aos="fade-right")
        .bg3.p-4.brad.h-100   
          .row.justify-content-center       
            .col-lg-auto
              img.img-t.img-a(src='@/assets/curso/temas/49.png' alt='')
            .col
              h5 Koibanx 
              p.mb-0 Es una plataforma basada en #[i blockchain] para el sector financiero, que permite hacer el proceso de pagos, gestión de costos, plazos, fidelización de programas a bancos, cooperativas, fiduciarias, etc.                                               
</template>

<script>
export default {
  name: 'Tema2',
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
