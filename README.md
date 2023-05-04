Download Link: https://assignmentchef.com/product/solved-cs580u-program-4-file-i-o
<br>
<h3>Driver Code and Test Files</h3>

<h3>program4.c</h3>

names.txt

<h3>Grading Rubric</h3>

<em><strong>TOTAL: ?? points</strong></em>

Test 1: Filter Initial Letter from Input File (?? points)

Test 2: Verify the Output File (?? points)

<h3>Guidelines</h3>

<strong>In this program, you will learn to</strong>:

<ul>

 <li>Read from a file</li>

 <li>Write to a file</li>

</ul>

In this lab, you only need to implement a function “filter_initial” to complete the following features:

<ul>

 <li>Takes “infile” (input file name), “outfile” (output file name), and “letter” (the target initial letter to search for)</li>

 <li>Opens the input file and reads the names in the file</li>

 <li>Finds and counts the names with the initial matches “letter”</li>

 <li>Copies and writes the matched names to the output file (one name per line). Overwrite the output file if exists.</li>

 <li>Handles an exception case when “outfile” is a NULL pointer. In this case, print the matched names to terminal (stdout) instead.</li>

 <li>Returns the count number of matched names</li>

</ul>