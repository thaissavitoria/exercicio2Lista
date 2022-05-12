<h1>Exercício 2</h1>
<br>
<h1>Proposta:</h1>
<p> Crie uma lista linear que consiga armazenar um conjunto de 100 nomes quaisquer, os quis serão salvos de forma aleatória. Feito a estrutura, crie as seguintes ações:</p>
<ul>
  <li>Uma função que consiga identificar replicações na lista, ou seja, nomes iguais. Remova todas as réplicas sem mover os "ponteiros"</li>
  <li>Como você gerenciaria os espaços em branco para novas inserções? Qual seria o custo dessas novas inserções?</li>
  </ul>
 <br>
 <h1>Desenvolvimento:</h1>
 <br>
 <p>Vamos explicar o desenvolvimento do problema com um exemplo.</p>
 <p>O primeiro passo é criar ou anexar a pasta um arquivo .txt que cotenha os nomes que serão lidos. Para que o programa execute sem problemas, é necessário que coloque-se uma linha em branco extra após o fim dos nomes, assim como no exemplo da foto abaixo:</p>
 <img src="imgs/txt.jpg" alt=ExemploArquivoTxt>
 
<p>Após o comando para executar(make run), o programa cria uma lista e preenche todas as primeiras posições(posição 0) do vetor de caracteres nome que está armazenado dentro do vetor nomes.</p>
<img src="imgs/FLvazia.jpg" alt=FazListaVazia>
<p>Esse preenchimento será útil para o procedimento de remoção de nomes iguais posteriormente.</p>
<p> Então, o programa chama uma função que copia os nomes do arquivo "nomes.txt" para a lista inicializada anteriormente e imprime a lista após o fim das inserções.</p>
<p>O processo de impressão confere se o primeiro caracter do nome é diferente de "0", se for, ele imprime a string</p>
<p>No próximo passo, o programa chama um função que percorre o vetor de nomes presentes na lista e se encontra algum repetido, seta a primeira posição do seu vetor de caracteres nome para "0", o que o faz ser "excluído" do vetor nomes na lista(ele apenas não aparecerá na próxima impressão, que ocorre logo após).</p>
<p>Por último, o programa imprime novamente usando o critério citado anteriormente</p>
<br>
<h1>Questões:</h1>
<ol>
  <li>Como você gerenciaria os espaços em branco para as novas inserções?<li>

