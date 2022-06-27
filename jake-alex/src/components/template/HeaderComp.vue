<template>
  <header>
    <div class="menu-esquerdo">
      <span> <RouterLink to="/">Livros</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/times">Autores</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/jogadores">Mais Vendidos</RouterLink> </span>
    </div>
    <div class="menu-direito">
      <input type="text" v-model="pesquisa" />
    </div>
  </header>
</template>

<style>
header span {
  padding: 0 20px;
}

header {
  background-color: #000000;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: rgb(255, 0, 0);
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>