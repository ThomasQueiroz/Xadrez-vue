<script setup>

</script>

<template>
  <header>
    <h1><i class="fas fa-chess"></i> Xadrez: O Jogo dos Reis</h1>
    <p class="subtitle">Estratégia, tática e milênios de história em um tabuleiro de 64 casas</p>
  </header>
</template>

<style scoped>
header {
  background: rgba(0, 0, 0, 0.8);
  padding: 20px;
  text-align: center;
  border-bottom: 4px solid #c19e5f;
  top: 0;
  z-index: 100;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
}

h1 {
  font-size: 2.8rem;
  color: #e8e8e8;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

h1 i {
  color: #c19e5f;
  margin-right: 15px;
}

.subtitle {
  font-size: 1.2rem;
  color: #c19e5f;
  max-width: 800px;
  margin: 0 auto;
}
</style>