<template>
    <section id="HomeContent">
        <div class="flex-wrap">
            <Logo/>          

            <img src="@/assets/wow1.gif" class="inline-wow">

            <h1>Upgrade your project</h1>
            <h2>Gratis design, UX, UI services</h2>
            <h3>Nodenode uses the proceeds from our block production activities to fund access to critical services that make for more attractive and usable products that run on our favorite open networks.</h3>
            <ul>
                <li>
                    <p>See our <nuxt-link to="/conduct">Code of Conduct</nuxt-link> for more information</p>
                </li>
                <li>
                    <p>View our <a href="/bp.telos.json">bp.json</a></p>
                </li>
                <li class="bp-api">
                    <p>Our peer node is <a href="https://api.nodenode.org:5357">api.nodenode.org:5357</a></p>
                </li>
            </ul>
            

            <BPNav/>
            
       </div>
    </section>
</template>

<style lang="scss">


</style>