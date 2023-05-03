Download Link: https://assignmentchef.com/product/solved-cs317-homework-1
<br>
<ul>

 <li>Draw a flowchart of Algorithm Design and Analysis Process. (5 points)</li>

</ul>




<ul>

 <li>What is a Basic Operation? Why do we need to count basic operations? Give few examples of basic and non-basic operations.   (5 points)</li>

</ul>




<ul>

 <li>Arrange the running time of functions mentioned below by the order (increasing) of their growth. (5 points) n<sup>3 </sup>, n, nlog(n) , log(n), 2<sup>n</sup>, n<sup>2</sup>, n!</li>

</ul>




<ul>

 <li>Solve the following problems. (10 points)</li>

</ul>

#1)

#2)




5)

What the three asymptotic notations that are used to compare and rank the order of growth of algorithms?  Explain them <strong>in plain English</strong> with one example each.  (5 points)




<ul>

 <li>Give the list of basic asymptotic efficiency classes. (5 points)</li>

</ul>




<ul>

 <li>Give the general plan for analyzing the non-recursive algorithms. (5 points)</li>

</ul>




<ul>

 <li>Give the general plan for analyzing the recursive algorithms. (5 points)</li>

</ul>




<ul>

 <li>Consider the following 3 algorithms and answer the (a) to (d) questions for each algorithm. (15 points)</li>

</ul>







<ul>

 <li>Give the pseudo code of the factorial function F (n) = n! Analyzethis algorithm, i.e. setup a recurrence relation and solve it to find the running time in <em>Θ</em>  (10 points)</li>

 <li>Design an algorithm (write in pseudo code) which takes less than <em>Θ</em><sub>(</sub><em>n</em><sub>)</sub> to search an entry (name of a person) in a telephone directory. Analyze this algorithm for its worst-case input situation. Make necessary assumptions to simplify your comparisons<strong>.</strong> If you don’t know what is a telephone directory, check out this link <a href="https://en.wikipedia.org/wiki/Telephone_directory">https://en.wikipedia.org/wiki/Telephone_directory</a> (10 points)</li>

 <li>Design an <em>Θ</em><sub>(</sub><em>n</em><sub>)</sub> algorithm to determine if the given array is already sorted or not. Analyze this algorithm for its worst-case input. Setup the summation and solve it. (10 points)</li>

 <li>Write down the pseudo code of any decrease-and-conquer type sorting algorithm and analyze the running time of this algorithm for its worst-case input scenario. Also mention the running time of this algorithm for its best and average case input scenarios. (10 points)</li>

 <li>Write a BubbleSort program using the language of your choice tosort the given list and demonstrate the understanding of debugging techniques using any modern IDE such as JetBrains or Microsoft Visual Studio. (10 points)</li>

</ul>

<u>Instructions:</u> Use the following numbers as input to your BubbleSort program.

6, 8, 10, 4, 3, 5

Bubble Sort algorithm uses two loops. Set a conditional break point as shown below at the inner most loop <u>such that it will stop after 3 passes</u> of the outer loop are completed.

Once your program stops after completion of 3 passes, show the current state of your input array using a watch window. That is showing a partially sorted array as below:

Now, use an “Evaluate Expression” or “Quick Watch” feature of the IDE you are using to evaluate the basic operation of the Bubble sort algorithm.

<u>Deliverables:</u>

 Your program’s source code and output (2 points)  Fours Screenshots (8 points):

o 3 screenshots as shown above o one screenshot of the complete IDE window.

15) Convert the “Brute Force Password Generation” program covered in the class from C# to your favorite language. For this particular program, you can use any programming language such as Ruby, Java, Python, C++ etc., but you cannot use C# as the program is already given in C#.   Run this program for password of lengths 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 15, 20, 25, 30 and 35 etc. Record the execution time of this program in milliseconds for each of this password length using <strong>Empirical or Experimental Analysis</strong> technique shown in the class. Record the execution time in the table below.  (10 points) Notes:

<ul>

 <li>You do not need to convert the program line by line. You are allowed some flexibility/creativity on it.</li>

 <li>If you are using C++, the BigInteger data type is not available by default. Please see the note on the next page about using cpp_int type from Boost library.</li>

</ul>

<table width="563">

 <tbody>

  <tr>

   <td width="280">Password Length</td>

   <td width="283">Execution time in  milliseconds to generate all the combinations</td>

  </tr>

  <tr>

   <td width="280">1</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">2</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">3</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">4</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">5</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">6</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">7</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">8</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">9</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">10</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">15</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">20</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">25</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">30</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="280">35</td>

   <td width="283"> </td>

  </tr>

 </tbody>

</table>

<u>Deliverables:</u>

<ul>

 <li>Your program’s source code</li>

 <li>Above table</li>

</ul>

<strong>Note on how to use BigInteger data type in C++</strong>

To store big integers in C++, you can use the Boost library (<a href="https://www.boost.org/">http:// </a><a href="https://www.boost.org/">www.boost.org/</a><a href="https://www.boost.org/">)</a>. Boost provides <strong>cpp_int</strong> data type that can be used to store big integers.

You can download the Boost library from

https://sourceforge.net/projects/boost/files/boost/1.63.0/

Once you have downloaded the Boost library, extract it in a folder as shown below.

Then add this folder under “Additional Include Libraries” in your Visual Studio project settings as shown below. You can find more instructions here

http://www.boost.org/doc/libs/1_63_0/more/getting_started/windo ws.html#link-from-within-the-visual-studio-ide

Here is the example program using cpp_int data type from the Boost library –

#include&lt;iostream&gt;

#include&lt;math.h&gt;

#include “z:codecppboost_1_63_0boostmultiprecisioncpp_int.hpp”

namespace mp = boost::multiprecision; using namespace std; void main() {

char chars[] = { ‘A’, ‘B’, ‘C’, ‘D’, ‘E’, ‘F’, ‘G’, ‘H’, ‘I’, ‘J’, ‘K’,

‘L’, ‘M’, ‘N’, ‘O’, ‘P’, ‘Q’, ‘R’, ‘S’, ‘T’, ‘U’, ‘V’, ‘W’, ‘X’, ‘Y’, ‘Z’ }; int passwordLength = 5;

mp::cpp_int  iPossibilities = (mp::cpp_int)pow(26,  passwordLength);




cout&lt;&lt; iPossibilities&lt;&lt; ” words total. “; for (mp::cpp_int i =  0; i &lt; iPossibilities; i=i+1)

{ mp::cpp_int k =  mp::cpp_int(i % 26); cout &lt;&lt; k &lt;&lt; endl;

}

}