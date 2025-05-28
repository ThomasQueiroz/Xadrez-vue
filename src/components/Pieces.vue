<script setup>
</script>

<template>
  <div class="card">
    <div class="card-header">
      <h2><i class="fas fa-chess-knight"></i> Peças e Movimentos</h2>
    </div>
    <div class="card-content">
      <div class="pieces-container">
        <div class="piece">
          <i class="fas fa-chess-king"></i>
          <div class="piece-name">Rei</div>
          <div class="piece-move">1 casa em qualquer direção</div>
        </div>
        <div class="piece">
          <i class="fas fa-chess-queen"></i>
          <div class="piece-name">Rainha</div>
          <div class="piece-move">Qualquer direção, quantas casas</div>
        </div>
        <div class="piece">
          <i class="fas fa-chess-rook"></i>
          <div class="piece-name">Torre</div>
          <div class="piece-move">Horizontal/vertical, quantas casas</div>
        </div>
      </div>
      <div class="pieces-container">
        <div class="piece">
          <i class="fas fa-chess-bishop"></i>
          <div class="piece-name">Bispo</div>
          <div class="piece-move">Diagonais, quantas casas</div>
        </div>
        <div class="piece">
          <i class="fas fa-chess-knight"></i>
          <div class="piece-name">Cavalo</div>
          <div class="piece-move">Movimento em "L"</div>
        </div>
        <div class="piece">
          <i class="fas fa-chess-pawn"></i>
          <div class="piece-name">Peão</div>
          <div class="piece-move">Para frente, captura na diagonal</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.pieces-container { 
    display: flex; 
    justify-content: space-around; 
    flex-wrap: wrap; 
    margin: 20px 0; 
}
.piece { 
    text-align: center; 
    margin: 15px; 
    width: 100px; 
}
.piece i { 
    font-size: 3rem; 
    color: #c19e5f; 
    margin-bottom: 10px; 
}
.piece-name { 
    font-weight: bold; 
    color: #e8e8e8; 
}
.piece-move { 
    font-size: 0.9rem; 
    color: #aaa; 
}
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