<script setup>
</script>

<template>
  <div class="card">
    <div class="card-header">
      <h2><i class="fas fa-landmark"></i> História</h2>
    </div>
    <div class="card-content">
      <h3>Origens e Evolução</h3>
      <p>O xadrez tem suas raízes no antigo jogo indiano <strong>Chaturanga</strong> (século VI), que representava as quatro divisões do exército indiano: infantaria, cavalaria, elefantes e carruagens.</p>
      <h3>Expansão Mundial</h3>
      <ul>
        <li>Século X: Chega à Europa através da Pérsia e do mundo árabe</li>
        <li>Século XV: Regras modernas estabelecidas na Espanha e Itália</li>
        <li>1851: Primeiro torneio internacional em Londres</li>
        <li>1924: Fundação da FIDE (Federação Internacional de Xadrez)</li>
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