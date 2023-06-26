<script setup lang="ts">
    import { RouterLink } from 'vue-router';
</script>
<template>
    <header class="header">
        <div class="container">
            <RouterLink to="/">
                <img alt="fc logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
            </RouterLink>
            <nav class="nav-container">
                <ul>
                    <li>
                        <RouterLink to="/">
                            HOME
                        </RouterLink>
                    </li>                    
                    <li>
                        <RouterLink to="categorias">
                            CATEGORIAS
                        </RouterLink>
                    </li>
                    <li>RECEITAS</li>
                    <li>DESPESAS</li>
                    <li>SOBRE</li>
                    <li>CONTATO</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped>
    header.header {
        position: relative;
        width: 100%;
        padding: 15px;
        border: 1px solid black;
    }
    .header .container {
        display: flex;
    }
    .header .container .nav-container ul {
        display: flex;
    }
    .header .container .nav-container ul li {
        padding: 0px 5px 0px 5px;
        margin: 2px 5px 2px 5px;
        list-style: none;
    }

    .header .container .nav-container ul li:hover {
        border-bottom: 1px solid black;
    }
</style>