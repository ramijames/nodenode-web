<template>
    <section id="ServicesContent">
        <div class="flex-wrap">
            <Logo/>

            <img src="@/assets/wow2.webp" class="inline-wow">

            <h1>Our service to the network</h1>
            <h2>Currently, we are providing these services to qualifying projects.</h2>

            <ul id="service-list">
                <li>
                    <section>
                        <h3><strong>Design</strong></h3>
                        <p>Your UX is solid, but you need a more unique face</p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Branding</strong></h3>
                        <p>Your idea is amazing, but your project needs name recognition</p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Experience</strong></h3>
                        <p>Your code is great, but nobody can figure out what to do</p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Product</strong></h3>
                        <p>You're ready, but the market doesn't know it</p>
                    </section>
                </li>
            </ul>
       </div>
    </section>
</template>

<style lang="scss">
    
    ul#service-list {
        margin:0;
        padding:0;
        list-style:none;
        display:flex;
        flex-direction:row;

        @media only screen and (max-width: 800px) {
            flex-direction:column;
        }

        li {
            font-family: 'Poppins';
            font-weight:100;
            list-style:none;
            padding:20px 40px 0 0;
            color:rgba(255,255,255,0.4);
            display:flex;
            align-items:flex-start;

            section {
                display:flex;
                flex-direction:column;
                justify-content:flex-start;

                h3 {
                    margin-bottom:0px;
                }
            }

            svg {
                margin-right:20px;
            }

            strong {
                color:rgba(255,255,255,1);
            }
        }
    }

</style>