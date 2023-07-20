<script>
    import '~/assets/css/schedule.css'
    import { NList, NListItem } from 'naive-ui'

    export default defineComponent({
        components: {
            NList,
            NListItem,
        }
    })
</script>

<template>
    <section class='schedule' id='schedule'>
        <div class='schedule_title'>
            <h1>Schedule</h1>
        </div>
        <div class='lists'>
            <n-list>
                    <template #header>
                        <h1>October 10</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Opening Ceremony @ 6pm</li>
                            <li>Team Crafting @ 7pm</li>
                            <li>Start Hacking! @ 6pm</li>
                        </ul>
                    </n-list-item>
                </n-list>
            <n-list>
                    <template #header>
                        <h1>October 11</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Tech Talk with MSU students @ 3pm</li>
                        </ul>
                    </n-list-item>
            </n-list>
            <n-list>
                    <template #header>
                        <h1>October 12</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Submission Opens @ 8am</li>
                            <li>Hacking Ends @ 12pm</li>
                            <li>Closing Ceremony @ 2pm</li>
                        </ul>
                    </n-list-item>
            </n-list>
        </div>
        
    </section>
</template>