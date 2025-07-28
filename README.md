# Diario-de-aprendizado
 um projeto pessoal onde eu, Vinicius Anderson (vinniscodes), registro minha jornada no universo da programação. Mais do que um simples bloco de notas, este é um sistema interativo e visualmente imersivo feito para me ajudar a acompanhar cursos, anotar insights e monitorar meu tempo de estudo diário.


🛠️ Stack Tecnológica e Como o Projeto Funciona

Esse projeto é todo feito só com HTML, CSS e JavaScript — ou seja, 100% front-end. Aqui vai o resumo do que foi usado e como:

🧱 HTML5: Estrutura do Site
Usei tags semânticas como <header>, <main>, <section>, <footer> pra deixar o código mais organizado e fácil de entender.

Os inputs (<input>, <textarea>) e botões (<button>, <a>) são a parte da interface onde o usuário interage.

Recursos externos tipo Google Fonts, Font Awesome, CSS externo e Particles.js são puxados com <link> e <script>.

🎨 CSS3: Visual Neon/Cyberpunk
Estilo todo baseado em cores neon, tipo aquele visual cyberpunk.

Usei variáveis CSS (no :root) pra facilitar a troca de cores e manutenção.

O layout é feito com Grid e Flexbox, então o site se adapta bem em qualquer tela.

Tem animações com @keyframes e transições pra deixar os botões, títulos e outros elementos mais vivos.

Pseudoelementos ::before e ::after ajudam a criar efeitos tipo brilho sem precisar colocar mais HTML.

🧠 JavaScript: Funcionalidade e Lógica
Faço toda a parte de interação usando document.getElementById() e addEventListener() — escuto cliques, inputs, etc.

Os dados ficam salvos no navegador usando Local Storage:

Cursos ficam no array cursos, salvos na chave 'vinniscodesCursos'.

Notas ficam no array notas, salvos na chave 'vinniscodesNotas' (cada nota tem um ID único).

Check-in diário salva o tempo de estudo e histórico em 'vinniscodesCheckinDiaAtual' e 'vinniscodesCheckinHistorico'. Um setInterval() atualiza o cronômetro todo segundo.

Sempre que o usuário faz alguma ação, uso uma função showNotification() pra dar retorno visual (tipo "salvo com sucesso", "preencha o campo", etc).

Também tem validação nos inputs, pra garantir que os dados digitados fazem sentido.

🌌 Particles.js
Usei pra criar um fundo animado com partículas que interagem com o mouse. Dá aquele toque mais tecnológico pro site.