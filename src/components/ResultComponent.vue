<template>
  <div class="ResultComponent">
    <button
      @click="getPicture"
      class="btn btn-primary"
    >
      Click on me to get a picture
    </button>
  </div>
</template>

<script>
export default {
  name: 'ResultCompontent',
  setup () {
    return {
      getPicture () {
        pictureService.getPicture()
      }
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
