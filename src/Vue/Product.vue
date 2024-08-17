<script setup>
    import LucideIcon from "./WLucideIcon.vue";
</script>

<template>
    <section id="products" data-transparent>

        <h4><LucideIcon name="apple"/> Our Products <LucideIcon name="apple"/></h4>

        <div class="break"></div>

        <article id="idc-l2" data-scheme="solid" data-highlight="1">
            <h3><LucideIcon name="crown"/> IDC-L2 <LucideIcon name="crown"/></h3>

            <div class="subscript"><a href="#">Learn More</a></div>
            <div class="description">It's your new tab page</div>

            <div class="space"></div>
            <div class="description align-start">
                <h6>Features:</h6>
                <ul>
                    <li>Windows-like UI/UX</li>
                    <li>Mobile adaptive</li>
                    <li>Editable grid items</li>
                    <li>Windowed frames</li>
                </ul>
            </div>

            <div class="space"></div>

            <div class="buttons">
                <a href="https://app.c24b.ru/"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="crown"/>Open Application<LucideIcon name="crown"/></button></a>
                <a href="https://github.com/BZ-0/APP.C24B"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="github"/>Source Code<LucideIcon name="github"/></button></a>
            </div>
        </article>

        <div class="word"><LucideIcon name="circle-fading-plus"/></div>

        <article id="idc-cloud" data-scheme="solid" data-highlight="1">
            <h3><LucideIcon name="server-cog"/> IDC-Cloud <LucideIcon name="server-cog"/></h3>

            <div class="subscript"><a href="#">Learn More</a></div>
            <div class="description">It's our server and database of application.</div>

            <div class="space"></div>
            <div class="description align-start">
                <h6>Features:</h6>
                <ul>
                    <li>Tuya Clouds</li>
                    <li>Synchronization</li>
                    <li>Other workspaces</li>
                    <li>File storages</li>
                    <li>Databases</li>
                </ul>
            </div>

            <div class="space"></div>

            <div class="buttons">
                <a href="https://cloud.c24b.ru/"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="server-cog"/>Registration<LucideIcon name="server-cog"/></button></a>
                <a href="https://github.com/BZ-0/Cloud.C24B"><button data-scheme="inverse" type="button" data-highlight-hover="1"><LucideIcon name="github"/>Source Code<LucideIcon name="github"/></button></a>
            </div>
        </article>

    </section>
</template>
