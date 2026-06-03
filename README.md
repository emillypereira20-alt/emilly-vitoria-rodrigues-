# emilly-vitoria-rodrigues-
Projeto desenvolvido para o concurso Agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sustentabilidade na Agropecuária</title>

<style>
:root{
    --verde:#2e7d32;
    --verde-claro:#4caf50;
    --fundo:#f4f9f4;
    --texto:#222;
    --card:#ffffff;
}

.dark{
    --fundo:#121212;
    --texto:#f5f5f5;
    --card:#1e1e1e;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:var(--fundo);
    color:var(--texto);
    transition:.3s;
}

header{
    background:linear-gradient(135deg,var(--verde),var(--verde-claro));
    color:white;
    padding:30px;
    text-align:center;
}

nav{
    background:#1b5e20;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:10px;
    font-weight:bold;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:30px 0;
}

.card{
    background:var(--card);
    padding:25px;
    margin-bottom:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

h2{
    color:var(--verde);
    margin-bottom:15px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.kpi{
    text-align:center;
    padding:25px;
    border-radius:15px;
    background:linear-gradient(135deg,#66bb6a,#2e7d32);
    color:white;
}

.kpi h3{
    font-size:2rem;
}

button{
    padding:12px 20px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    margin:5px;
}

.dark-btn{
    background:#333;
    color:white;
}

.voice-btn{
    background:#2196f3;
    color:white;
}

.accessibility{
    position:fixed;
    right:20px;
    bottom:20px;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:20px;
}

ul{
    padding-left:20px;
}

@media(max-width:768px){
    header h1{
        font-size:1.8rem;
    }
}
</style>
</head>
<body>

<header>
    <h1>🌱 Sustentabilidade na Agropecuária</h1>
    <p>Produção Inteligente • Tecnologia • Inclusão • Meio Ambiente</p>
</header>

<nav>
    <a href="#introducao">Introdução</a>
    <a href="#objetivos">Objetivos</a>
    <a href="#tecnologia">Tecnologia</a>
    <a href="#acessibilidade">Acessibilidade</a>
    <a href="#dashboard">Dashboard</a>
</nav>

<div class="container">

<section id="introducao" class="card">
<h2>🌍 Introdução</h2>

<p>
A sustentabilidade na agropecuária busca equilibrar a produção de alimentos,
a preservação ambiental e o desenvolvimento econômico.
</p>

<br>

<p>
Com o uso de sensores IoT, drones, energia solar e sistemas inteligentes,
é possível produzir mais utilizando menos recursos naturais.
</p>

</section>

<section id="objetivos" class="card">

<h2>🎯 Objetivos</h2>

<ul>
<li>Reduzir impactos ambientais.</li>
<li>Economizar água e energia.</li>
<li>Aumentar a produtividade.</li>
<li>Promover inclusão digital.</li>
<li>Utilizar tecnologias sustentáveis.</li>
</ul>

</section>

<section id="tecnologia" class="card">

<h2>🛰️ Tecnologias Utilizadas</h2>

<div class="grid">

<div class="card">
<h3>📡 Sensores IoT</h3>
<p>Monitoramento de solo, temperatura e umidade.</p>
</div>

<div class="card">
<h3>🚁 Drones</h3>
<p>Análise aérea das plantações e pastagens.</p>
</div>

<div class="card">
<h3>☀️ Energia Solar</h3>
<p>Redução de custos energéticos.</p>
</div>

<div class="card">
<h3>📊 Dashboard</h3>
<p>Análise de dados em tempo real.</p>
</div>

</div>

</section>

<section id="acessibilidade" class="card">

<h2>♿ Recursos de Acessibilidade</h2>

<ul>
<li>🔊 Leitura por voz.</li>
<li>🔍 Aumento de fonte.</li>
<li>🌙 Modo escuro.</li>
<li>📱 Design responsivo.</li>
<li>👐 Compatível com Libras.</li>
<li>⌨ Navegação por teclado.</li>
</ul>

</section>

<section id="dashboard" class="card">

<h2>📈 Dashboard Sustentável</h2>

<div class="grid">

<div class="kpi">
<h3 id="agua">0%</h3>
<p>Economia de Água</p>
</div>

<div class="kpi">
<h3 id="energia">0%</h3>
<p>Energia Renovável</p>
</div>

<div class="kpi">
<h3 id="carbono">0%</h3>
<p>Redução de Carbono</p>
</div>

<div class="kpi">
<h3 id="produtividade">0%</h3>
<p>Aumento de Produção</p>
</div>

</div>

</section>

<section class="card">

<h2>📅 Cronograma</h2>

<table width="100%" border="1" cellpadding="10">

<tr>
<th>Etapa</th>
<th>Status</th>
</tr>

<tr>
<td>Pesquisa</td>
<td>✅ Concluído</td>
</tr>

<tr>
<td>Coleta de Dados</td>
<td>✅ Concluído</td>
</tr>

<tr>
<td>Implementação</td>
<td>🔄 Em andamento</td>
</tr>

<tr>
<td>Avaliação</td>
<td>⏳ Pendente</td>
</tr>

</table>

</section>

</div>

<div class="accessibility">

<button class="dark-btn" onclick="toggleDark()">
🌙 Modo Escuro
</button>

<button class="voice-btn" onclick="lerPagina()">
🔊 Ler Página
</button>

</div>

<footer>
    <p>🌱 Projeto Sustentabilidade na Agropecuária - 2026</p>
</footer>

<script>

function toggleDark(){
    document.body.classList.toggle("dark");
}

function animar(id, valor){

    let atual = 0;

    const elemento = document.getElementById(id);

    const intervalo = setInterval(() => {

        atual++;

        elemento.innerHTML = atual + "%";

        if(atual >= valor){
            clearInterval(intervalo);
        }

    },20);
}

animar("agua",85);
animar("energia",92);
animar("carbono",78);
animar("produtividade",88);

function lerPagina(){

    const texto = document.body.innerText;

    const voz = new SpeechSynthesisUtterance(texto);

    voz.lang = "pt-BR";

    speechSynthesis.speak(voz);
}

</script>

</body>
</html>
agro-sustentavel/
│
├── index.html
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── dashboard.js
│   └── acessibilidade.js
│
├── assets/
│   ├── imagens/
│   ├── icones/
│   └── videos/
│
├── backend/
│   ├── api/
│   ├── banco/
│   └── sensores/
│
└── docs/
    └── relatorio.pdf
