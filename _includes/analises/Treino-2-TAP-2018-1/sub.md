 <div id="sub">
 
 </div>
## K - Sub-prime

Resolva este problema:
[URI][uri-1105]{:target="_blank"}

<p align="justify">
O enunciado do problema começa explicando a versão clássica do jogo de Bingo e logo após apresenta uma nova versão chamada <b>A</b>lbert-<b>C</b>harles-<b>M</b>ary.  Nesta versão o caller sorteia uma primeira bola, coloca-a de volta no globo, sorteia uma segunda bola, coloca-a de volta no globo e então anuncia a diferença absoluta entre os números das duas bolas. O problema consiste em descobrir se é possível gerar todos os números de <b>0</b> até <b>N</b> através destas diferenças levando em consideração as <b>B</b> bolas que restaram dentro do globo.  Seja <b>bi</b> o valor de alguma bola <b>i</b> dentro do globo e <b>c</b> um valor entre <b>0</b> e <b>N</b> inclusive, <b>c</b> é gerado se existir alguma bola, dentro do globo, com o valor <b>bi + c</b>. Como o valor de <b>N</b> ≤ <b>90</b>, podemos olhar para todos os valores possíveis de <b>c</b>, ou seja, de <b>0</b> até <b>N</b> e verificar se o valor <b>bi + c</b> está dentro do globo.
</p>

Um exemplo de implementação segue abaixo:

{% gist wellvolks/a69aeb0ed5305b43040b44b84f829de9 sub-prime.cpp %}


[uri-1105]:		https://www.urionlinejudge.com.br/judge/pt/problems/view/1105
