<template>
    <section id="ServicesContent">
        <div class="flex-wrap">
            <Logo/>

            <img src="@/assets/wow2.webp" class="inline-wow">

            <h1>Our service to the network</h1>
            <h2>Currently, we are providing these services to qualifying projects.</h2>
            <table>
               <tr>
                   <td>
                        <nuxt-link to="/schedule">
                            <p><strong>Design ➝</strong></p>
                            <p>Your UX is solid, but you need a more unique face</p>
                        </nuxt-link>
                   </td>
                   <td>
                        <nuxt-link to="/schedule">
                            <p><strong>Branding ➝</strong></p>
                            <p>Your idea is amazing, but your project needs name recognition</p>
                        </nuxt-link>
                   </td>
               </tr>
               <tr>
                   <td>
                        <nuxt-link to="/schedule">
                            <p><strong>User Experience ➝</strong></p>
                            <p>Your code is great, but nobody can figure out what to do</p>
                        </nuxt-link>
                   </td>
                   <td>
                        <nuxt-link to="/schedule">
                            <p><strong>Product Marketing ➝</strong></p>
                            <p>You're ready, but the market doesn't know it</p>
                        </nuxt-link>
                   </td>
               </tr>
           </table>
       </div>
    </section>
</template>

<style lang="scss"></style>