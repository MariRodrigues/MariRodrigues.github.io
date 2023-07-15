<template>
    <header>
        <nav class="container">
            <div class="logo">
                <a href="/"><img alt="MariDev" id="logo" src="../assets/img/logo-mrdev.png"></a>
            </div>
            <div id="menu-items">
                <ul>
                    <li><a href="../pages/Home.vue">Home</a></li>
                    <li><a href="#sobre-mim">Sobre</a></li>
                    <li><a href="#fundo">Skills</a></li>
                    <li><a href="#projetos">Projetos</a></li>
                </ul>

            </div>

        </nav>

    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
header {
    background-color: var(--color-background-nav);
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-bottom: 1px solid #b8b8b827;
}

nav {
    display: flex;
    justify-content: space-between;
    height: 100%;
    width: 50%;
    align-items: center;
    
}

#logo {
    width: 40px;
}

#menu-items {
    display: flex;
    width: auto;
}

#menu-items a {
    color: white;
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
}

ul {
    display: flex;
}

ul li {
    margin: 0;
    margin-left: 30px;
    font-size: 18px;
    list-style: none;
}
</style>