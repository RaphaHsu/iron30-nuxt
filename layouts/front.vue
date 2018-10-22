<template>
  <div>
    <Header/>
    <nuxt/>
    <Footer/>
  </div>
</template>

<script>
    import Header from '~/components/partial/_header.vue'
    import Footer from '~/components/partial/_footer.vue'

    export default {
        components: {
            Header,
            Footer
        }
    }
</script>

