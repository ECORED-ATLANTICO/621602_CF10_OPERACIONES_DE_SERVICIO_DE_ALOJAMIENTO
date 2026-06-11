<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Rates and customer transactions/ Tarifas y transacciones con clientes
  
    .container
      .row.justify-content-center.align-items-center.mb-5.bg-color-5(data-aos="fade-right")
        .col-lg-7.p-4.order-1.order-lg-2
          p.mb-3 Understanding rates and customer transactions is essential in the hospitality industry, as it enables professionals to provide accurate information, explain service options, and support guests throughout the booking and payment processes. Effective communication in these situations contributes to customer satisfaction and strengthens the quality of service provided.
          p.mb-0 Comprender las tarifas y las transacciones con los clientes es fundamental en la industria hotelera, ya que permite brindar información precisa, explicar las diferentes opciones de servicio y acompañar a los huéspedes durante los procesos de reserva y pago. Una comunicación efectiva en estas situaciones contribuye a la satisfacción del cliente y fortalece la calidad del servicio ofrecido.
        .col-lg-5.p-0.order-2.order-lg-1
          img(src="@/assets/curso/tema1/img01.png", alt="")

    .container
      .titulo-con-imagen.mb-5(data-aos="fade-right")
        .titulo-con-imagen__fondo
          img.titulo-con-imagen__imagen(src="@/assets/curso/img-subtitulo.png")
          h3.titulo-con-imagen__texto Rates / Tarifas



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-9.mb-4.mb-lg-0
        p.mb-3(data-aos="fade-right") Rates are the amounts paid by hotel guests in exchange for the products or services they receive. They are determined by the base price and other additional charges and may vary according to supply and demand conditions within the tourism market. Hotels offer different types of rates based on the needs and characteristics of the market segments they serve.
        p.mb-3(data-aos="fade-right") The following section presents some of the most common rate types used in the hospitality industry.
        p.mb-3(data-aos="fade-right") Las tarifas corresponden a los valores que pagan las personas usuarias de los servicios hoteleros a cambio de los productos o servicios recibidos. Estas se componen del precio base y de otros conceptos adicionales, y pueden variar de acuerdo con las condiciones de oferta y demanda del mercado turístico. Los establecimientos de alojamiento manejan diferentes tipos de tarifas según las necesidades y características de los segmentos de mercado a los que orientan sus servicios.
        p.mb-0(data-aos="fade-right") A continuación, se presentan algunos de los tipos de tarifas más utilizados en el sector hotelero.

      .col-lg-3.col-md-8
        figure
          img(src="@/assets/curso/tema1/img02.png", data-aos="zoom-in").mx-auto

    .bg-full-width.bg-fondo-2.tarjeta.mb-5
      .px-1.py-4.py-md-4.p-lg-4.px-lg-2(data-aos="fade-right")
        SlyderA(tipo="b").bg-color-white.p-0.p-lg-4.tarjeta
          .row.justify-content-center.align-items-center.p-4.p-lg-3
            .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0
              h4.mb-3 <em>Rack rate</em> / Tarifa rack
              p.mb-2 <em>It is the official rate charged by the hotel, to which no discount applies. It serves as a reference for rate management.</em>
              p.mb-0 Es la tarifa oficial que cobra el hotel, a la cual no se aplica ningún descuento. Sirve de referencia para el manejo de tarifas.
            .col-lg-5.col-md-8.order-2.order-lg-2
              img(src="@/assets/curso/tema1/img04.png", alt="").img-fluid.mx-auto

          .row.justify-content-center.align-items-center.p-4.p-lg-3
            .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0
              h4.mb-3 <em>Net or floor rate</em> / Tarifa neta o de piso
              p.mb-2 <em>This is the fee that is assigned to intermediaries, such as travel agencies, bed banks and marketing platforms, on which they can generate their profit or mark-up.</em>
              p.mb-0 Esta es la tarifa que se asigna a intermediarios como agencias de viaje, bancos de camas y plataformas de marketing, sobre la cual ellos pueden generar su utilidad o sobreprecio.
            .col-lg-5.col-md-8.order-2.order-lg-2
              img(src="@/assets/curso/tema1/img05.png", alt="").img-fluid.mx-auto

          .row.justify-content-center.align-items-center.p-4.p-lg-3
            .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0
              h4.mb-3 <em>Confirmed rate</em> / Tarifa confirmada
              p.mb-2 <em>It is the rate that was informed to the client at the time of booking. If when the guest arrives there is not available room according to the confirmed rate, another one of better category is usually given for the same price, which means doing an upgrade.</em>
              p.mb-0 Es la tarifa que se le informó al cliente al momento de la reserva. Si al llegar el huésped no hay disponible una habitación acorde con la tarifa confirmada, se suele dar otra de mejor categoría por el mismo precio, lo que significa hacer una mejora.
            .col-lg-5.col-md-8.order-2.order-lg-2
              img(src="@/assets/curso/tema1/img06.png", alt="").img-fluid.mx-auto

          .row.justify-content-center.align-items-center.p-4.p-lg-3
            .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0
              h4.mb-3 <em>Negotiated rate</em> / Tarifa negociada
              p.mb-2 <em>This one has a discount on the rack rate and some conditions on its granting. It usually occurs only in negotiations with companies, agencies, associations, among others, based on a minimum production of nights per month.</em>
              p.mb-0 Esta tiene un descuento sobre la tarifa rack y unas condiciones en su otorgamiento. Por lo general, se da solo en negociaciones con empresas, agencias, asociaciones, entre otras, con base en una producción mínima de noches por mes.
            .col-lg-5.col-md-8.order-2.order-lg-2
              img(src="@/assets/curso/tema1/img07.png", alt="").img-fluid.mx-auto

          .row.justify-content-center.align-items-center.p-4.p-lg-3
            .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0
              h4.mb-3 <em>Complementary</em> / Tarifa complementaria
              p.mb-2 <em>They are the rates granted to certain entities or people who represent some interest for the hotel. For example: other hotels, associations, conglomerates with defined conditions, hotel employees, friends and family, etc.</em>
              p.mb-0 Son las tarifas que se otorgan a determinadas entidades o personas que representan algún interés para el hotel. Por ejemplo: otros hoteles, asociaciones, conglomerados con condiciones delimitadas, empleados del hotel, amigos y familiares, etc.
            .col-lg-5.col-md-8.order-2.order-lg-2
              img(src="@/assets/curso/tema1/img07.png", alt="").img-fluid.mx-auto
              

    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-12
        TabsA.color-acento-botones()
          .tarjeta.color-acento-botones--borde.p-4(titulo="<em>Promotional rates</em> / Tarifas promocionales")
            p.mb-3 <em>They are discounts which are applied for hotel promotion purposes, following some policies and restrictions. Example: non-refundable rates, children under 12 do not pay, pay 3 nights and stay 4.</em>
            p.mb-0 Son los descuentos que se aplican para fines de promoción del hotel, siguiendo unas políticas y restricciones. Ejemplo: tarifas no reembolsables, menores de 12 años no pagan, pague 3 noches y hospédese 4.

          .tarjeta.color-acento-botones--borde.p-4(titulo="<em>BAR Rate</em> / Tarifa BAR")
            p.mb-3 <em>With the increase in distribution channels, there was a time when the hotelier lost control over his price. It was common to see clients arriving at the hotel who had found, through an intermediary, a lower rate than the one offered directly by the hotel. To solve this problem, strengthen direct sales, and increase rate transparency, hoteliers began to publish the BAR (Best Available Rate) on their websites. The Best Available Rate guarantees that a lower rate will not be found in any distribution channel. The management of this type of rate is not only about price, but also about the value of the rate.</em>
            p.mb-0 Con el aumento de los canales de distribución, hubo un momento en que el hotelero perdió el control sobre su precio. Era usual que llegaran clientes al hotel que habían encontrado, a través de un intermediario, una tarifa inferior que la ofrecida directamente por el hotel. Para dar solución a esta problemática, fortalecer la venta directa y aumentar la transparencia de las tarifas, los hoteleros comenzaron a publicar en sus webs la BAR (Best Available Rate, en inglés). La mejor tarifa disponible garantiza que no se va a encontrar una tarifa inferior en ningún canal de distribución. El manejo de este tipo de tarifas no tiene que ver solo con precio, sino con el valor de la tarifa.

          .tarjeta.color-acento-botones--borde.p-4(titulo="<em>Group rates</em> / Tarifa grupo o evento")
            p.mb-3 <em>These rates are created based on availability and market conditions at the time the quote is requested. And they apply to groups or special events, for example, fairs, concerts, congresses.</em>
            p.mb-0 Estas tarifas se crean con base en la disponibilidad y las condiciones de mercado del momento en que se pide la cotización. Y aplican para grupos o eventos especiales, por ejemplo, ferias, conciertos, congresos.

          .tarjeta.color-acento-botones--borde.p-4(titulo="<em>Long stay rate</em> / Tarifa larga estadía")
            p.mb-3 <em>It applies for a minimum number of nights a month. With some frequency, there are people who decide to live in hotels, due to the advantages that this provides them, and are classified as permanent guests.</em>
            p.mb-0 Aplica para un número mínimo de noches al mes. Con alguna frecuencia, hay personas que deciden vivir en hoteles, debido a las ventajas que ello les proporciona, y se catalogan como huéspedes permanentes.

          .tarjeta.color-acento-botones--borde.p-4(titulo="<em>Packages or plans</em> / Paquetes o planes")
            p.mb-3 <em>Packages are a way to market hotel products, to provide customers with more services, for more attractive prices. It can be packaged with own or third-party products. Example: wedding night plan, package with food and tour included.</em>
            p.mb-0 Los paquetes son una forma de comercializar productos hoteleros, para brindar a los clientes más servicios, por precios más atractivos. Se puede empaquetar con productos propios o de terceros. Ejemplo: plan noche de bodas, paquete con alimentación y excursiones incluidas.


    
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5.mb-4.mb-lg-0.col-md-12.order-2.order-lg-1
        .bg-color-5.p-4.br-15.mb-0(data-aos="fade-right")
          h5.mb-3 <em>Many elements influence the rate setup:</em>
          ul.lista-ul
            li
              i.lista-ul__vineta
              span <em>Hotel category.</em>
            li
              i.lista-ul__vineta
              span <em>Type of hotel.</em>
            li
              i.lista-ul__vineta
              span <em>Season.</em>
            li
              i.lista-ul__vineta
              span <em>Day of the week.</em>
            li
              i.lista-ul__vineta
              span <em>Stay Length.</em>
            li
              i.lista-ul__vineta
              span <em>Hotel location.</em>
            li
              i.lista-ul__vineta
              span <em>Location within the hotel.</em>
            li
              i.lista-ul__vineta
              span <em>Room type.</em>
            li
              i.lista-ul__vineta
              span <em>Meal plan.</em>
            li
              i.lista-ul__vineta
              span <em>Discounts.</em>
            li
              i.lista-ul__vineta
              span <em>Individual or group client.</em>

      .col-lg-2.col-md-4.mb-4.mb-lg-0.order-1.order-lg-2.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema1/img08.png", alt="").img-fluid.mx-auto

      .col-lg-5.col-md-12.order-3.order-lg-3
        .bg-color-24.p-4.br-15.mb-0(data-aos="fade-left")
          h5.mb-3 Muchos elementos influyen en la configuración de las tarifas:
          ul.lista-ul
            li
              i.lista-ul__vineta
              span Categoría del hotel.
            li
              i.lista-ul__vineta
              span Tipo de hotel.
            li
              i.lista-ul__vineta
              span Temporada.
            li
              i.lista-ul__vineta
              span Día de la semana.
            li
              i.lista-ul__vineta
              span Duración de la estancia.
            li
              i.lista-ul__vineta
              span Ubicación del hotel.
            li
              i.lista-ul__vineta
              span Ubicación dentro del hotel.
            li
              i.lista-ul__vineta
              span Tipo de habitación.
            li
              i.lista-ul__vineta
              span Plan de comidas.
            li
              i.lista-ul__vineta
              span Descuentos.
            li
              i.lista-ul__vineta
              span Cliente individual o grupal.


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-3.col-md-8.mb-4.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/img09.png", data-aos="zoom-in").mx-auto

      .col-lg-9
        h4.mb-3 <em>Meal plans</em> / Planes de alimentación
        p.mb-3(data-aos="fade-right") <em>Hotels offer plans beside to the accommodation, with the purpose of promoting the second line of the hotel industry, which is the sale of food and beverage services.</em>
        p.mb-3(data-aos="fade-right") Los hoteles ofrecen planes junto al alojamiento con el propósito de promover el segundo renglón de la industria hotelera, que es la venta de servicios de alimentos y bebidas.
        p.mb-3(data-aos="fade-right") <em>Generally, hotels offer the client several plans that are determined by the basic price of the room and the most suitable food option for the client.</em>
        p.mb-0(data-aos="fade-right") Generalmente, los hoteles ponen a disposición del cliente varios planes, que están determinados por el precio básico de la habitación y la opción de alimentación más adecuada para el cliente.

    p.mb-5 <em>There are different types of plans</em> / Existen diferentes tipos de planes

    .container
      .titulo-con-imagen.mb-5(data-aos="fade-right")
        .titulo-con-imagen__fondo
          img.titulo-con-imagen__imagen(src="@/assets/curso/img-subtitulo.png")
          h3.titulo-con-imagen__texto <em>Discounts</em> / Descuentos
    
    p.mb-4(data-aos="fade-right") <em>Discounts are a way of promotion. Through this practice, among other things, the hotels can:</em>

    .row.mb-4.justify-content-center.align-items-center
      .col-lg-9.mb-4.mb-lg-0
        .bg-fondo-3.px-lg-4.py-lg-3.px-4.py-3.br-15.mb-3
          ul.lista-ul
            li
              i.lista-ul__vineta
              span <em>Promote the Brand.</em>
            li
              i.lista-ul__vineta
              span <em>Increase the frequency of purchase.</em>
            li
              i.lista-ul__vineta
              span <em>Increase sales at certain times.</em>
            li
              i.lista-ul__vineta
              span <em>Increase revenue at peak times.</em>

          p.mb-0 <em>Normally, to access a discount, the client must comply with some rules, which are known as “Terms and conditions”.</em>

        p.mb-3 <em>In the market you can find different types of discounts:</em>
    
        .row.justify-content-center
          .col-xl-6.col-md-6.col-12.mb-3
            .tarjeta-avatar-b(data-aos="zoom-in").h-100
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/tema1/img17.svg' alt='AvatarTop')
              .tarjeta.bg-color-24.align-content-center
                .p-3
                  p.mb-0 <b><em>Promotional codes: </em></b><em>these are codes made up of numbers or letters and that when applied to payment generate a reduction in value. Example: “GET10”. The instruction would show something like: “By entering the code, get a 10 % discount on selected items.”</em>

          .col-xl-6.col-md-6.col-12.mb-3
            .tarjeta-avatar-b(data-aos="zoom-in").h-100
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/tema1/img18.svg' alt='AvatarTop')
              .tarjeta.bg-color-24.align-content-center
                .p-3
                  p.mb-0 <b><em>Discount plans: </em></b><em>here the discount promotes packaged products: Stay 3 nights x $300 and get all meals for free.</em>

      .col-lg-3.col-md-8
        figure
          img(src="@/assets/curso/tema1/img21.png", data-aos="zoom-in").mx-auto


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.mb-0.mb-lg-0
        .row.justify-content-center
          .col-xl-5.col-md-6.col-12.mb-3
            .tarjeta-avatar-b(data-aos="zoom-in").h-100
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/tema1/img19.svg' alt='AvatarTop')
              .tarjeta.bg-color-24.align-content-center
                .p-3
                  p.mb-0 <b><em>Discounts on nights: </em></b><em>this type of discount is intended to increase occupancy on dates with low demand: Pay 3 nights’ accommodation and get the fourth night for free.</em>

          .col-xl-7.col-md-6.col-12.mb-3
            .tarjeta-avatar-b(data-aos="zoom-in").h-100
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/tema1/img20.svg' alt='AvatarTop')
              .tarjeta.bg-color-24.align-content-center
                .p-3
                  p.mb-0 <b><em>Direct discounts: </em></b><em>this type of discount uses the strategy of showing the discount and the original price crossed out, to give the customer the perception that they are benefiting. Before $ 250,000 - Today $ 187,500. Save 25 %.</em>

    p.mb-5 Los descuentos son una forma de promoción. Por medio de esta práctica, se logra, entre otras cosas:

    .bloque-texto-g.bloque-texto-g--inverso.bg-color-2.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img22.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        ul.lista-ul.mb-3
          li
            i.lista-ul__vineta
            span Promover la marca.
          li
            i.lista-ul__vineta
            span Aumentar la frecuencia de compra.
          li
            i.lista-ul__vineta
            span Aumentar las ventas en momentos determinados.
          li
            i.lista-ul__vineta
            span Aumentar los ingresos en los momentos pico.
        p.mb-2 Normalmente, para acceder a un descuento, el cliente debe cumplir unas reglas, que se conocen como “Términos y condiciones”. <br>
        p.mb-0 En el mercado, se pueden encontrar diferentes tipos de descuentos:



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
