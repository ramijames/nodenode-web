<template>    
    <nav class="global">
        <NuxtLink class="nav-item" to="/schedule" id="schedule">
            <i>
                <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0 0H30V23H23V30L15 23H0V0Z" fill="black"/>
                    <path d="M18 6V10.5" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M24 12V13C24 14.6569 22.6569 16 21 16H9C7.34315 16 6 14.6569 6 13V12" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M12 6V10.5" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </i>
            <div>
                <div class="title">Schedule a free consultation</div>
                <div class="explanation">Does your project have the right stuff?</div>
            </div>
        </NuxtLink>
        <!-- NuxtLink class="nav-item" to="/initiative" id="initiative">
            <i>
                <svg width="34" height="36" viewBox="0 0 34 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect y="26" width="30" height="10" fill="black" fill-opacity="0.5"/>
                    <path d="M0 27C0 26.4477 0.447715 26 1 26H29C29.5523 26 30 26.4477 30 27V29H0V27Z" fill="black"/>
                    <mask id="path-3-outside-1" maskUnits="userSpaceOnUse" x="3.35669" y="-0.625122" width="31" height="33" fill="black">
                    <rect fill="white" x="3.35669" y="-0.625122" width="31" height="33"/>
                    <path d="M15.8227 3.3748C16.3579 2.40854 17.5589 2.08696 18.5053 2.65653L30.5262 9.89107C31.4726 10.4606 31.806 11.7057 31.2708 12.6719L22.0601 29.3017C21.525 30.2679 20.3239 30.5895 19.3775 30.02L7.35662 22.7854C6.41023 22.2158 6.07687 20.9708 6.61205 20.0046L15.8227 3.3748Z"/>
                    </mask>
                    <path d="M15.8227 3.3748C16.3579 2.40854 17.5589 2.08696 18.5053 2.65653L30.5262 9.89107C31.4726 10.4606 31.806 11.7057 31.2708 12.6719L22.0601 29.3017C21.525 30.2679 20.3239 30.5895 19.3775 30.02L7.35662 22.7854C6.41023 22.2158 6.07687 20.9708 6.61205 20.0046L15.8227 3.3748Z" fill="black"/>
                    <path d="M7.35662 22.7854L8.38792 21.0718L7.35662 22.7854ZM6.61205 20.0046L8.36162 20.9736L6.61205 20.0046ZM22.0601 29.3017L20.3106 28.3327L22.0601 29.3017ZM19.3775 30.02L18.3462 31.7336L19.3775 30.02ZM30.5262 9.89107L29.4949 11.6047L30.5262 9.89107ZM31.2708 12.6719L33.0204 13.641L31.2708 12.6719ZM18.5053 2.65653L19.5366 0.942933L18.5053 2.65653ZM15.8227 3.3748L14.0731 2.40578L15.8227 3.3748ZM17.474 4.37013L29.4949 11.6047L31.5575 8.17747L19.5366 0.942933L17.474 4.37013ZM29.5212 11.7029L20.3106 28.3327L23.8097 30.2707L33.0204 13.641L29.5212 11.7029ZM20.4088 28.3064L8.38792 21.0718L6.32533 24.499L18.3462 31.7336L20.4088 28.3064ZM8.36162 20.9736L17.5723 4.34383L14.0731 2.40578L4.86248 19.0355L8.36162 20.9736ZM8.38792 21.0718C8.38483 21.07 8.36962 21.0598 8.36069 21.0265C8.35177 20.9931 8.35987 20.9767 8.36162 20.9736L4.86248 19.0355C3.80568 20.9436 4.45651 23.3743 6.32533 24.499L8.38792 21.0718ZM20.3106 28.3327C20.3088 28.3359 20.312 28.3294 20.3228 28.3211C20.3324 28.3137 20.3437 28.308 20.3558 28.3048C20.3678 28.3016 20.3804 28.3008 20.3925 28.3024C20.4059 28.3043 20.412 28.3083 20.4088 28.3064L18.3462 31.7336C20.2632 32.8872 22.7257 32.2279 23.8097 30.2707L20.3106 28.3327ZM29.4949 11.6047C29.498 11.6065 29.5132 11.6167 29.5221 11.65C29.5311 11.6834 29.523 11.6998 29.5212 11.7029L33.0204 13.641C34.0772 11.7329 33.4263 9.30218 31.5575 8.17747L29.4949 11.6047ZM19.5366 0.942933C17.6197 -0.210741 15.1571 0.448596 14.0731 2.40578L17.5723 4.34383C17.5741 4.3406 17.5708 4.34706 17.5601 4.35537C17.5504 4.36284 17.5391 4.36846 17.5271 4.37168C17.5151 4.3749 17.5024 4.3757 17.4903 4.37404C17.4769 4.3722 17.4709 4.36823 17.474 4.37013L19.5366 0.942933Z" fill="white" mask="url(#path-3-outside-1)"/>
                    <path d="M15.9404 14.8919L16.2544 17.1071C16.3463 17.7553 17.026 18.1419 17.6301 17.8894L24.1935 15.1468" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>

            </i>
            <div>
                <div class="title">Support the initiative</div>
                <div class="explanation">Your votes help fund access</div>
            </div>
        </NuxtLink -->
        <NuxtLink class="nav-item" to="/services" id="services">
            <i>
                <svg width="27" height="34" viewBox="0 0 27 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M18.585 10.7836C14.8966 5.72664 6.33663 -2.52598 1.60426 4.91897C-3.12811 12.3639 10.9529 11.9308 18.585 10.7836Z" fill="black"/>
                    <path opacity="0.6" d="M24.3941 0.587501C19.3564 -2.00817 17.1075 4.55732 16.4187 9.33558C16.3107 10.0851 17.0717 10.6228 17.7506 10.2873C22.8303 7.77709 29.5194 3.22833 24.3941 0.587501Z" fill="black"/>
                    <path d="M22.7152 22.0838C19.0727 16.5 -2.41591 21.3848 3.25886 29.7732C8.93364 38.1617 30.0114 33.2685 22.7152 22.0838Z" fill="black" fill-opacity="0.5"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M23.935 28.3171C24.0626 27.9471 23.909 27.545 23.58 27.333C23.572 27.3278 23.564 27.3226 23.5559 27.3175C22.7499 26.801 21.685 26.5243 20.6972 26.3527C19.6486 26.1706 18.4306 26.0667 17.1504 26.0236C14.5876 25.9374 11.6193 26.0904 8.95338 26.4326C6.85808 26.7016 4.77155 27.1083 3.19895 27.6877C2.74854 27.8536 2.51124 28.3441 2.705 28.7833C2.84799 29.1073 3.03161 29.4375 3.25874 29.7732C3.2741 29.7959 3.30187 29.8049 3.32683 29.7935C7.42875 27.9306 19.7902 27.2799 22.4769 29.0015C22.928 29.2905 23.5652 29.2101 23.7787 28.7187C23.836 28.587 23.8881 28.4532 23.935 28.3171ZM12.8135 33.9997C13.0145 33.9988 13.2154 33.9966 13.4161 33.9928C13.2153 33.9986 13.0144 34.0009 12.8135 33.9997Z" fill="black"/>
                    <path d="M16.2329 10C26.8814 17.5556 21.0731 23.6944 16.2329 27" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>

            </i>
            <div>
                <div class="title">Hear about how we help you</div>
                <div class="explanation">Design, UX, product, strategy, and marketing</div>
            </div>
        </NuxtLink>
        <NuxtLink class="nav-item" to="/about" id="about">
            <i>
                <svg width="30" height="19" viewBox="0 0 30 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path opacity="0.2" d="M28.4795 0C28.93 0 29.296 0.138936 29.5776 0.416808C29.8591 0.694678 29.9999 1.04202 29.9999 1.45882V16.6462C29.9999 17.0978 29.831 17.4798 29.4931 17.7924C29.174 18.0877 28.7705 18.2353 28.2824 18.2353C28.0197 18.2353 27.7569 18.2006 27.4941 18.1311C27.2501 18.0443 27.0718 17.9314 26.9592 17.7924L16.6263 5.65294V16.7765C16.6263 17.1933 16.4762 17.5406 16.1759 17.8185C15.8943 18.0964 15.5189 18.2353 15.0497 18.2353C14.5992 18.2353 14.2332 18.0964 13.9516 17.8185C13.6701 17.5406 13.5293 17.1933 13.5293 16.7765V1.58908C13.5293 1.13754 13.6888 0.764146 14.0079 0.468908C14.3458 0.156303 14.7587 0 15.2467 0C15.5283 0 15.8005 0.0521012 16.0632 0.156304C16.3448 0.260505 16.5513 0.39944 16.6826 0.57311L26.931 12.6605V1.45882C26.931 1.04202 27.0718 0.694678 27.3533 0.416808C27.6536 0.138936 28.029 0 28.4795 0Z" fill="black"/>
                    <path d="M14.9502 0C15.4007 0 15.7667 0.138936 16.0483 0.416808C16.3298 0.694678 16.4706 1.04202 16.4706 1.45882V16.6462C16.4706 17.0978 16.3017 17.4798 15.9638 17.7924C15.6447 18.0877 15.2412 18.2353 14.7531 18.2353C14.4904 18.2353 14.2276 18.2006 13.9648 18.1311C13.7208 18.0443 13.5425 17.9314 13.4299 17.7924L3.09703 5.65294V16.7765C3.09703 17.1933 2.94687 17.5406 2.64656 17.8185C2.36501 18.0964 1.98961 18.2353 1.52036 18.2353C1.06988 18.2353 0.703871 18.0964 0.422323 17.8185C0.140774 17.5406 0 17.1933 0 16.7765V1.58908C0 1.13754 0.159544 0.764146 0.478633 0.468908C0.816491 0.156303 1.22943 0 1.71745 0C1.99899 0 2.27116 0.0521012 2.53394 0.156304C2.81549 0.260505 3.02195 0.39944 3.15334 0.57311L13.4017 12.6605V1.45882C13.4017 1.04202 13.5425 0.694678 13.824 0.416808C14.1244 0.138936 14.4997 0 14.9502 0Z" fill="black"/>
                </svg>

            </i>
            <div>
                <div class="title">Learn more about Nodenode</div>
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

nav.global {

    background:white;
    display: flex;
    flex-direction: row;
    z-index:1;

    @media only screen and (max-width: 800px) {
        left:0px;
        right:0px;
        bottom:0px;
        flex-direction:column;
    } 

    &:hover, .selected {
        background:rgba(255,255,255,0.84);
    }


    .nav-item {
        width:33.3333%;
        padding:$padding-med $padding-big;
        transition: all .12s ease-in-out;
        display: flex;
        flex-direction: row;
        cursor: pointer;

        @media only screen and (max-width: 800px) {
            width:100%;
            padding: 14px $padding-med;
        } 

        i {
            align-self:center;
            margin-right:$padding-med;
        }

        div {

            align-self:center;

            .title {
                font-family: Poppins;
                font-style: normal;
                font-size: 14px;
                line-height: 20px;
                color: $black;

                @media only screen and (max-width: 1200px) {
                    font-size: 12px;
                    line-height: 14px;
                    margin-bottom:2px;
                } 
            }

            .explanation {
                font-family: Poppins;
                font-style: normal;
                font-weight: normal;
                font-size: 12px;
                line-height: 14px;
                color: $black;
                opacity: 0.5;

                @media only screen and (max-width: 1200px) {
                    font-size: 11px;
                    line-height: 13px;
                } 
            }
        }

        &:hover, .selected {
             background:white;
            transform: scale(1.03);
            box-shadow: 0px 4px 4px rgba(132, 47, 194, 0.42), 0px 4px 44px rgba(81, 22, 136, 0.87); 
        }
    }
}

</style>