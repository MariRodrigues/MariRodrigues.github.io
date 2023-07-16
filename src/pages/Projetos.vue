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
                        <p>API didática para um e-commerce, implementada utilizando .NET 5, Dapper e Entity Framework para mapeamento ORM. Aplica 
                            conceitos de clean code e SOLID, seguindo a organização de Design Orientado ao Domínio (DDD). Adota o padrão 
                            CQRS e inclui testes unitários e de integração.</p>
                    </div>
                </div>
                <div class="card">
                    <a href="https://github.com/MariRodrigues/EcommerceFront" target="_blank"><img src="../assets/img/EmDev22.png" alt="Avatar"></a>
                    <div class="descricao">
                        <h4><b>Ecommerce Front</b></h4>
                        <p>Front-end desenvolvido com Vue.js, Bootstrap e Axios. Implementa a página principal e cadastro de categorias. 
                            Objetiva conectar-se à API back-end para aprendizado e demonstração funcional.</p>
                    </div>
                </div>
                <div class="card">
                    <a href="https://github.com/MariRodrigues/UsuariosAPI" target="_blank"><img src="../assets/img/EmDev33.png" alt="Avatar"></a>
                    <div class="descricao">
                        <h4><b>API Usuários</b></h4>
                        <p>API para autenticação e autorização de usuários no e-commerce. Integra-se às controllers da EcommerceAPI, 
                            usando o Identity Framework para gerenciar as funcionalidades de autorização.</p>
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
    height: 790px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 70%;
    height: 85%;
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
  height: 210px;
}

.descricao p {
    padding: 8px 5px 8px 5px;
}

.descricao h4 {
    text-align: center;
}

</style>