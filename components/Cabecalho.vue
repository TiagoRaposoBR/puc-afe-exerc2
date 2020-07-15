<template>
  <div class="cabecalho">
    <div class="cabecalho__menu">
      <span class="cabecalho__menu--item">Blog</span>
      <span class="cabecalho__menu--item">Sobre</span>
      <span class="cabecalho__menu--item">Descrição</span>
    </div>
    <div class="cabecalho__imagem">
      <img class="cabecalho__imagem--img" src="../assets/Perfil.jpg" alt />
    </div>
    <div class="cabecalho__texto">
      <div class="cabecalho__texto--titulo">Tiago Raposo</div>
      <div class="cabecalho__texto--descricao">
          Formado em Jogos Digitais pela PUC Minas, tenho experiência em vários projetos diferentes, não limitados a estes: jogos comerciais para Android e iPhone, aplicações em realidade virtual e aumentada, sistemas full-stack, aplicativos nativos para Android e plugins para engenharia civil.
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>

<style scoped>

.cabecalho {
	width: 100%;
	height: 20rem;
	background-color: royalblue;
	font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	color: antiquewhite;
}

.cabecalho__menu {
    font-size: medium;
    margin: 0px auto 20px auto;
    width: fit-content;
}

.cabecalho__menu--item {
    margin: 8px 30px;
    display: inline-block;
    cursor: pointer;
}

.cabecalho__menu--item:hover {
    font-weight: bold;
}

.cabecalho__imagem {
    width: 40%;
    float: left;
}

.cabecalho__imagem--img {
    width: 200px;
    height: 206px;
    float: right;
    margin: 0 20px;
}

.cabecalho__texto {
	text-align: left;
}

.cabecalho__texto--titulo {
    font-size: xxx-large;
    margin-bottom: 1rem;
}

.cabecalho__texto--descricao {
	font-size: small;
    width: 40%;
    text-align: justify;
    display: inline-block;
}
</style>