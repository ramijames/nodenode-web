<template>
    <section id="HomeContent" class="content">
                      
        <video autoplay muted loop id="bg">
          <source src="@/assets/bg-480p.mp4" type="video/mp4">
        </video>

        <h1>Upgrade your project</h1>
        <h2>Gratis design, UX, UI services</h2>
        <h3>Nodenode uses the proceeds from our block production activities to fund access to critical services that make for more attractive and usable products that run on our favorite open networks.</h3>
        <div class="options">
            <nuxt-link to="/conduct">Code of Conduct ↦</nuxt-link>
            <a href="/bp.telos.json">BP Config ↦</a>
        </div>
            
    </section>
</template>

<style lang="scss">

.options {
    display:flex;
    flex-direction:row;
    padding:0;
    margin:0;
    list-style:none;

    a {
        width:160px;
        margin-right:20px;
        padding:120px 40px 20px 20px;
        font-family: Poppins;
        color: #ffffff;
        cursor: pointer;
        border-bottom:6px solid white;
        background: rgba(255,255,255,0.06);
        border-radius: 4px;
        -webkit-backdrop-filter: blur(8px);
        backdrop-filter: blur(8px);
        box-shadow:0 10px 10px rgba(0,0,0,0.32);

        &:hover {
            background: rgba(255,255,255,0.16);
        }

    }
}

</style>