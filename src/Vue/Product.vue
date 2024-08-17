<script setup>
    import LucideIcon from "./WLucideIcon.vue";
</script>

<template>
    <section id="products" data-transparent>

        <h3>Our Products</h3>

        <div class="break"></div>

        <article id="idc-l2" data-scheme="solid" data-highlight="1">
            <h3><LucideIcon name="crown"/> IDC-L2 <LucideIcon name="crown"/></h3>

            <div class="subscript"><a href="#">Learn More</a></div>
            <div class="description">It's your new tab page</div>

            <div class="space"></div>

            <a href="https://app.c24b.ru/"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="crown"/>Open Application<LucideIcon name="crown"/></button></a>
        </article>

        <div class="word"><LucideIcon name="circle-fading-plus"/></div>

        <article id="idc-cloud" data-scheme="solid" data-highlight="1">
            <h3><LucideIcon name="server-cog"/> IDC-Cloud <LucideIcon name="server-cog"/></h3>

            <div class="subscript"><a href="#">Learn More</a></div>
            <div class="description">It's our server and database of application.</div>

            <div class="space"></div>

            <a href="https://cloud.c24b.ru/"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="server-cog"/>Registration<LucideIcon name="server-cog"/></button></a>
        </article>

    </section>
</template>
