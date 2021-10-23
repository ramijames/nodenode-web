<template>
    <section id="ServicesContent">
        <div class="flex-wrap">
            <Logo/>

            <img src="@/assets/wow2.webp" class="inline-wow">

            <h1>Improvement services for open networks</h1>
            <h2>Currently, we are providing these services to qualifying projects.</h2>

            <ul id="service-list">
                <li>
                    <section>
                        <h3><strong>Design</strong></h3>
                        <p>Your UX is solid, but you need a more unique face. We are here to help unify the ecosystem into one which is visually exciting and understandable.</p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Branding</strong></h3>
                        <p>Your idea is amazing, but your project needs name recognition to succeed. A solid brand has been proven time and again to create loyalty. </p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Experience</strong></h3>
                        <p>Your code is great, but nobody can figure out what to do. We are here to help identify core functionality and create the shortest path to its use. Your user's experience should be pleasant and exhilarating.</p>
                    </section>
                </li>
                <li>
                    <section>
                        <h3><strong>Market</strong></h3>
                        <p>You're ready, but the market doesn't know it. We can help evangelize your cause, so that the users who need it most know about your digital revolution.</p>
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
            width:25%;

            @media only screen and (max-width: 800px) {
                width:100%;
            }

            p {
                padding: 0 20px;
                border-left:1px solid white;
            }

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