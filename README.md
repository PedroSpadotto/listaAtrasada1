# listaAtrasada1
Desculpa pelo atraso prof

Lista de exercícios número 1, todos foram feitos com x86

1) O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável
da versão atual que trabalhamos em aula e o que eles processam? 

GLSL é uma linguagem de programação utilizada para criar shaders e os dois tipos de shaders que são opcionais são Vertex e Fragment shading.

2) O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?

Primitivas Gráficas são argumento que usamos em draw calls, de acordo com este argumento a draw call irá interpretar os vértices de diferentes maneiras com a finalidade de desenhar uma forma específica, ou seja com base nisto sera feita a rasteirização. Nós armazenamos estes vértices em um VBO do Vertex Shader.

3) Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles). 

VBO: buffer responsavel pelos dados dos vértices, ou seja é um array onde as posições utilizadas nas primitivas gráficas são armazenados e enviados para a GPU

EBO: é um maneira diferente de utilizar os buffers de modo que por possuir uma lista com números que representam vértices, isto permite que números diferentes apontem para o mesmo vértice com a intenção de não existirem vértices repetidos ao desenhar certas formas

VAO: array que é responsável por conectar atributos (posição e cor por exemplo) do vértice com base na quantidade de bytes que vão receber determinado atributo, se relaciona com VBOs e EBOs pois os valores destes representam a posição que receberá certa cor por exemplo

4) Considerando o seguinte triângulo abaixo, formado pelos vértices P1, P2 e P3,
respectivamente com as cores vermelho, verde e azul. Adicionei uma imagem com os detalhes desta questão.
        
5) Analise o código fonte do projeto Hello Triangle. Localize e relacione os conceitos de
shaders, VBOs e VAO apresentados até então. Não precisa entregar nada neste exercício.

6) No código fonte do exercício 6 eu comentei as linhas que representam cada letra desta questão, então pra testar os diferentes desenhos é só comentar e descomentar as linhas relevantes. 

7) Questão 7 fiz normal, só compilar e rodar que deve estar funcionando. Criei os triângulos com os 9 vértices utilizando a primitiva de Triangle Fan.

8) Criei outro atributo pra cor no VS e alterei os buffers pra supportar dois atributos por index.

9) Utilizei diversas primitas para criar a casa. Principal alteração foi a criação de mais drawcalls e adicionando novos vértices.

10) Adicionei o arquivo do shader que criamos.
