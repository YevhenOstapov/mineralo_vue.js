< >
    <nuxt />
</ >


<script>

  export default {
    components: {
    },
    head(){
      return {
        title: "Mineralo - Vue Nuxt Bottled Water Delivery Service  "
      }
    },
    mounted(){
      this.$nextTick(() => {
        this.$nuxt.$loading.start()
        setTimeout(() => this.$nuxt.$loading.finish(), 500)
      })
    }
  }
</script>

<style>
</style>
