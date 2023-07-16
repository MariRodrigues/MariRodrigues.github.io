<template>
    <main>
        <div id="home" class="container border-shadow-bottom">
            <div class="item">
                <img alt="Foto-Perfil" id="imagem-perfil" src="@/assets/img/perfil.jpg">

            </div>
            <div class="texto">
                <p class="titulo">Mariana Souza</p>
                <h3>Desenvolvedora Backend</h3>

            </div>

        </div>
    </main>
</template>

<script>
export default {
    name: 'Home'
}

</script>

<style scoped>
/* 22px opens sans */
main {
    background-color: #2F2E2E;
    width: 100%;
    height: 350px;
    display: flex;
    border-bottom: 1px solid #b8b8b827;
}

.border-shadow-bottom {
    box-shadow: 0 4px 2px -2px #68686667;
}

.container {
    padding-top: 10px;
    width: 70%;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin-top: 30px;
}

.item {
    display: flex;
    width: 300px;
    height: 250px;
    justify-content: right;
    align-items: center;
}

.texto {
    display: flex;
    flex-direction: column;
    width: 500px;
    height: 250px;
    justify-content: center;
    align-items: right;

}

#imagem-perfil {
    height: 250px;
    width: 250px;
    border-radius: 50%;
    border: 1px solid #25252577;
}

.texto p {
    font-family: 'Open Sans', sans-serif;
    font-size: 22px;
    color: white;
}

.texto h3 {
    color: white;
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
}

.texto .titulo {
    font-family: 'Ysabeau SC', sans-serif;
    font-size: 60px;
}




@media (max-width: 1200px) {

    /* acima de 992px */
    main {
        background-color: #5e24ff;
        height: 600px;
    }

    .container {
        padding-top: 50px;
        width: 70%;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }

    .texto {
        align-items: center;
        width: 100%;
    }
}
</style>