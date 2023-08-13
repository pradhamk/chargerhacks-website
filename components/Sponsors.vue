<script>
    import '~/assets/css/sponsors.css'
    import * as pkg from 'naive-ui'
    
    const { NImageGroup, NImage, NSpace } = pkg
    
    export default defineComponent({
        components: {
            NImageGroup,
            NImage,
            NSpace
        }
    })
</script>

<template>
    <section id='sponsors' class='sponsors'>
        <h1 class='sponsors_title'>Sponsors</h1>
        <div class='sponsors_div'>
            <a href='https://solana.com/' target='_blank'>
                <n-image
                    width="410"
                    src="/imgs/Solana.svg"
                    preview-disabled
                    class="solana_logo"
                />
            </a>
            <NImageGroup>
                <n-space justify="center">
                    <a href='https://sekai.team/' target='_blank'>
                        <n-image
                            width="130"
                            src="/imgs/PRSK.svg"
                            preview-disabled
                        />
                    </a>
                    <a href='https://www.interviewcake.com/r/UHN8CA' target='_blank'>
                        <n-image
                            width="110"
                            src="/imgs/InterviewCakeLogo.svg"
                            preview-disabled
                        />
                    </a>
                    <a href='https://osec.io/' target='_blank'>
                        <n-image
                            width="110"
                            src="/imgs/Ottersec.svg"
                            preview-disabled
                        />
                    </a>
                    <a href='https://www.axure.com/' target='_blank'>
                        <n-image
                            width="110"
                            src="/imgs/Axure.svg"
                            preview-disabled
                        />
                    </a>
                </n-space>
            </NImageGroup>
        </div>
        <div class='sponsors_request_div'>
            <p class='sponsors_request'>
                Sponsors help us fund ChargerHacks, allowing us to further incentivize students into participating. If you would like to help us in our endeavor to encourage/sprout new interests in our future generation, contact us at 
                <a href='mailto:contact@chargerhacks.com'>
                    contact@chargerhacks.com
                </a>
            </p>
        </div>
    </section>
</template>
