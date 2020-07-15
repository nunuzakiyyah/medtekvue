<template>
  <div class="home">
    <Header />
    <Dokter />
    <Lokasi />
     
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Dokter from '@/components/Dokter.vue'
import Lokasi from '@/components/Lokasi.vue'



export default {
  name: 'home',
  components: {
    Header,
    // carousel,
    Dokter,
    Lokasi,
  }
}
</script>


