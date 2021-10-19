<template>    
    <nav></nav>
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

@keyframes grow {
  from {
    top:44px;
  }
  to {
    top:0;
  }
}

nav.bp {
    border:1px solid rgba(255,255,255,0.1);
    display: flex;
    flex-direction: row;
    backdrop-filter: blur(34px);
    overflow:hidden;
    justify-content:space-between;
    align-items:center;
    padding: 10px $padding-med;
    font-size:12px;
    animation-name: grow;
    animation-duration: 0.25s;
    animation-timing-function: ease-in-out;
    position:relative;
    z-index:0;
    font-family: Poppins;
    margin-top:20px;

    .bp-api {
        color: rgba(255, 255, 255, 1);
        width:50%;  

        .bp-pill {
            color: black;
            background-color:white;
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