<template>
<Navbar />
 <Corpo />
 <Footer />
</template>

<script>
import Navbar from '../src/components/Navbar.vue'
import Corpo from '../src/components/Corpo.vue'
import Footer from '../src/components/Footer.vue'
export default {
    name: 'Home',
    components: {
    Navbar,
    Corpo,
    Footer,
  }
}

</script>

<style>

</style>
>