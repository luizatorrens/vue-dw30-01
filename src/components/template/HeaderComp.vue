<template>
  <header class="menu-superior">
    <div class="menu-esquerdo">
      <span> <RouterLink to="/">Home</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/times">Times</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/jogadores">Jogadores</RouterLink> </span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>

<style>
header span {
  padding: 0 20px;
}
.menu-superior {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
