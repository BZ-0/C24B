<script setup>
    import LucideIcon from "./WLucideIcon.vue";
</script>

<template>
    <main data-scheme="accent" data-highlight="1">

        <div class="info-block">
            <h4><LucideIcon name="medal"/>Unite.JS<LucideIcon name="medal"/></h4>
            <div class="subscript"><a href="#">Learn More</a></div>

            <div class="description">Our unified JS library package.</div>

            <div class="space"></div>
            <div class="description">
                <h6>Features:</h6>
                <ul>
                    <li>Grid utils (used in application).</li>
                    <li>Reactive and objects utils.</li>
                    <li>Pointer and interaction utils.</li>
                    <li>Dynamic styles workers.</li>
                    <li>Web Worker core utils.</li>
                    <li>DOM utils, observers.</li>
                    <li>Cryptography utils.</li>
                </ul>
            </div>


            <div class="space"></div>

            <div class="buttons">
                <a href="#"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="book-marked"/>Documentation<LucideIcon name="book-marked"/></button></a>
                <a href="https://github.com/BZ-0/unite.js"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="github"/>Source Code<LucideIcon name="github"/></button></a>
            </div>
        </div>

    </main>
</template>
