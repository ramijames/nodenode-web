<template>
  <div id="Conduct">
    <div class="wrap-content">
        <ConductContent/>
    </div>
    <section class="sub-nav">
        <NuxtLink class="back" to="/">
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <circle cx="16" cy="16" r="16" fill="white" fill-opacity="1"/>
                <path d="M18 10L11 16.5L18 23" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            Home
        </NuxtLink>
    </section>
    <Navigation/>
  </div>
</template>

<style lang="scss">
    #Conduct {
        display:flex;
        flex-direction:column;
        height: 100%;
    }
</style>