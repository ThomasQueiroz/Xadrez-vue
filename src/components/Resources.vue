<script setup>
const resources = [
  {
    name: 'Lichess',
    link: 'https://lichess.org',
    desc: 'Plataforma gratuita e open-source para jogar e aprender xadrez, com ferramentas de análise e treinamento.'
  },
  {
    name: 'Chess.com',
    link: 'https://chess.com',
    desc: 'Maior comunidade de xadrez online, com aulas, torneios e partidas contra jogadores de todo o mundo.'
  },
  {
    name: 'Chessable',
    link: 'https://www.chessable.com',
    desc: 'Cursos de xadrez baseados em ciência para todos os níveis, do iniciante ao grande mestre.'
  }
]
</script>

<template>
  <section class="resources">
    <h2><i class="fas fa-graduation-cap"></i> Recursos para Aprender</h2>
    <div class="resources-list">
      <div class="resource" v-for="(res, i) in resources" :key="i">
        <a :href="res.link" target="_blank">{{ res.name }}</a>
        <p>{{ res.desc }}</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.resources {
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  padding: 30px;
  margin: 40px 0;
  border: 1px solid rgba(193, 158, 95, 0.2);
}
.resources h2 {
  text-align: center;
  margin-bottom: 25px;
  color: #e8e8e8;
  font-size: 1.8rem;
}
.resources-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
.resource {
  background: rgba(0, 0, 0, 0.2);
  padding: 20px;
  border-radius: 10px;
  transition: background 0.3s;
}
.resource:hover {
  background: rgba(193, 158, 95, 0.1);
}
.resource a {
  color: #c19e5f;
  text-decoration: none;
  font-weight: bold;
  display: block;
  margin-bottom: 10px;
}
.resource a:hover {
  text-decoration: underline;
}
.resource p {
  color: #ccc;
  font-size: 0.95rem;
}
</style>