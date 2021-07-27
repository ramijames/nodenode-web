<template>    
    <nav class="bp">
        <section class="bp-api">
            <span class="bp-pill">API</span>
            api.nodenode.org:5357
        </section>
        <a class="bp-json" href="#">
            View our bp.json 
            <svg width="6" height="12" viewBox="0 0 9 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1 14L8 7.5L0.999999 1" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </a>
    </nav>
</template>

<script>
    export default {
        data() {
            return {
            }
        }
    }
</script>

<style lang="scss">

@import "@/assets/scss/_variables.scss";

nav.bp {
    position: absolute;
    right:20px;
    height: 52px;
    left: 20px;
    bottom:102px;
    background: rgba(0, 0, 0, 0.3);
    backdrop-filter: blur(74px);
    display: flex;
    flex-direction: row;
    backdrop-filter: blur(34px);
    overflow:hidden;
    justify-content:space-between;
    align-items:center;
    padding: 0 $padding-med;
    font-size:12px;

    .bp-api {
        color: rgba(255, 255, 255, 0.5);

        .bp-pill {
            color: rgba(255, 255, 255, 0.5);
            background-color:black;
            padding:3px 6px;
            font-size:9px;
            font-weight:bold;
            border-radius:20px;
            margin-right:5px;
        }
    }

    .bp-json {
        color:white;
        padding:4px 8px;
        
        svg {
            margin-left:10px;
        }

        &:hover {
            padding:4px 12px;
        }
       
    }
    
}

</style>