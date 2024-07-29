<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-md-0
  
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.bgi.align-items-center
      .col-lg-12.col-12.px-lg-5.px-4.pb-4 
        .row.justify-content-center.align-items-center          
          .col-lg-12  
            .row.justify-content-center.bg1.brad.p-3.mb-5          
              .col-lg-8.my-3
                p(data-aos="fade-down") Las tecnologías emergentes o disruptivas facilitan la creación de un marco de innovación que es aprovechado por organizaciones para la creación de nuevos servicios y productos. La palabra disruptiva viene del francés y se refiere a un cambio concluyente o violento. Es así como cada tecnología que genera transformaciones intensas en los conocimientos de productos o servicios, es una tecnología disruptiva. 

                p(data-aos="fade-down").mb-0 A medida que avanza el tiempo, avanzan también las innovaciones tecnológicas y surgen nuevos términos utilizados para distinguir la convergencia y emergencia de nuevas tecnologías, con potencial suficiente para manifestarse como tecnologías disruptivas.                   
              .col-lg-4.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/2.png', alt='') 

            .row.justify-content-center
              .col-lg-4.my-3
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/3.png', alt='')                          
              .col-lg-8.my-3
                p(data-aos="fade-down") Es muy importante reconocer las tendencias que pueden encaminar las innovaciones o condiciones de vida en los siguientes años, en la actualidad, hay muchas que son consideradas tecnologías emergentes y disruptivas, las cuales se estudiarán en el presente componente formativo. 

                h5(data-aos="fade-down").mb-0 Le deseamos muchos éxitos en este proceso de aprendizaje.               
              


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
