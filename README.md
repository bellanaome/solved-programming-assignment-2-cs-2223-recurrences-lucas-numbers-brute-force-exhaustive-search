Download Link: https://assignmentchef.com/product/solved-programming-assignment-2-cs-2223-recurrences-lucas-numbers-brute-force-exhaustive-search
<br>
<ol>

 <li>Consider the recurrence <em>R</em>(<em>n</em>) = 4<em>R</em>(<em>n </em>− 1) − 3<em>R</em>(<em>n </em>− 2) with initial conditions</li>

</ol>

<em>R</em>(0) = 2 and <em>R</em>(1) = 8.                                                                               (4 Points)

Find its characteristic equation, and use it to create a formula for the recurrence that depends only on <em>n</em>, i.e. is not recursive.

What is the recurrence’s order of growth? Use Θ(<em>n</em>) if you can.

<ol start="2">

 <li>The Lucas numbers, named for 19th century French mathematician Edouard´ Lucas, are defined exactly as the Fibonacci numbers, except that they have ever-so-slightly different initial conditions. The Lucas numbers are given by:</li>

</ol>

<em>L</em>(0) = 2

<em>L</em>(1) = 1

<em>L</em>(<em>n</em>) = <em>L</em>(<em>n </em>− 1) + <em>L</em>(<em>n </em>− 2) for <em>n &gt; </em>1

Write a C++ program that accepts as input a value <em>n </em>and writes as output the sequence <em>L</em>(0)<em>,L</em>(1)<em>,…,L</em>(<em>n</em>). Your program should compute the values recursively with a separate function that uses the definition above. You may

hardcode the initial conditions.                                                                (7 Points)

What else is Lucas known for?

<ol start="3">

 <li>Use the <strong>clock() </strong>function from <em>&lt; time.h &gt; </em>to investigate the order of growth of your recursive algorithm that computes the Lucas numbers. (11 Points)

  <ul>

   <li>Extend your program from Part 2 above to determine the time needed to compute each of the first 30 Lucas numbers. (You are encouraged to go higher!) Display these results for each <em>n </em>on the standard console output.</li>

   <li>Have your code examine the ratio of successive calculations, i.e. <sup>Time(</sup><sub>Time(</sub><em><sup>L</sup><sub>L</sub></em><sup>(<em>n</em></sup><sub>(</sub><sup>+1))</sup><em><sub>n</sub></em><sub>)) </sub>.</li>

  </ul></li>

</ol>

Do you recognize this number?

What is the order of growth of your algorithm?

1

<ol start="4">

 <li>The Suribachs Magic Square–pictured below–is an interesting construction.While not <em>technically </em>a magic square, its rows, columns, diagonals, corners, center, and “postage stamps” do all have the same sum. In fact, there are many other <em>combinations </em>in the square that also have this sum. (18 Points)

  <ul>

   <li>Write a C++ program that counts all the 4-element combinations that have the same sum as the rows/columns, etc.</li>

   <li>Add to your program so that you can count all combinations with this sum. Some will have fewer than 4 elements, some will have exactly 4 elements, some will have more than 4 elements. Count them all.</li>

   <li>Make yet another addition to your program that counts the number of ways every possible sum can be formed. Include 0 as a possible sum; the largest sum will be created by summing every cell of the square.</li>

   <li>What sum can be created with the greatest number of combinations, and how many combinations is that? Notice anything interesting about that?</li>

  </ul></li>

</ol>

Bonus: The Suribachs Magic Square is fascinating. Your investigations might have piqued your curiosity about it. Write (and document!) a C++ program investigating some aspect of it not covered here, <em>or </em>write a 1-page report detailing where it can be found, explaining why it is named what it is named, and discussing its “mystical” significance. (2 Bonus Points)