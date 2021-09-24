<template>
    <section id="HomeContent">
        <div class="flex-wrap">
            <Logo/>
            <h1>Free, high-quality services to make our networks the best they can be</h1>
            <h3>Nodenode uses the proceeds from our block production activities to fund access to critical services that make for more attractive and usable products that run on our favorite open networks.</h3>
            <img src="@/assets/woosh.svg" class="woosh" preserveAspectRatio="none" />


       </div>
    </section>
</template>

<style lang="scss">

#HomeContent {
    .woosh {
        height:120%;
        width:50%;
        position:absolute;
        right:0;
        mix-blend-mode: overlay;
    }
}

</style>