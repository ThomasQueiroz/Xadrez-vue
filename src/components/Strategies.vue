<script setup>
</script>

<template>
  <div class="card centered-card">
    <div class="card-header">
      <h2><i class="fas fa-brain"></i> Estratégias</h2>
    </div>
    <div class="card-content">
      <h3>Princípios Fundamentais</h3>
      <ul>
        <li>Controle o centro do tabuleiro</li>
        <li>Desenvolva suas peças rapidamente</li>
        <li>Proteja seu rei (geralmente com roque)</li>
        <li>Não mova a mesma peça múltiplas vezes na abertura</li>
        <li>Evite bloquear seus bispos</li>
      </ul>
      <h3>Aberturas Clássicas</h3>
      <ul>
        <li>Ruy López (Abertura Espanhola)</li>
        <li>Siciliana</li>
        <li>Defesa Francesa</li>
        <li>Gambito da Dama</li>
      </ul>
      <h3>Finais Básicos</h3>
      <p>Dominar finais é essencial para converter vantagens. Os mais importantes incluem rei e peão vs rei, torre vs peão, e dama vs torre.</p>
    </div>
  </div>
</template>

<style scoped>
.centered-card { 
    width: 100%; 
    max-width: 800px; 
    margin: 0 auto; 
}
.card { 
    background: rgba(255, 255, 255, 0.05); 
    border-radius: 15px; overflow: hidden; 
    border: 1px solid rgba(193, 158, 95, 0.2); 
    transition: transform 0.3s, box-shadow 0.3s; 
}
.card-header { 
    background: rgba(193, 158, 95, 0.2); 
    padding: 20px; text-align: center; 
    border-bottom: 1px solid rgba(193, 158, 95, 0.3); 
}
.card-header h2 { 
    font-size: 1.8rem; 
    color: #e8e8e8; 
}
.card-content { 
    padding: 25px; 
}
.card-content h3 { 
    color: #c19e5f; 
    margin-bottom: 15px; 
    font-size: 1.4rem; 
}
.card-content ul { 
    padding-left: 25px; 
    margin-bottom: 20px; 
}
.card-content li { 
    margin-bottom: 10px; 
    line-height: 1.6; 
}
</style>