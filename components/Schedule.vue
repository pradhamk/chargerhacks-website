<script>
    import '~/assets/css/schedule.css'
    import * as pkg from 'naive-ui'
    
    const { NList, NListItem } = pkg
    
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
                        <h1>October 13</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Opening Ceremony @ 6pm</li>
                            <li>Team Crafting @ 7pm</li>
                            <li>Start Hacking! @ 8pm</li>
                        </ul>
                    </n-list-item>
                </n-list>
            <n-list>
                    <template #header>
                        <h1>October 14</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Tech/College Talk with MSU & UofM students @ 3pm</li>
                        </ul>
                    </n-list-item>
            </n-list>
            <n-list>
                    <template #header>
                        <h1>October 15</h1>
                    </template>
                    <n-list-item>
                        <ul class='schedule_events'>
                            <li>Submissions Open @ 8am</li>
                            <li>Hacking Ends @ 12pm</li>
                            <li>Closing Ceremony @ 2pm</li>
                        </ul>
                    </n-list-item>
            </n-list>
        </div>
        
    </section>
</template>
