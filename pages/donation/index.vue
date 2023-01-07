<template>
  <div>
    <Hero
      title='Donation'
      sub-title='We are glad that you have chosen to support TCF and its projects financially. Your trust and your observation of our activities are the most precious assets we have.You may either support TCF as a whole organization or specify which projects you want to support. Our ideal is to have as many monthly contributors as possible regardless of the size of their contribution but of course other types of contribution are very welcome.You can donate by sending money to our bank account or via PayPal.'
    />
    <div class='container mx-auto px-4 text-center pb-12'>
      <p class='text-xl font-medium'>
        Transnational Community Federation e. V.<br>
        IBAN: DE93 4306 0967 1265 8150 00<br>
        BIC: GENODEM1GLS<br>
        Our bank’s webpage: <a href='https://gls.de'>https://gls.de</a><br>
        To donate via PayPal please click on the image below:
      </p>
      <img src='~assets/images/qrCode.png' class='mx-auto mt-6'/>
      <p class='mt-6 text-xl font-medium'>
        Or go to this link: Individual projects or the entire organisation <br>
        Bitcoin:<br>
        bc1qkufpj9ka6ggqqya6ykypn3ejcnau2wk3ywvnl2<br>
        ETH:<br>
        0x9f6a4D8B1688321e629dFFae13D6fe2455BE2DE4<br>
      </p>
    </div>
  </div>
</template>
<script>
  import Hero from '../../components/sections/Hero'
  export default {
    name: 'Donation',
    components: { Hero }
  }
</script>
