<template>
    <section id="sobre-mim">
        <div class="container">
            <div class="titulo">
                <h1><strong>Sobre mim</strong></h1>

            </div>
            <div class="texto">
                <p>Meu nome é Mariana e sou formada em Ciência da Computação pela Universidade Nove de Julho (Univove). 
                Desde sempre, tenho uma paixão pela tecnologia e um forte interesse em me tornar uma desenvolvedora backend.
                <br><br>
                Iniciei minha jornada de estudos na área de programação ao concluir um curso técnico em Mecatrônica em 2015. Foi nesse 
                momento que decidi que a programação seria minha carreira e me tornei determinada a estudar e me aprimorar na área.
                <br><br>
                Atualmente, trabalho na empresa Clearsale, onde atuo como desenvolvedora backend em uma equipe utilizando 
                tecnologias como C#, .NET, SQL Server, Entity Framework, Identity e Dapper. Trabalhamos com metodologias 
                ágeis, como Scrum e Kanban, para promover um ambiente colaborativo e eficiente.
                <br><br>
                Meu foco principal continua sendo o desenvolvimento backend, mas também tenho interesse em expandir meu 
                conhecimento em outras áreas relacionadas, como front-end e arquitetura. Estou sempre em busca de novos 
                desafios e oportunidades para aprimorar minha trajetória profissional, mantendo-me atualizada sobre as 
                tendências e melhores práticas da indústria.
                </p>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Sobre'
}
</script>

<style scoped>
section {
    background-image: url('../assets/img/texture-background.png');
    width: 100%;
    height: 700px;
    display: flex;
    justify-content: center;
    align-items: center;

}

.container {
    width: 70%;
    height: 600px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    background-color: white;
    border: 1px solid #b8b8b827;
    box-shadow: rgba(165, 164, 164, 0.37) 2px 2px 1px;
}

.titulo {
    padding-top: 30px;
}

.titulo h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 30px;
    color: rgb(65, 64, 64);
}

.texto {
    /* top | right | bottom | left */
    padding: 0px 100px 50px 100px;

}

.texto p {
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
}

@media (max-width: 1200px) {
    .container{
        width: 90%;
        margin: 0 auto;
    }

    .texto {
    /* top | right | bottom | left */
    padding: 0px 50px 10px 50px;
    align-items: center;
}


}
</style>