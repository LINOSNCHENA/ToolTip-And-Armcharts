<template>
      <div>
      <h1>2- Nuxt-Vue Plugins</h1>
      <button v-tooltip.top-center="msg">Hover me</button>
    </div>
</template>

<script>
export default {
  data(){
    return {
      msg: 'Pemba Vue tooltip plugin Choma'
    }
  },
}
</script>