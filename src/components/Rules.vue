<script setup>
</script>
<template>
  <div class="card">
    <div class="card-header">
      <h2><i class="fas fa-book"></i> Regras Básicas</h2>
    </div>
    <div class="card-content">
      <h3>Fundamentos do Jogo</h3>
      <p>O xadrez é jogado em um tabuleiro de 64 casas, alternando entre claras e escuras. Cada jogador começa com 16 peças: 1 rei, 1 rainha, 2 torres, 2 bispos, 2 cavalos e 8 peões.</p>
      <h3>Objetivo Principal</h3>
      <p>Dar <strong>xeque-mate</strong> no rei adversário. Isso ocorre quando o rei está sob ataque (em xeque) e não há movimento legal que o salve.</p>
      <h3>Movimentos Especiais</h3>
      <ul>
        <li>Roque: Protege o rei e desenvolve a torre</li>
        <li>En passant: Captura especial de peão</li>
        <li>Promoção: Peão que alcança a última linha vira outra peça</li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.card {
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid rgba(193, 158, 95, 0.2);
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
  border-color: rgba(193, 158, 95, 0.5);
}

.card-header {
  background: rgba(193, 158, 95, 0.2);
  padding: 20px;
  text-align: center;
  border-bottom: 1px solid rgba(193, 158, 95, 0.3);
}

.card-header h2 {
  font-size: 1.8rem;
  color: #e8e8e8;
}

.card-header i {
  color: #c19e5f;
  margin-right: 10px;
}

.card-content {
  padding: 25px;
}

.card-content h3 {
  color: #c19e5f;
  margin-bottom: 15px;
  font-size: 1.4rem;
}

.card-content p,
.card-content ul {
  line-height: 1.7;
  margin-bottom: 15px;
}

.card-content ul {
  padding-left: 25px;
}

.card-content li {
  margin-bottom: 10px;
}
</style>