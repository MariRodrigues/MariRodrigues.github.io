<template>
    <section>
        <div class="container">
            <div class="titulo">
                <h1>Contatos</h1>
            </div>
            <div class="contatos">
                <img alt="WhatsApp" class="icones" src="@/assets/img/icon-linkedin.png">
                <img alt="WhatsApp" class="icones" src="@/assets/img/whatsapp.png">
            </div>

        </div>


    </section>
</template>

<script>
export default {
    name: 'Contato'
}
</script>

<style scoped>
section {
    background-color: #252525;
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.titulo h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 40px;
    color: white;
}

.contatos {
    margin-top: 40px;
    margin-bottom: 40px;
    height: 120px;
    width: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.icones {
    margin-left: 5px;
    margin-right: 5px;
    width: 100px;
    height: 100px;
    background-color: aliceblue;
    border-radius: 20%;
}


</style>