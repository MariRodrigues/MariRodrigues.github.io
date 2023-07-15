<template>
    <section id="projetos">
        <div class="container">
            <div class="titulo">
                <h1><strong>Projetos</strong></h1>

            </div>
            <div class="cards">
                <div class="card">
                    <a href="https://github.com/MariRodrigues/EcommerceAPI" target="_blank"><img src="../assets/img/ecommerceApi.png" alt="Avatar"></a>
                    <div class="descricao">
                        <h4><b>API Ecommerce</b></h4>
                        <p>Projeto de API REST, feita em .NET. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
                    when an unknown printer took a galley of type and scrambled it to make a type
                    specimen book.</p>
                    </div>
                </div>
                <div class="card">
                    <a href="https://github.com/MariRodrigues/EcommerceAPI" target="_blank"><img src="../assets/img/bg.png" alt="Avatar"></a>
                    <div class="descricao">
                        <h4><b>Ecommerce Front</b></h4>
                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
                    when an unknown printer took a galley of type and scrambled it to make a type
                    specimen book.</p>
                    </div>
                </div>
                <div class="card">
                    <a href="https://github.com/MariRodrigues/EcommerceAPI" target="_blank"><img src="../assets/img/bg.png" alt="Avatar"></a>
                    <div class="descricao">
                        <h4><b>API Usuários</b></h4>
                        <p>Architect & Engineer</p>
                    </div>
                </div>


            </div>

        </div>

    </section>
</template>

<script>
export default {
    name: 'Projetos'
}
</script>

<style scoped>
section {
    background-image: url('../assets/img/texture-background.png');
    width: 100%;
    height: 850px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 70%;
    height: 80%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    align-items: center;
    background-color: white;
    border: 1px solid #b8b8b827;
    box-shadow: rgba(165, 164, 164, 0.37) 2px 2px 1px;
}

.titulo {
    margin-top: 20px;
}

.titulo h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 30px;
    color: rgb(65, 64, 64);
}

.cards {
    margin-top: 20px;
    width: 95%;
    height: 500px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-around;
}

.card {
  width: 400px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin-top: 20px;
  margin-left: 5px;
  margin-right: 5px;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.card img {
    width: 100%;
    height: 300px;
}

.card p {
    font-family: 'Open Sans', sans-serif;
}

.card h4 {
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
}

.descricao {
    /* top | right | bottom | left */
  padding: 2px 16px;
  height: 200px;
}

.descricao p {
    padding: 8px 5px 8px 5px;
}

.descricao h4 {
    text-align: center;
}

</style>