<template>
    <section id="sobre-mim">
        <div class="container">
            <div class="titulo">
                <h1><strong>Sobre mim</strong></h1>

            </div>
            <div class="texto">
                <p><br>It is a long established fact that a reader will be distracted by the readable content of a page
                    when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal
                    distribution of letters, as opposed to using 'Content here, content here', making it look like
                    readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their
                    default model text, and a search for 'lorem ipsum' will uncover many web sites still in their
                    infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose
                    (injected humour and the like). <br><br>
                    There are many variations of passages of Lorem Ipsum available, but the majority have suffered
                    alteration in some form, by injected humour, or randomised words which don't look even slightly
                    believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't
                    anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet
                    tend to repeat predefined chunks as necessary,
                    <br><br>
                    The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested.
                    Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in
                    their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
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
    padding: 0px 100px 10px 100px;
    align-items: center;
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