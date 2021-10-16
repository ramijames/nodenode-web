<template>
    <section id="ServicesContent">
        <div class="flex-wrap">
            <Logo/>

            <img src="@/assets/wow2.webp" class="inline-wow">

            <h1>Our service to the network</h1>
           <h3>Currently, we are providing these services to qualifying projects.</h3>
           <table>
               <tr>
                   <td>
                        <nuxt-link to="/schedule">
                            <h2>Design ➝</h2>
                            <p>Your UX is solid, but you need a more unique face</p>
                        </nuxt-link>
                   </td>
                   <td>
                        <nuxt-link to="/schedule">
                            <h2>Branding ➝</h2>
                            <p>Your idea is amazing, but your project needs name recognition</p>
                        </nuxt-link>
                   </td>
               </tr>
               <tr>
                   <td>
                        <nuxt-link to="/schedule">
                            <h2>User Experience ➝</h2>
                            <p>Your code is great, but nobody can figure out what to do</p>
                        </nuxt-link>
                   </td>
                   <td>
                        <nuxt-link to="/schedule">
                            <h2>Product Marketing ➝</h2>
                            <p>You're ready, but the market doesn't know it</p>
                        </nuxt-link>
                   </td>
               </tr>
           </table>
       </div>
    </section>
</template>

<style lang="scss"></style>