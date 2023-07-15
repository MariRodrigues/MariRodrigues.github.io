<template>
  <div id="app">
    <Header />
    <Home />
    <Sobre />
    <Habilidades />
    <Projetos />
    <Footer />
    
  </div>
</template>

<script>
import './styles/global.css'
import Header from './components/Header.vue'
import Home from './pages/Home.vue'
import Habilidades from './pages/Habilidades.vue'
import Footer from './components/Footer.vue'
import Sobre from './pages/Sobre.vue'
import Projetos from './pages/Projetos.vue'


export default {
  name: 'App',
  components: {
    Header,
    Home,
    Habilidades,
    Sobre,
    Projetos,
    Footer
  }
}
</script>


