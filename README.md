# 🐦 Flappy Bird Clone
### 🎮 Um jogo 2D desenvolvido com JavaScript puro

<p align="center">
  <img width="1885" height="874" alt="image" src="https://github.com/user-attachments/assets/abf0d4f0-87f4-4e26-8664-af68f2269b5f" />
</p>

<p align="center">
  <strong>Manipulação avançada do DOM • Lógica de jogo • Persistência com localStorage • UX aprimorada</strong>
</p>

---

# 📌 Sobre o Projeto

Este projeto é uma recriação do clássico **Flappy Bird**, desenvolvido utilizando apenas:

- ✅ HTML  
- ✅ CSS  
- ✅ JavaScript puro (Vanilla JS)

O objetivo foi evoluir além de um simples clone, implementando melhorias estruturais, sistema de recorde persistente, tela de Game Over dinâmica e organização profissional de código.

---

# 🚀 Funcionalidades Implementadas

## 🎯 Sistema de Pontuação
- Contador atualizado em tempo real
- Exibição fixa no canto superior direito
- Atualização automática ao ultrapassar barreiras

---

## 🏆 Sistema de Recorde Persistente
- Armazenamento utilizando `localStorage`
- Recorde salvo mesmo após fechar o navegador
- Exibição no canto superior esquerdo
- Destaque animado ao atingir novo recorde
- Comparação automática entre pontuação atual e melhor marca

---

## 💀 Tela de Game Over
- Overlay escuro semi-transparente
- Exibição da pontuação final
- Botão **"Jogar Novamente"**
- Reinicialização completa sem recarregar a página
- Feedback visual para novo recorde

---

## 🔁 Sistema de Reinicialização
- Reconstrução completa do estado do jogo
- Limpeza dinâmica da área de jogo
- Nova instância criada via JavaScript
- Experiência fluida e sem refresh

---

# 🧠 Conceitos Técnicos Aplicados

## 🎮 Lógica de Jogo 2D
- Simulação de gravidade
- Movimentação contínua com `setInterval`
- Geração procedural de barreiras
- Detecção de colisão com `getBoundingClientRect`

---

## 🧩 Manipulação Avançada do DOM
- Criação dinâmica de elementos:
  - Pássaro
  - Barreiras
  - HUD (pontuação e recorde)
  - Tela de Game Over
- Atualizações visuais em tempo real
- Separação clara entre lógica e renderização

---

## 💾 Persistência de Dados
- Uso estratégico de `localStorage`
- Controle de atualização de recorde
- Renderização condicional para novo recorde

---

## 🛠 Melhorias Estruturais
- Correção de erro de `clientHeight`
- Inicialização protegida com `window.onload`
- Proteções contra elementos `null`
- Organização modular das funções construtoras
- HUD reposicionado para melhor experiência do jogador

---

# 🎮 Como Jogar

1. Abra o arquivo `index.html`
2. Pressione **Espaço** para fazer o pássaro voar
3. Desvie das barreiras
4. Tente bater seu próprio recorde 🏆

---

## 📂 Estrutura do Projeto

```bash
Flappy Bird/
├── css/
│   ├── estilo.css
│   └── flappy.css
├── fonts/
│   └── Oswald-Regular.ttf
├── html/
│   └── flappy.html
├── imgs/
│   └── passaro.png
├── js/
│   └── flappy.js
└── README.md
```

---

# 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Aprimorar lógica de programação
- Consolidar manipulação avançada do DOM
- Aplicar conceitos reais de jogos 2D
- Trabalhar persistência de dados no navegador
- Estruturar código para portfólio profissional

---

# 🔮 Próximas Melhorias

- 🎵 Implementação de efeitos sonoros
- 📱 Versão responsiva para mobile
- ⚡ Migração para `requestAnimationFrame`
- 🏅 Sistema de ranking global
- 🎨 Sistema de temas personalizados
- 🧠 Refatoração para ES6 Classes

---

# 📊 Status do Projeto

| Funcionalidade              | Status |
|-----------------------------|--------|
| Sistema de Pontuação        | ✅     |
| Game Over Dinâmico          | ✅     |
| Reinicialização sem Refresh | ✅     |
| Recorde Persistente         | ✅     |
| Destaque Novo Recorde       | ✅     |
| Organização Estrutural      | ✅     |

---

# 👨‍💻 Desenvolvido por

**Murilo Oliveira**  
Full-Stack Developer em evolução 🚀  

---

<p align="center">
  <strong>Se este projeto te ajudou ou te inspirou, deixe uma ⭐ no repositório!</strong>
</p>
