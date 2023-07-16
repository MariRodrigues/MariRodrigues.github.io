<template>
    <section id="skills">
        <div class="container">
            <div class="titulo">
                <h1><strong>Formação & Certificados</strong></h1>
            </div>
            <div class="conteudo">
                <div class="formacoes">
                    <div class="formacao">
                        <h1>Bacharelado em Ciência da Computação - Universidade Nove de Julho</h1>
                        <h3>Concluído em 2015</h3>
                        <p>Com uma formação ampla, o curso de Ciência da Computação capacita os alunos para
                            atuar em um mercado em constante mudança e crescimento, para analisar, especificar,
                            desenvolver, implantar e avaliar sistemas informatizados, de acordo com as necessidades
                            atuais</p>
                    </div>
                    <div class="formacao">
                        <h1>Técnico em Mecatrônica - ETEC Martin Luther King</h1>
                        <h3>Concluído em 2015</h3>
                        <p>O Técnico em Mecatrônica é o profissional que atua no projeto, na execução e na instalação de
                            máquinas e equipamentos automatizados e sistemas robotizados. Realiza manutenção, medições e
                            testes dessas máquinas, equipamentos e sistemas, conforme especificações técnicas. Opera
                            equipamentos, utiliza softwares específicos e linguagens de programação adequadas.</p>
                    </div>
                </div>
                <div class="divisoria"></div>
                <div class="cursos">
                    <div class="curso">
                        <a href="https://cursos.alura.com.br/formacao-dotnet-v95996" target="_blank"><img
                                src="@/assets/img/alura.jpg"></a>
                        <div class="infos-curso">
                            <h1>ASP.NET Core REST APIs</h1>
                            <h3>Concluído em Jan/2023</h3>
                            <p>Principais conceitos de API Rest com ASP.NET Core e boas práticas de desenvolvimento.
                                A formação Alura reúne 4 cursos, abordando desde os verbos essenciais em HTTP,
                                mapeamento de entidades com banco de dados utilizando o Entity Framework, e também
                                focando na
                                segurança de APIs com o Identity, onde foi implementada a lógica para controle de
                                usuários trazendo conceitos de autorização e autenticação.</p>
                        </div>
                    </div>
                    <div class="curso">
                        <a href="https://www.alura.com.br/formacao-boas-praticas-c-sharp" target="_blank"><img
                                src="@/assets/img/alura.jpg"></a>
                        <div class="infos-curso">
                            <h1>Boas Práticas em C#</h1>
                            <h3>Concluído em Jan/2023</h3>
                            <p>Formação que reúne cursos com abordagens de boas práticas no desenvolvimento de Software
                                com C#: Design Patterns, SOLID, Clean Code.</p>
                        </div>
                    </div>
                    <div class="curso">
                        <a href="https://balta.io/cursos/refatorando-para-testes-de-unidade" target="_blank"><img
                                src="@/assets/img/balta.png"></a>
                        <div class="infos-curso">
                            <h1>Refatorando para Testes de Unidade</h1>
                            <h3>Concluído em 2015</h3>
                            <p>Curso focado em refatoração e reescrita de código legado, incluindo Testes Unitários
                                para facilitar e aumentar a confiabilidade nas entregas.</p>
                        </div>
                    </div>

                </div>

            </div>

            <div class="skills">
                <div class="habilidades">
                    <div class="icone-skill"><img alt="Azure"  src="@/assets/img/azure.png"></div>
                    <div class="descricao">Azure DevOps</div>
                </div>
                <div class="habilidades">
                    <div class="icone-skill"><img alt="CSharp" src="@/assets/img/csharp.png"></div>
                    <div class="descricao">C#</div>
                </div>
                <div class="habilidades">
                    <div class="icone-skill"><img alt="Git"  src="@/assets/img/git.png"></div>
                    <div class="descricao">Git</div>
                </div>
                <div class="habilidades">
                    <div class="icone-skill"><img alt=".NET"  src="@/assets/img/dapper.png"></div>
                    <div class="descricao">Dapper</div>
                </div>
                <div class="habilidades">
                    <div class="icone-skill"><img alt="VueJs"  src="@/assets/img/dotnet.png"></div>
                    <div class="descricao">.NET</div>
                </div>
                <div class="habilidades">
                    <div class="icone-skill"><img alt="SqlServer"  src="@/assets/img/sqlserver.png"></div>
                    <div class="descricao">Sql Server</div>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'Habilidades'
}

</script>

<style scoped>
#skills {
    width: 100%;
    height: 990px;
    background-image: url('../assets/img/texture-background.png');

}

.container {
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.titulo {
    width: 500px;
    margin: 5px;
    padding: 5px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
}

.titulo h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 30px;
    color: rgb(65, 64, 64);
}

.conteudo {
    margin-top: 20px;
    width: 70%;
    display: flex;
    justify-content: space-around;
}

.formacoes {
    padding-top: 20px;
    width: 500px;
    height: 400px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;

}

.formacao {
    margin-top: 10px;
    height: 210px;
}

.formacao h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 19px;
    color: rgb(24, 23, 23);
}

.formacao h3 {
    font-family: 'Open Sans', sans-serif;
    font-size: 14px;
    color: #FF66C4;
}

.formacao p {
    font-family: 'Open Sans', sans-serif;
    font-size: 17px;
}

.cursos {
    padding-top: 20px;
    width: 500px;
    height: 700px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: left;
}

.curso {
    display: flex;
}

.curso h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 19px;
    color: rgb(24, 23, 23);
}

.curso h3 {
    font-family: 'Open Sans', sans-serif;
    font-size: 14px;
    color: #FF66C4;
}

.curso p {
    font-family: 'Open Sans', sans-serif;
    font-size: 17px;
}

.curso img {
    height: 60px;
    width: 60px;
    box-shadow: rgba(165, 164, 164, 0.37) 2px 2px 1px;
}

.infos-curso {
    padding-left: 15px;
}

.divisoria {
    margin-top: 30px;
    width: 1px;
    height: 500px;
    background-color: #c5c5c542;
}

.skills {
    width: 40%;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.habilidades {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    align-items: center;
}

.icone-skill {
    border-radius: 10%;
    margin-top: 5px;
    margin-bottom: 5px;
    height: 100px;
    width: 100px;
    text-align: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: rgb(255, 253, 253);
    box-shadow: rgba(27, 27, 27, 0.37) 2px 2px 1px;
transition: 0.2s opacity;
}

.icone-skill img {
    height: 70px;
    width: 70px;   
}

.icone-skill:hover {
box-shadow: #fc92d3 2px 2px 1px;
}

.habilidades .descricao {
    margin-top: 5px;
    font-family: 'Open Sans', sans-serif;
    size: 25px;
    color: #242323;
}

@media (max-width: 860px) {
    #fundo {
        height: 1200px;
    }
}
</style>