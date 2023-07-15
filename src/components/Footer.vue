<template>
    <footer>
        <div class="container">
            <div class="redes-sociais">
                <a href="https://github.com/MariRodrigues" target="_blank"><img alt="Foto-Perfil" class="icones"
                        src="@/assets/img/github-pink.png"></a>
                <a href="https://www.instagram.com/marisouzaas2/" target="_blank"><img alt="Foto-Perfil" class="icones"
                        src="@/assets/img/insta-pink.png"></a>
                <a href="https://www.linkedin.com/in/mariana-rodrigues-de-souza-522321124/" target="_blank"><img alt="Foto-Perfil" class="icones"
                        src="@/assets/img/linkedin-pink.png"></a>
                <a href="https://web.facebook.com/MariSouzaaS2/" target="_blank"><img alt="Foto-Perfil" class="icones"
                        src="@/assets/img/face-pink.png"></a>
            </div>
            <div class="descritivo">
                <p>© Mariana Rodrigues 2023. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
footer {
    background-color: var(--color-background-footer);
    width: 100%;
    height: 220px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-top: 1px solid #b8b8b827;
}

.container {
    height: 100%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.descritivo {
    margin-top: 10px;
}

.descritivo p {
    color: rgb(255, 255, 255);
    font-family: 'Open Sans', sans-serif;
}

.redes-sociais {
    margin-top: 10px;
    width: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.icones {
    border-radius: 20%;
    margin: 10px;
    height: 40px;
    width: 40px;
}

.icones:hover {
    opacity: 0.6;
    transition: 0.5s;
}
</style>