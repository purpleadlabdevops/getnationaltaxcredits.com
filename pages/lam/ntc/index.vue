<template>
  <div>
    <LAMTop />
    <LAMSection1 />
    <LAMReviews />
    <LAMSection2 />
    <LAMSection3 />
    <LAMSection4 />
    <LAMSection5 />
    <LAMSection6 />
    <LAMSection7 />
    <LAMFaq />
  </div>
</template>

<script>
export default {
  layout: 'lam',
  head() {
    return {
      script: [
        {
          ssr: false,
          async: true,
          src: 'https://b-js.ringba.com/CA1349bcc1652d44cdb86bcb9d9c2c5ac9'
        },
      ]
    }
  },
  mounted(){
    this.$store.commit('setPhone', '18557132954')
  }
}
</script>
