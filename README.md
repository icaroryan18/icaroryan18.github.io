<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Uso da IA nos Estudos de Matemática</title>
<style>
body{font-family:Arial,sans-serif;line-height:1.6;margin:0;background:#f4f6f8;color:#222}
header{background:#1f4e79;color:white;padding:35px 20px;text-align:center}
main{max-width:950px;margin:25px auto;padding:0 18px}
section{background:white;margin:18px 0;padding:25px;border-radius:12px;box-shadow:0 2px 8px #0001}
h2{color:#1f4e79}
.step{border-left:5px solid #1f4e79;padding-left:15px;margin:18px 0}
.formula{font-size:1.15rem;background:#eef4f8;padding:15px;border-radius:8px;text-align:center}
.flow{background:#fafafa;border:1px solid #ddd;padding:18px;border-radius:10px;text-align:center}
.flow div{padding:9px;margin:5px auto;max-width:500px;background:#eef4f8;border-radius:8px}
.flow .arrow{background:none;padding:0}
input{padding:10px;width:90px;margin:5px;border:1px solid #bbb;border-radius:6px}
button{padding:11px 18px;background:#1f4e79;color:white;border:0;border-radius:7px;cursor:pointer}
button:hover{opacity:.9}
#resultado{font-size:1.2rem;font-weight:bold;margin-top:15px}
footer{text-align:center;padding:25px;color:#666}
</style>
</head>
<body>
<header>
<h1>Uso da IA nos Estudos de Matemática</h1>
<p>Da resolução da distância entre pontos à criação de um protótipo web</p>
</header>

<main>
<section>
<h2>Apresentação</h2>
<p>Este trabalho demonstra como a Inteligência Artificial pode ser utilizada como ferramenta de apoio aos estudos de Matemática, especialmente na resolução de problemas envolvendo distância entre pontos e na transformação de um raciocínio matemático em um algoritmo e uma página web.</p>
</section>

<section>
<h2>Passo 2 — Exercício escolhido</h2>
<p><strong>Exercício do Livro 3 — Distância entre Pontos:</strong></p>
<p><em>Insira aqui o enunciado completo do exercício escolhido no Livro 3.</em></p>
</section>

<section>
<h2>Passo 3 — Resolução matemática</h2>
<p>Para calcular a distância entre dois pontos A(x₁,y₁) e B(x₂,y₂), utilizamos:</p>
<div class="formula">d = √[(x₂ − x₁)² + (y₂ − y₁)²]</div>
<p>Primeiro identificamos as coordenadas dos pontos. Depois substituímos os valores na fórmula, realizamos as subtrações, elevamos ao quadrado, somamos os resultados e, por fim, calculamos a raiz quadrada.</p>
</section>

<section>
<h2>Passo 4 — Algoritmo em texto</h2>
<ol>
<li>Iniciar.</li>
<li>Receber as coordenadas x₁ e y₁ do ponto A.</li>
<li>Receber as coordenadas x₂ e y₂ do ponto B.</li>
<li>Calcular a diferença entre as coordenadas x.</li>
<li>Calcular a diferença entre as coordenadas y.</li>
<li>Elevar as duas diferenças ao quadrado.</li>
<li>Somar os dois resultados.</li>
<li>Calcular a raiz quadrada da soma.</li>
<li>Exibir a distância entre os pontos.</li>
<li>Finalizar.</li>
</ol>
</section>

<section>
<h2>Passo 5 — Fluxograma</h2>
<div class="flow">
<div>INÍCIO</div><div class="arrow">↓</div>
<div>Receber A(x₁,y₁) e B(x₂,y₂)</div><div class="arrow">↓</div>
<div>Calcular Δx = x₂ − x₁ e Δy = y₂ − y₁</div><div class="arrow">↓</div>
<div>Calcular Δx² + Δy²</div><div class="arrow">↓</div>
<div>Calcular d = √(Δx² + Δy²)</div><div class="arrow">↓</div>
<div>Exibir a distância d</div><div class="arrow">↓</div>
<div>FIM</div>
</div>
</section>

<section>
<h2>Passo 6 — Verificação do fluxo</h2>
<p>O fluxo precisa considerar que as diferenças entre as coordenadas podem ser negativas. Isso não causa problema porque elas são elevadas ao quadrado antes da soma. Assim, o algoritmo funciona para pontos em qualquer região do plano cartesiano.</p>
</section>

<section>
<h2>Passo 7 e 8 — Algoritmo e aplicação</h2>
<p>Use o calculador abaixo para inserir os pontos do exercício escolhido e comparar o resultado com sua resolução manual.</p>
<label>A: <input id="x1" type="number" step="any" placeholder="x₁"> <input id="y1" type="number" step="any" placeholder="y₁"></label><br>
<label>B: <input id="x2" type="number" step="any" placeholder="x₂"> <input id="y2" type="number" step="any" placeholder="y₂"></label><br><br>
<button onclick="calcular()">Calcular distância</button>
<div id="resultado"></div>
</section>

<section>
<h2>Algoritmo estruturado (pseudocódigo)</h2>
<pre>
INÍCIO
  leia x1, y1
  leia x2, y2
  dx ← x2 - x1
  dy ← y2 - y1
  distancia ← √(dx² + dy²)
  escreva distancia
FIM
</pre>
</section>

<section>
<h2>Passo 9 — Conclusão</h2>
<h3>Vantagens e desvantagens</h3>
<p>A IA pode ajudar a organizar ideias, transformar um raciocínio em algoritmo, criar fluxogramas e gerar protótipos rapidamente. Como limitação, uma resposta gerada por IA pode conter erros ou interpretar incorretamente o problema, por isso é necessário conferir os cálculos e compreender o conteúdo.</p>

<h3>Visão do profissional de TI</h3>
<p>Um desenvolvedor pode utilizar o fluxograma e o protótipo HTML como ponto de partida para um aplicativo mais completo, acrescentando validação de dados, acessibilidade, interface responsiva, testes automatizados, armazenamento de informações e outros recursos.</p>

<h3>Controle e propriedade intelectual</h3>
<p>Fornecer os passos matemáticos à IA é importante porque mantém o estudante no controle do raciocínio e permite que a tecnologia seja usada como ferramenta de apoio. A IA pode ajudar a transformar as ideias em código, mas o conhecimento matemático, a conferência dos resultados e a decisão sobre o que será apresentado permanecem fundamentais para a autoria e a qualidade do trabalho.</p>
</section>
</main>

<footer>Projeto escolar — Uso da IA nos Estudos de Matemática</footer>

<script>
function calcular(){
  const x1=Number(document.getElementById('x1').value);
  const y1=Number(document.getElementById('y1').value);
  const x2=Number(document.getElementById('x2').value);
  const y2=Number(document.getElementById('y2').value);
  if([x1,y1,x2,y2].some(Number.isNaN)){
    document.getElementById('resultado').textContent='Preencha as quatro coordenadas.';
    return;
  }
  const d=Math.sqrt((x2-x1)**2+(y2-y1)**2);
  document.getElementById('resultado').textContent='Distância = '+d;
}
</script>
</body>
</html>
