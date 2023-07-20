<script>
    import '~/assets/css/about.css'
    import { NCard, NDivider } from 'naive-ui'

    export default defineComponent({
        components: {
            NCard,
            NDivider
        }
    })
</script>

<template>
    <section class='about' id='about'>
        <div class='about_title'>
            <img src='/imgs/arrow.svg' alt='chargerhacks_lightning' class='lightning'/>
            <h1>What is</h1>
            <h1 class='chargerhacks'>ChargerHacks</h1>
            <h1 class='question'>?</h1>
            <img src='/imgs/arrow.svg' alt='chargerhacks_lightning' class='lightning'/>
        </div>
        <div>
            <p class='about_p'>
                ChargerHacks 2023 is Churchill High School's very first Hackathon run by high schoolers for those interested in pursuing a future in the tech industry. Through this 2-day virtual hackathon, we want students to be able to work together to learn, build, and network.
            </p>
        </div>
        <div class='about_cards'>
            <n-card size='large'>
                <span class="material-symbols-outlined">School</span>
                <br>
                <h1>Run by high schoolers</h1>
                <n-divider />
                <p>ChargerHacks is organized by Churchill High School's Coding Club where students explore the world of technology through volunteering, participating in hackathons, and other events.</p>
            </n-card>
            <n-card size='large'>
                <span class="material-symbols-outlined">pin_drop</span>
                <br>
                <h1>Fully Virtual</h1>
                <n-divider />
                <p>As we have decided to run ChargerHacks virtually this year, all current students wether is be high school or college are strongly encouraged to attend, regardless of their physical location</p>
            </n-card>
            <n-card size='large'>
                <span class="material-symbols-outlined">event</span>
                <br>
                <h1>October 10-12, 2023</h1>
                <n-divider />
                <p>ChargerHacks 2023 will take place from October 10 to October 12, giving contestants 3 days/2 nights to learn, plan, and develop their project</p>
            </n-card>
        </div>
    </section>
</template>