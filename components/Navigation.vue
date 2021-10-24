<template>    
    <nav class="bottom">
        <NuxtLink class="nav-item" to="/schedule" id="schedule">
            <i>
                <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15 22.5H0.5V0.5H29.5V22.5H23H22.5V23V28.8981L15.3293 22.6237L15.1879 22.5H15Z"/>
                <path d="M18 6V10.5"/>
                <path d="M24 12V16H6V12"/>
                <path d="M12 6V10.5"/>
                </svg>

            </i>
            <div>
                <div class="title">Schedule</div>
                <div class="explanation">Does your project have the right stuff?</div>
            </div>
        </NuxtLink>
        <NuxtLink class="nav-item" to="/services" id="services">
            <i>
                <svg width="32" height="33" viewBox="0 0 32 33" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M18.6514 13.2791L19.4806 13.168L18.99 12.4903C17.3765 10.2621 14.6926 7.28754 11.8859 5.66736C10.4823 4.85712 8.99138 4.35261 7.55925 4.51085C6.09631 4.6725 4.7872 5.51473 3.7561 7.20142C3.24631 8.03535 2.96924 8.80479 2.93018 9.51302C2.89043 10.234 3.09958 10.8619 3.50655 11.3869C4.29294 12.4016 5.77279 12.9776 7.43435 13.3056C10.7979 13.9694 15.4293 13.7111 18.6514 13.2791Z" stroke="black"/>
                    <path d="M20.203 12.4569L19.4368 12.7973L19.5015 11.9614C19.6852 9.58843 20.3192 6.17629 21.6549 3.70555C22.3227 2.47014 23.1973 1.41162 24.3363 0.873485C25.5039 0.321787 26.8638 0.356548 28.3902 1.14303C29.1436 1.53123 29.7016 1.98012 30.0557 2.49671C30.417 3.02361 30.5487 3.59636 30.4842 4.18191C30.3601 5.3091 29.5186 6.41503 28.4465 7.4079C26.2727 9.42101 22.7577 11.3219 20.203 12.4569Z" stroke="black"/>
                    <path d="M29.134 19.8105C28.0895 18.2094 25.8524 17.4504 23.3806 17.2515C20.8722 17.0496 17.9584 17.4086 15.3463 18.2108C12.7465 19.0092 10.3699 20.2701 9.00628 21.9302C8.3178 22.7683 7.87573 23.7237 7.81697 24.7775C7.75813 25.8329 8.08685 26.933 8.84473 28.0533C10.3588 30.2914 12.8755 31.61 15.6184 32.1732C18.3638 32.7368 21.3881 32.5565 23.9994 31.7458C26.6007 30.9383 28.8656 29.4804 29.99 27.4231C31.1363 25.3258 31.0347 22.7241 29.134 19.8105Z" stroke="black"/>
                    <path d="M18.958 13.0679C25.9958 21.1246 23.207 28.4339 20.6976 32.46"/>
                </svg>


            </i>
            <div>
                <div class="title">Services</div>
                <div class="explanation">Design, UX, product, strategy, and marketing</div>
            </div>
        </NuxtLink>
        <NuxtLink class="nav-item" to="/about" id="about">
            <i>
                <svg width="26" height="29" viewBox="0 0 26 29" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M21.1787 28.3159L21.1986 28.3231L21.219 28.3286C21.6427 28.4424 22.0692 28.5 22.4974 28.5C23.3201 28.5 24.0355 28.2431 24.604 27.7086C25.1956 27.1524 25.5 26.4553 25.5 25.6471V3.16C25.5 2.41962 25.2486 1.77552 24.7387 1.2641C24.2221 0.746062 23.5551 0.5 22.7846 0.5C22.0138 0.5 21.3404 0.74581 20.8011 1.25286L20.7952 1.25839L20.7895 1.26409C20.2796 1.77552 20.0282 2.41962 20.0282 3.16V18.366L5.98694 1.53801C5.72205 1.1883 5.33421 0.939454 4.87376 0.765487C4.4335 0.588868 3.97533 0.5 3.50256 0.5C2.67152 0.5 1.9452 0.775063 1.35495 1.33C0.784221 1.86659 0.5 2.55372 0.5 3.35286V25.84C0.5 26.5804 0.751359 27.2245 1.26133 27.7359C1.77788 28.2539 2.44492 28.5 3.21538 28.5C4.00379 28.5 4.68491 28.2597 5.20473 27.7416C5.74206 27.2337 6.01282 26.5881 6.01282 25.84V10.7455L20.1824 27.6612C20.4239 27.9613 20.7745 28.1698 21.1787 28.3159Z"/>
                </svg>

            </i>
            <div>
                <div class="title">Contributors</div>
                <div class="explanation">We’re really excited to meet you all</div>
            </div>
        </NuxtLink>
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


nav.bottom {
    flex-shrink: 0;
    display: flex;
    flex-direction: row;
    z-index:1;
    position: fixed;
    bottom:0;
    width:100%;
    z-index:1000;
    flex-direction:row;
    height:86px;
    overflow:hidden;
    border-top:1px solid rgba(255,255,255,0.09);

    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);

    .nav-item {
        width:33.3333%;
        padding:$padding-med 0 $padding-med 20px;
        transition: all .12s ease-in-out;
        display: flex;
        flex-direction: row;
        align-items:center;
        cursor: pointer;

        @media only screen and (max-width: 1000px) {
            flex-direction: column;
            padding-left:0;
        } 

        i {
            align-self:center;
            margin-right:$padding-med;
            height: 34px;

            @media only screen and (max-width: 1000px) {
                margin-right:0;
                margin-bottom:4px;
            } 

            svg, path {
                stroke:white;
            }
            
        }

        div {

            align-self:center;

            .title {
                font-family: Poppins;
                font-style: normal;
                font-size: 14px;
                line-height: 20px;
                color: white;
            }

            .explanation {
                font-family: Poppins;
                font-style: normal;
                font-weight: normal;
                font-size: 12px;
                line-height: 14px;
                color: white;
                opacity: 0.5;

                @media only screen and (max-width: 1000px) {
                    display:none;
                } 
            }
        }

        &:hover, .selected, &.nuxt-link-active {
            background:rgba(255,255,255,1);

            .title, .explanation { 
                color:black;
            }
            
            svg, path {
                stroke:black;
            }
            
        }

        &.nuxt-link-active {
            background:rgba(255,255,255,1);
        }
    }
}



</style>