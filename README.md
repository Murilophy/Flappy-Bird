🐦 Flappy Bird – Projeto em JavaScript

Bem-vindo ao Flappy Bird Clone, um jogo desenvolvido em HTML, CSS e JavaScript puro, com foco em manipulação avançada do DOM, lógica de jogos 2D e persistência de dados no navegador.

Este projeto evoluiu além de um simples clone: agora conta com tela de Game Over, sistema de recorde salvo no navegador, reinicialização dinâmica e melhorias estruturais no código.

🎮 Sobre o Jogo

Uma recriação do clássico Flappy Bird, onde o jogador controla um pássaro que deve atravessar barreiras sem colidir.

Cada barreira ultrapassada soma pontos. Ao colidir, o jogo exibe a pontuação final e permite reiniciar instantaneamente.

🚀 Funcionalidades Implementadas
🎯 Sistema de Pontuação

Contador dinâmico atualizado em tempo real

Exibição fixa no canto superior direito

🏆 Sistema de Recorde Persistente

Armazenamento usando localStorage

Recorde salvo mesmo após fechar o navegador

Exibição no canto superior esquerdo

Destaque animado quando um novo recorde é atingido

💀 Tela de Game Over

Overlay escuro semi-transparente

Exibição da pontuação final

Botão "Jogar Novamente"

Reinicialização completa do jogo sem recarregar a página

🔁 Reinício Automático

Estado do jogo reconstruído dinamicamente

Limpeza total da área antes de reiniciar

Nova instância criada via JavaScript

🛠 Melhorias Técnicas

Correção de erro de leitura de clientHeight

Inicialização protegida com window.onload

Proteções contra elementos null

Melhor organização estrutural do código

Separação visual clara entre HUD e área de jogo

🧠 Conceitos Aplicados

Este projeto utiliza:

🧩 Manipulação do DOM

Criação dinâmica de:

Pássaro

Barreiras

HUD (pontuação e recorde)

Tela de Game Over

🎮 Lógica de Jogo 2D

Gravidade simulada

Movimentação contínua com setInterval

Geração procedural de obstáculos

Detecção de colisão com getBoundingClientRect

💾 Persistência de Dados

Uso de localStorage

Controle de atualização de recorde

Comparação entre pontuação atual e melhor marca

🎨 Experiência do Usuário (UX)

Feedback visual ao bater recorde

HUD organizado para não atrapalhar a jogabilidade

Reinício rápido e fluido

🚀 Como Jogar

Abra o arquivo index.html no navegador;

Pressione Espaço para fazer o pássaro voar;

Desvie das barreiras;

Tente bater seu próprio recorde!

📂 Estrutura do Projeto
/css
    estilo.css
/js
    flappy.js
/imgs
    bird.png
    background.png
index.html
🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

Aprendizado de lógica de jogos

Organização de código JavaScript

Manipulação avançada do DOM

Estruturação de projetos para portfólio

Aplicação prática de persistência no navegador

É um excelente exercício para quem deseja evoluir como Front-End Developer.

🖼 Prévia do Jogo
<img width="1906" height="898" alt="image" src="https://github.com/user-attachments/assets/3cd9b757-8ba3-40c2-8221-947c85dcd4b0" />

🔮 Melhorias Futuras

🎵 Efeitos sonoros

🌈 Sistema de temas

📱 Versão mobile responsiva

⚡ Otimização com requestAnimationFrame

🏅 Sistema de ranking global

🧠 Refatoração para padrão orientado a classes ES6

📌 Status do Projeto

✅ Funcional
✅ Recorde persistente
✅ Tela de Game Over
✅ Código organizado
🚀 Em constante evolução

Se quiser, posso:

Deixar o README ainda mais chamativo (nível portfólio top GitHub)

Adicionar badges profissionais

Criar GIF animado para prévia

Adaptar para padrão de README de empresa

Esse projeto já está muito além de um simples exercício 👏🔥
