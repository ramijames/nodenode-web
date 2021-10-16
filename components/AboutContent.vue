<template>
    <section id="AboutContent">
        <div class="flex-wrap">
            <Logo/>

            <img src="@/assets/4Th1.gif" class="inline-wow">
            <h1>Your available talent</h1>
            <h2>We are starting small and will be expanding the team of experienced minds as the project grows.</h2>
            <ul>
                <li><strong>Rami James</strong> - Scatter, Ultra, Telos</li>
                <li><strong>Felipe Faria</strong> - EOS Rio, Ultra, The Sandbox</li>
            </ul>
       </div>
    </section>
</template>

<style lang="scss">

#AboutContent {
    ul {
        margin:0;
        padding:20px 0;

        li {
            font-family: 'Poppins';
            font-size:24px;
            font-weight:100;
            list-style:none;
            padding:5px 0;
            color:rgba(255,255,255,0.4);

            strong {
                color:rgba(255,255,255,1);
            }
        }
    }
}

</style>