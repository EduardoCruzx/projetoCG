# projetoCG
Projeto CG BCC-So 2017/1

Alunos: Eduardo Cruz, João Franciso de Paula, Gabriel Piovani

Projeto Final:
    -Bibliote utilizada: WebGL
    -Divisão de tarefas: A teoria e o temas foram discutidos informalmente entre os membros do grupo através de um grupo de chat criado e de conversas pessoais, assim como os métodos a serem implementados em cada fase.Como o aluno Eduardo Cruz possía um previo conhecimento na linguagem JavaScript(a linguagem utilizada pela biblioteca), ele ficou a cargo da implementação dos métodos discutidos.
    -As nossas maiores dificuldades foram de abstrair os conceitos passados em aula e passá-los para a lógica especificada em cada fase, e no fim, juntar e criar um projeto abrangindo tudo e que fizesse algum sentido(um cenário plausível).Ao longo das fases algumas mudanças e adaptações foram feitas.




Parte 1: Visualização de um modelo em 3d fornecido por um exemplo

    - Objeto conseguido através do site three.js, usando webgl, linguagem javascript.

Parte 2: Visualização de 2 objetos com animação na mesma cena

    - Mais um objeto, do tipo .obj adicionado, podendo ser trocado por qualquer outro,
    desde que sejam importadas devidamente suas texturas.

    - Luzes adicionadas, uma em cada dimensão. 

    - A câmera se move no eixo x automaticamente e pode ser controlada no eixo y com o mouse.

    - Um dos objetos está rotacionado no eixo y, e está em seu tamanho original.
    O outro está rotacionado no eixo z, e seu tamanho foi diminuído pela metade. Nas três dimensões.

    Atualização: 
        
        - Foi retirada a função de alteração de câmera no eixo y com o mouse, para evitar confusão do 
        usuário. No lugar foi colocada uma movimentação automática.

        - O primeiro objeto agora gira em seu eixo y durante a animação.
        - O segundo objeto agora aumenta e diminui de tamanho durante a animação.

Parte 3: Visualização de 4 objetos com animação na mesma cena e mais de uma câmera.

    - Nesta atividade, adicionamos mais dois objetos na cena, alteramos as posições para que os 4 objetos ficassem
      como um quadrado.

    - Adicionamos luzes na posição negativa de cada dimensão, ficando 6 no total, para uma melhor Visualização
      dos objetos quando alguma câmera trazeira for selecionada.

    - Adicionamos mais 3  câmera, ficando 4 no total. E ao invés de a câmera olhar para a cena, agora ela olha 
      para um objeto, cada uma olhando para um.

    - Também adicionamos a troca de câmera por meio de um clique com o botão esquerdo do mouse.

Parte 4: Visualização de objeto movendo-se em curva.

    - Nessa etapa adicionamos um caminho curvo, utilizando uma Curva de Bezier e setamos o objeto Female2 para
      percorrer essa curva.

    - Para uma melhor visualização, distribuímos os outros objetos em linha reta, para contrastar com que
      percorre a curva. 

    - Para as próximas fases planejamos replicar as curvas em mais objetos e adicionar o chão e o céu, para melhorar
      a imersão.

    Obs: A fase 4 foi finalizada no dia 09/06/17 como previsto. Porém ao tentar entregar, percebemos que o campus
    estava sem internet (que só voltou no dia seguinte), e só por motivos de esquecimento, não entregamos até hoje.
    Porém, pode ser observado que a data de alteração dos arquivos, é de 09/06/17.

Parte 5: Pessoa se movimentando no interior de uma cabana de pedra.

    - O ambiente da cabana será retangular

    - Utilizamos três objetos carregados de arquivos: uma pessoa, um inseto e quatro tochas (das quais saem fumaça do fogo)

    - Como forma simples inserimos um círculo em uma das paredes, que simula um portal para outra dimensão

    - A pessoa se move dentro do quarto; o portal se move sobre a parede de acordo com a entrada do usuário via teclado (setas
      direcionais) e o inseto se movimenta de um lado para outro utilizando a curva de bézier.
