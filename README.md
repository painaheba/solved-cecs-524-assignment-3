Download Link: https://assignmentchef.com/product/solved-cecs-524-assignment-3
<br>






General Instruction

<ol>

 <li>( Write regular expression to capture the hexadecimal floating-point values. A hexadecimal floating-point value has an optional fractional portion (beginning with a dot) and a mandatory exponent (beginning with P or p). There may be digits to the left of the dot, the right of the dot, or both, and the exponent itself is given in decimal (contains only the digits 0-9), with an optional leading + or – sign. A hexadecimal floating-point value may end with an optional F or f (indicating “float”-single precision) or L or l (indicating “long”-double precision).

  <ol>

   <li>A character</li>

   <li>The empty string</li>

  </ol></li>

</ol>

<ul>

 <li>Concatenation</li>

</ul>

<ol>

 <li>‘or’</li>

 <li>Kleene star. (Please use superscript star symbols, <em><sup>?</sup></em>)</li>

</ol>

<ol start="2">

 <li>(21 points) Write a Java, C++, and Python programs (without external library) that determines whether a given stream of characters is a hexadecimal floating-point value or not.

  <ol start="3">

   <li>The file names of the source codes should be java, Assn3.cpp, Assn3.py.</li>

   <li>The programs should read the input file name from the command-line argumentspassed to the program. (args[], argv[], sys.argv[]).</li>

  </ol></li>

</ol>

<ul>

 <li>The program should read each line from an input file and print out its evaluation.</li>

</ul>

<ol>

 <li>You can use <strong>any regular expression </strong>which is allowed in the programming languages.</li>

 <li>Execution commands should be:</li>

</ol>

javac Assn3.java; java Assn3 a3_input.txt g++ Assn3.cpp -o Assn3; ./Assn3 a3_input.txt python Assn3.py a3_input.txt

Expected output for the provided a3 input.txt.

Matched: 0x1p+1

Not Matched: 0x1p+8.8

Not Matched: 1a.0p-6 Matched: 0x1.b7p-1

Note. Your programs will be tested with a different test file.