<script>
    import '~/assets/css/faqs.css'
    import * as pkg from 'naive-ui'

    const { NCollapse, NCollapseItem, NDivider, NImage } = pkg

    export default defineComponent({
        components: {
            NCollapse,
            NCollapseItem,
            NDivider,
            NImage
        }
    })
</script>

<template>
    <section id='faqs' class='faqs'>
        <h1 class='faqs_title'>FAQs</h1>
        <n-image width="90" src="/imgs/arrow.svg" class='left_lightning'/>
        <n-image width="90" src="/imgs/arrow.svg" class='right_lightning'/>
        <n-divider />
        <n-collapse accordion>
            <n-collapse-item title='What is ChargerHacks?' name="1">
                <p>ChargerHacks 2023 is Churchill High School's very first hackathon run by high schoolers for those interested in pursuing a future in the tech industry. Through this 2-day virtual hackathon, we want students to be able to work together to learn, build, and network.</p>
            </n-collapse-item>
            <n-collapse-item title='Who runs ChargerHacks?' name="2">
                <p>ChargerHacks is organized and run by Churchill High School's Coding Club.</p>
            </n-collapse-item>
            <n-collapse-item title="What to expect during ChargerHacks?" name="3">
                <p>During the competition, you can work with your team to collaborate on an innovative project.</p>
            </n-collapse-item>
            <n-collapse-item title="Who can apply?" name="4">
                <p>Students of all educational levels are welcome to apply such as high schoolers and college students.</p>
            </n-collapse-item>
            <n-collapse-item title="What do I need to know to attend?" name="5">
                <p>You don't need to know anything to attend! ChargerHacks is an event where you can learn and explore the various fields of technology.</p>
            </n-collapse-item>
            <n-collapse-item title="What do I need?" name="6">
                <p>You'll need an internet connection as well as a computer with zoom installed.</p>
            </n-collapse-item>
            <n-collapse-item title="How many people can be on a team?" name="7">
                <p>Each team is allowed to contain up to 4 members. However, there is no minimum limit and you are welcome to play by yourself.</p>
            </n-collapse-item>
            <n-collapse-item title="Can we register as a team?" name="8">
                <p>You should register individually first. You will be able to "form" your team on devpost during project submissions.</p>
            </n-collapse-item>
            <n-collapse-item title="What do I do after applying?" name="9">
                <p>After you apply, simply wait until the day of the opening ceremony where further instructions will be shared such as the zoom link for the opening ceremony.</p>
            </n-collapse-item>
            <n-collapse-item title="I have more questions!" name="10">
                <p>If you any unaddressed questions, feel free to email 
                    <a href="mailto:contact@chargerhacks.com" class='email_link'>
                        contact@chargerhacks.com
                    </a>
                    .
                </p>
            </n-collapse-item>
        </n-collapse>
    </section>
</template>