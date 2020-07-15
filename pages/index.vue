<template>
  <div>
    <Cabecalho></Cabecalho>
    <div class="feed">
      <div class="feed__titulo">Últimas do blog</div>

      <Elemento titulo="Overpower Studios" projeto="Jogos para Android e iOS usando Unity 3D: Scorching Skies, Aces High e Kill Metal Racing"></Elemento>
      <Elemento titulo="Coffey" projeto="Treinamento em realidade virtual para Vale, usando Unity 3D"></Elemento>
      <Elemento titulo="REF Spatial" projeto="Aplicativo para Android nativo para auxiliar pesagem de animais em fazenda"></Elemento>
      <Elemento titulo="Engetower" projeto="Sistema de controle de projetos de engenharia, em Angular, Java, .NET e PostgreSQL"></Elemento>
      <Elemento titulo="Engetower" projeto="Sistema de conversão de torres em AutoCAD automatizado em servidor remoto, em .NET Core"></Elemento>

      <div class="feed__ver-mais">Ver mais...</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
.feed {
  width: 30rem;
  margin: 30px auto;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

.feed__titulo {
  margin-bottom: 2rem;
  font-size: x-large;
  font-weight: bold;
}

.feed__ver-mais {
  font-weight: bold;
  cursor: pointer;
}

.feed__ver-mais:hover {
  color: royalblue;
}
</style>
