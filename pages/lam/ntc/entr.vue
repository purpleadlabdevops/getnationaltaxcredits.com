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
          src: 'https://b-js.ringba.com/CA5718d7a7ff764a70bd4a3de6201b3c40'
        },
      ]
    }
  },
  mounted(){
    this.$store.commit('setPhone', '18777920179')
  },
}
</script>
