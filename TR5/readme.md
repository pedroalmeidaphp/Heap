<h1 align="center"> Heap</h1>
<h2>Sobre o desafio:</h2>
<p>Foi dado um arquivo .h, com uma struct criada(que seria para a criação da heap), e 4 funções, e pedido que fosse implementado as funções de criar heap, de adicionar novo elemento de forma ordenada e de remover menor elemento em um arquivo .c, baseado na função de comparação que seria criada pelo professor e que não seria de conhecimento dos alunos.</p>
<h2>Sobre os arquivos:</h2>
<ul>
<li>heap.h: Arquivo contendo a estrutura, as funções a serem implementadas e a função de comparação</li>
<li>TR4_537674.c: Arquivo com as funções implementadas(exeto a de comparação)</li>
<li>main.c: Arquivo em são implementadas todas as funções inclusive a de comparação, e criado uma heap para teste</li>
<h2>Como executa-lo:</h2>
<p>Primeiramente é necessario que seja compilado a biblioteca criada, o que é possivel colocando o seguinte comenado no terminal:</p>
<p> <strong>gcc -c src/TR5_537674.c -o lib/ops.o</strong></p>
<p>Agora que a biblioteca foi gerada, basta que ela seja compilada junto à main, para que seja gerado o executavel:</p>
<p> <strong>gcc lib/ops.o src/main.c -o executavel_do_programa</strong></p>
<p>Por fim, para executar o programa, basta digitar:</p>
<p> <strong>./executavel_do_programa</strong></p>