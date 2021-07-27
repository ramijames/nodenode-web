<template>
    <div class="fullscreen-bg">
    <video loop muted autoplay poster="@/assets/fakurian-design-u8Jn2rzYIps-unsplash.jpg" class="fullscreen-bg__video">
        <source src="@/assets/33177417_4k-abstract-black-hole-background_by_beratturan_preview.mp4" type="video/mp4">
    </video>
</div>
</template>

<script type="text/javascript">

export default {
        name: 'BgVideo',
        head () {
          return {
            title: '',
            meta: [
              { 
                hid: 'description', 
                name: 'description', 
                content: 'BgVideo'
              }
            ]
          }
        }
    }

</script>

<style lang="scss">

.fullscreen-bg {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    overflow: hidden;
    z-index: -100;
}

.fullscreen-bg__video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>