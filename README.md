
Este é um código que implementa o jogo Flappy Bird usando JavaScript e manipulação do DOM (Document Object Model). Vou explicar um pouco sobre as principais partes do código:

Função novoElemento:

Esta função cria um novo elemento HTML com a tag e classe especificadas.
Função Barreira:

Esta função define um objeto Barreira, que consiste em uma div que representa a barreira.
Dentro do objeto, há dois elementos de div, um para a borda e outro para o corpo da barreira.
O método setAltura permite definir a altura do corpo da barreira.
Função ParDeBarreiras:

Esta função cria um par de barreiras, superior e inferior.
As barreiras são criadas com alturas aleatórias, mantendo uma abertura especificada.
Os métodos getX, setX e getLargura permitem obter e definir a posição horizontal e a largura do par de barreiras.
Função Barreiras:

Esta função cria um conjunto de pares de barreiras.
Os pares são criados com deslocamento horizontal entre eles para simular o movimento do jogo.
O método animar é responsável por mover as barreiras e verificar se o pássaro passou por uma abertura para contabilizar pontos.
Função Passaro:

Esta função define o objeto Passaro, que é representado por uma imagem de um pássaro.
O pássaro pode voar para cima quando uma tecla é pressionada e cai quando a tecla é solta.
O método animar move o pássaro para cima ou para baixo, dependendo da ação do jogador.
Função Progresso:

Esta função cria um elemento de texto para exibir o progresso do jogo (pontuação).
Função estaoSobrepostos:

Esta função verifica se dois elementos HTML estão sobrepostos na tela.
Função colidiu:

Esta função verifica se o pássaro colidiu com alguma das barreiras.
Função FlappyBird:

Esta função configura e inicia o jogo Flappy Bird.
Cria o elemento do jogo, incluindo o pássaro, as barreiras e o progresso.
Inicia um temporizador para animar as barreiras e o pássaro e verificar colisões.
O jogo é iniciado ao criar uma instância de FlappyBird e chamar seu método start. Durante o jogo, o jogador controla o pássaro para evitar colisões com as barreiras e acumular pontos ao atravessar as aberturas nas barreiras.

---IMG DO JOGO---

![image](https://github.com/Murilophy/Flappy-Bird/assets/137320364/cd0e35ff-2d1c-4e5d-9007-9f66dc1bb1e6)

