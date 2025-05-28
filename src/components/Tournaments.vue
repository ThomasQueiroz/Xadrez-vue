<script setup>
</script>

<template>
  <div class="card">
    <div class="card-header">
      <h2><i class="fas fa-trophy"></i> Torneios Importantes</h2>
    </div>
    <div class="card-content">
      <h3>Principais Competições</h3>
      <ul>
        <li><strong>Campeonato Mundial de Xadrez:</strong> Disputado desde 1886, determina o campeão mundial</li>
        <li><strong>Olimpíada de Xadrez:</strong> Competição por equipes nacionais, realizada a cada dois anos</li>
        <li><strong>Torneio de Candidatos:</strong> Define o desafiante ao título mundial</li>
        <li><strong>Grand Chess Tour:</strong> Série de torneios com os melhores jogadores do mundo</li>
      </ul>
      <h3>Campeões Atuais</h3>
      <ul>
        <li>Campeão Mundial: Dommaraju Gukesh (Índia)</li>
        <li>Campeã Mundial Feminina: Ju Wenjun (China)</li>
        <li>Campeão Mundial Júnior: Marc'Andria Maurizzi (França)</li>
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