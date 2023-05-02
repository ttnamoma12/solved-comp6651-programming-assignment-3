Download Link: https://assignmentchef.com/product/solved-comp6651-programming-assignment-3
<br>
The World Chess Federation (F.I.D.E) are planning the World Chess Championship. tournament. One of the constraints they need to respect is to pair chess players from different countries. There are <em>N </em>professional chess players numbered from 0 to <em>N </em>−1 . FIDE does not have information about the citizenship of each chess player but they do know have some information about which players belong to the same country. Your task is to compute the number of ways possible to play a match between 2 players from different countries. You are provided with enough number of pairs so you succeed in your mission even though you don’t know their citizenship right away. For example, if the players 1 , 2 and 3 are from the same country then the 2 pairs (1<em>,</em>2) and (2<em>,</em>3) give sufficient information and the third pair (1<em>,</em>3) is not needed.

<h1>1        Input and Output</h1>

The first line contains two integers, <em>N </em>and <em>I </em>separated by a single space. <em>I </em>lines follow. Each line contains 2 integers <em>A </em>and <em>B </em>separated by a single space such that

<h2>0 ≤ A,B ≤ N − 1</h2>

1 ≤ <em>N </em>≤ 10<sup>5</sup>

1 ≤ <em>I </em>≤ 10<sup>4</sup>

<em>A </em>and <em>B </em>are chess players from the same country. The input should be taken from a separate input file. The output should be a single line displaying the number of permissible ways to choose a pair of chess players. There is no need to write it in a separate output file. You can display it on the console.

<h1>2       Sample Input</h1>

5 2

0 1

<ul>

 <li>3</li>

</ul>

1

<ul>

 <li><strong>Sample Output</strong></li>

</ul>

8

<h1>4       Explanation</h1>

We have the following pairs (0<em>,</em>2)<em>,</em>(0<em>,</em>3)<em>,</em>(1<em>,</em>2)<em>,</em>(1<em>,</em>3)<em>,</em>(0<em>,</em>4)<em>,</em>(1<em>,</em>4)<em>,</em>(2<em>,</em>4)<em>,</em>(3<em>,</em>4) where players are from different countries in each pair.

2