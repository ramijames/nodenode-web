<template>
  <div id="Schedule">
    <div class="wrap-content">
        <ScheduleContent/>
    </div>
    <section class="sub-nav">
        <NuxtLink class="back" to="/">
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <circle cx="16" cy="16" r="16" fill="black" fill-opacity="0.5"/>
                <path d="M18 10L11 16.5L18 23" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            Back
        </NuxtLink>
        <section class="button-group">
            <span class="info">
                Opens Calendly
            </span>
            <a class="button">
                Schedule Now
            </a>
        </section>
    </section>
    
    <Navigation/>
  </div>
</template>

<style lang="scss">
    #Schedule {
        width:100%;
        height:100%;
    }
</style>