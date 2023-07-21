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
            <NImageGroup>
                <n-space justify="center" show-toolbar-tooltip >
                    <n-image
                        width="100"
                        src="https://gw.alipayobjects.com/zos/antfincdn/aPkFc8Sj7n/method-draw-image.svg"
                    />
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