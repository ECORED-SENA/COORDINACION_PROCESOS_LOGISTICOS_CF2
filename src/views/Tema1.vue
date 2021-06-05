<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Gestión de almacenes - Conceptos generales


    #t_1_1.titulo-segundo
      .h2 1.1 Introducción general a la gestión de almacenes

    p.mb-4 La gestión de almacenes es el proceso de la función logística que recibe, almacena, controla y mueve las diferentes mercancías dentro del almacén; permite controlar unitariamente los productos y ubicarlos correctamente para reducir al máximo las operaciones de manutención, los errores y el tiempo de dedicación. En la práctica es el conjunto de procesos que optimizan la logística, permitiendo tener la información confiable y oportuna, maximizando el tiempo de respuesta mediante la mejora continua de las técnicas de operaciones de manipulación, almacenamiento y transporte de mercadería, rapidez en entregas y con ello reducción de costos.
    p.mb-4 Por ende, teniendo en cuenta el concepto de Flamarique (2019), los procesos necesarios para llevar la gestión de almacenamiento se soportan en 5 características que se presentan a continuación:
  


    .row.justify-content-center
      .col-lg-12.align-self-center
        .tarjeta-avatar-b
          img(src='@/assets/curso/tema1/num1.svg', alt='AvatarNum')
          .tarjeta.transparent1
            .p-4
              p El rastreo sirve para identificar el origen de un lote o unidad de carga concreta. Permite explorar las etapas que ha seguido el producto desde su transformación hasta llegar a la entrega final, por lo que se incluye la identificación de las materias primas utilizadas y las operaciones de producción llevadas a cabo.

    .row.justify-content-center
      .col-lg-12.align-self-center
        .tarjeta-avatar-b
          img(src='@/assets/curso/tema1/num2.svg' alt='AvatarNum')
          .tarjeta.transparent2
            .p-4
              p Maximizar el espacio: el espacio de almacenamiento tiene un costo para la organización, normalmente elevado, por lo que hay que aprovecharlo al máximo. El objetivo es almacenar la mayor cantidad de mercancía en el mínimo espacio posible, buscando el equilibrio entre las necesidades del mercado, el tiempo de reposición del producto y la calidad del servicio. 

    .row.justify-content-center
      .col-lg-12.align-self-center
        .tarjeta-avatar-b
          img(src='@/assets/curso/tema1/num3.svg' alt='AvatarNum')
          .tarjeta.transparent2
            .p-4
              p Minimizar la manutención del producto: se trata de reducir al máximo los movimientos de las mercancías, asegurando siempre la accesibilidad a las mismas. Al limitar los movimientos al mínimo se reduce la posibilidad de accidentes y el deterioro o las roturas de los productos.

    .row.justify-content-center
      .col-lg-12.align-self-center
        .tarjeta-avatar-b
          img(src='@/assets/curso/tema1/num4.svg' alt='AvatarNum')
          .tarjeta.transparent2
            .p-4
              p Adecuación a la rotación de las existencias: se ha de ajustar la cantidad de producto disponible a la demanda del mercado y a los tiempos de aprovisionamiento. De este modo, se reduce la cantidad de mercancía almacenada y la inversión económica necesaria, con el consiguiente ahorro financiero. La adecuación a la rotación de las existencias también requiere menor espacio de almacenamiento, reduce la cantidad de productos obsoletos o caducados y exige dedicar un menor tiempo a la manutención.

    .row.justify-content-center
      .col-lg-12.align-self-center
        .tarjeta-avatar-b.mb-5
          img(src='@/assets/curso/tema1/num5.svg' alt='AvatarNum')
          .tarjeta.transparent2
            .p-4
              p Fácil acceso a las existencias: se trata de acceder directamente a la mercancía almacenada, de modo que la manutención sea mínima. Facilitar el acceso a las existencias reduce los tiempos de entrada y salida, así como los de preparación de pedidos, y evita accidentes que pueden afectar a las personas y las mercancías. Como resultado de ello, aumenta la productividad global en el almacén.


    #t_1_2.titulo-segundo
      .h2 1.2 Evolución de los almacenes

    #t_1_3.titulo-segundo
      .h2 1.3 Características de los almacenes

    #t_1_4.titulo-segundo
      .h2 1.4 Función de los almacenes

    #t_1_5.titulo-segundo
      .h2 1.5 Ubicación de los almacenes

    #t_1_6.titulo-segundo
      .h2 1.6 Distribución física y layout












  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
