# listaAtrasada1
Desculpa pelo atraso prof

Lista de exercícios número 1

1) O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável
da versão atual que trabalhamos em aula e o que eles processam? 

GLSL é uma linguagem de programação utilizada para criar shaders e os dois tipos de shaders que são opcionais são Vertex e Fragment shading.

2) O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?

Primitivas Gráficas são argumento que usamos em draw calls, de acordo com este argumento a draw call irá interpretar os vértices de diferentes maneiras com a finalidade de desenhar uma forma específica, ou seja com base nisto sera feita a rasteirização. Nós armazenamos estes vértices utilizando os Vertex Shaders.

3) Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles). 



4) Considerando o seguinte triângulo abaixo, formado pelos vértices P1, P2 e P3,
respectivamente com as cores vermelho, verde e azul.
        a. Descreva uma possível configuração dos buffers (VBO, VAO e EBO) para
representá-lo.
        b. Como estes atributos seriam identificados no vertex shader?
        
5) Analise o código fonte do projeto Hello Triangle. Localize e relacione os conceitos de
shaders, VBOs e VAO apresentados até então. Não precisa entregar nada neste exercício.
