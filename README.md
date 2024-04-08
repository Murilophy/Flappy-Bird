
Este é um código que implementa o jogo Flappy Bird usando JavaScript e manipulação do DOM (Document Object Model).
Vou explicar um pouco sobre a parte de javascript do código:

𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕟𝕠𝕧𝕠𝔼𝕝𝕖𝕞𝕖𝕟𝕥𝕠:

Esta função cria um novo elemento HTML com a tag e classe especificadas.

𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕟𝕠𝕧𝕠𝔼𝕝𝕖𝕞𝕖𝕟𝕥𝕠:

Esta função define um objeto Barreira, que consiste em uma div que representa a barreira.
Dentro do objeto, há dois elementos de div, um para a borda e outro para o corpo da barreira.
O método setAltura permite definir a altura do corpo da barreira.


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕟𝕠𝕧𝕠𝔼𝕝𝕖𝕞𝕖𝕟𝕥𝕠:

Esta função cria um par de barreiras, superior e inferior.
As barreiras são criadas com alturas aleatórias, mantendo uma abertura especificada.
Os métodos getX, setX e getLargura permitem obter e definir a posição horizontal e a largura do par de barreiras.


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕟𝕠𝕧𝕠𝔼𝕝𝕖𝕞𝕖𝕟𝕥𝕠:

Esta função cria um conjunto de pares de barreiras.
Os pares são criados com deslocamento horizontal entre eles para simular o movimento do jogo.
O método animar é responsável por mover as barreiras e verificar se o pássaro passou por uma abertura para contabilizar pontos.


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 ℙ𝕒𝕤𝕤𝕒𝕣𝕠:

Esta função define o objeto Passaro, que é representado por uma imagem de um pássaro.
O pássaro pode voar para cima quando uma tecla é pressionada e cai quando a tecla é solta.
O método animar move o pássaro para cima ou para baixo, dependendo da ação do jogador.


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 ℙ𝕣𝕠𝕘𝕣𝕖𝕤𝕤𝕠:

Esta função cria um elemento de texto para exibir o progresso do jogo (pontuação).


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕖𝕤𝕥𝕒𝕠𝕊𝕠𝕓𝕣𝕖𝕡𝕠𝕤𝕥𝕠𝕤:

Esta função verifica se dois elementos HTML estão sobrepostos na tela.


𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝕔𝕠𝕝𝕚𝕕𝕚𝕦:

Esta função verifica se o pássaro colidiu com alguma das barreiras.

𝔽𝕦𝕟𝕔̧𝕒̃𝕠 𝔽𝕝𝕒𝕡𝕡𝕪𝔹𝕚𝕣𝕕:

Esta função configura e inicia o jogo Flappy Bird.
Cria o elemento do jogo, incluindo o pássaro, as barreiras e o progresso.
Inicia um temporizador para animar as barreiras e o pássaro e verificar colisões.
O jogo é iniciado ao criar uma instância de FlappyBird e chamar seu método start. 
Durante o jogo, o jogador controla o pássaro para evitar colisões com as barreiras e acumular pontos ao atravessar as aberturas nas barreiras.


---𝑰𝑴𝑮 𝑫𝑶 𝑱𝑶𝑮𝑶---

![image](https://github.com/Murilophy/Flappy-Bird/assets/137320364/cd0e35ff-2d1c-4e5d-9007-9f66dc1bb1e6)

