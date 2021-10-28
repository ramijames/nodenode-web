<template>
    <section id="ScheduleContent" class="content">

            <video autoplay muted loop id="bg">
              <source src="@/assets/bg-480p.mp4" type="video/mp4">
            </video>

            <h1>Schedule a free consultation</h1>
            <h2>Let’s start with an introductory call.</h2>
            <h3>As our resources are limited, we must carefully select which projects we partner with. Our criteria for acceptance are decided by the larger impact on the Telos ecosystem, user growth potential, and project complexity.</h3>

            <vue-calendly url="https://calendly.com/rami-james" :height="660"></vue-calendly>
    </section>
</template>

<script>

export default {

}

</script>

<style lang="scss">

</style>