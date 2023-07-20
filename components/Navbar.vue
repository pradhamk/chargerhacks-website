<script setup lang="ts">
    import '~/assets/css/navbar.css'

    function open_menu(_e) {
        const open_menu = document.getElementById("mobile_menu")
        open_menu?.classList.add("active")
        document.body.style.overflow = 'hidden';
    }

    function close_menu(_e) {
        const open_menu = document.getElementById("mobile_menu")
        open_menu?.classList.remove("active")
        document.body.style.overflow = 'none';
    }
</script>

<template>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <nav class="navbar">
        <div class='nav_logo_div'>
            <a href='/'>
                <img src='/imgs/chargerhacks_logo.svg' alt='ChargerHacks Logo' class='nav_logo'/>
            </a>
        </div>
        <div class='nav_links'>
            <a href="#about">About</a>
            <a href="#schedule">Schedule</a>
            <a href="#faqs">FAQs</a>
            <a href="#sponsors">Sponsors</a>
        </div>
        <div class='nav_apply_div'>
            <a href='/'>
                <button class="nav_apply_button">Apply</button>
            </a>
        </div>
        <div id="mobile_menu" class='mobile_menu'>
            <button id="open_button" class='mobile_menu_open' @click="open_menu">
                <span class="material-symbols-outlined">menu</span>
            </button>
            <button id="close_button" class='mobile_menu_close' @click="close_menu">
                <span class="material-symbols-outlined">close</span>
            </button>
            <div class="mobile_menu_links">
                <a href="#about" @click="close_menu">About</a>
                <a href="#schedule" @click="close_menu">Schedule</a>
                <a href="#faqs" @click="close_menu">FAQs</a>
                <a href="#sponsors" @click="close_menu">Sponsors</a>
            </div>
        </div>
    </nav>
</template>