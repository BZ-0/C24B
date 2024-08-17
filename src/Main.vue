<script setup>

    import Main from "@us/Vue/Main.vue"
    import Header from "@us/Vue/Header.vue"
    import Navbar from "@us/Vue/Navbar.vue"
    import Cards from "@us/Vue/Cards.vue"
    import Product from "@us/Vue/Product.vue"
    import Footer from "@us/Vue/Footer.vue"

</script>

<!-- -->
<template>

    <Navbar></Navbar>

    <div class="content">
        <Header></Header>
        <Main></Main>

        <div class="background" data-scheme="solid">
            <Product></Product>
            <Cards></Cards>
        </div>

        <Footer></Footer>
    </div>

</template>

