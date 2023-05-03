Download Link: https://assignmentchef.com/product/solved-cs135-project1
<br>









<h1>Project Goals</h1>




The goals of this project are to:

<ol>

 <li>Provide you an overview of core c programming concepts</li>

 <li>Introduce variables, assignment, choice, and iteration</li>

 <li>Explore c arithmetic and logical operators</li>

</ol>




<h1>Project Description</h1>




This project consists of three simple programs:




<h2>Program 1 (speed conversion):​</h2>




Write a program that converts measurements from miles per hour to meters per second. This program should:




❏ prompt a user to enter a speed in miles per hour, then ❏ output the equivalent speed in meters per second.




For example the program should prompt:




Please enter a speed in miles per hour:




If the user enters 25, then the program should output:




25 mph is 11.176 m/s




Code for this program should be in a file named ​<em>convert.c</em>




<strong>Program 2 (compound interest): </strong>




Write a program that serves as a compound interest rate calculator. This program should:




❏ prompt a user to enter a dollar amount (principal) and a percentage (annual interest rate), then

❏ output the value of the principal, plus interest compounded annually each year for 20 years. For example, the program should prompt the user:




Please enter the amount of principal and interest percentage:




if the user entered: ​1000 5, then the program should output:​




<ul>

 <li>$1050.00</li>

 <li>$1102.50</li>

 <li>$1157.62</li>

 <li>$1215.51</li>

 <li>$1276.28</li>

 <li>$1340.10</li>

 <li>$1407.10</li>

 <li>$1477.46</li>

 <li>$1551.33</li>

 <li>$1628.89</li>

 <li>$1710.34</li>

 <li>$1795.86</li>

 <li>$1885.65</li>

 <li>$1979.93</li>

 <li>$2078.93</li>

 <li>$2182.87</li>

 <li>$2292.02</li>

 <li>$2406.62</li>

 <li>$2526.95</li>

 <li>$2653.30</li>

</ul>




<h2>Constraints</h2>

❏ You must <strong>use a while loop </strong>​      to calculate each year’s value.​




Code for this program should be in a file named ​<em>interest.c </em>







Write a program that computes your percentage grade for cs135 given the percentage weight for each portion of this cs135 class in the class <u>syllabus</u><u>​ </u>. You must calculate the​              following:




❏ project average (must prompt for the number of projects)

❏ quiz average (must prompt for the number of quizzes)

❏ exam average (must prompt for the number of midterms)

❏ overall class average




So your program should read each grade (a number between 0.00 and 100.00) for each portion of the class in the following order




<ol>

 <li>projects</li>

 <li>midterms</li>

 <li>quizzes</li>

 <li>final project</li>

 <li>final exam</li>

</ol>




After reading these values from the terminal, your program should then compute and print the following:




<ol>

 <li>The average projects grade (not including the final project)</li>

 <li>The average of all the midterm and final grades</li>

 <li>The average of the quiz grades</li>

 <li>The final percentage grade</li>

 <li>Whether these scores qualify a student for cs202 (C (73) or better, as per the syllabus)</li>

</ol>




on the terminal. Here is sample output:




Average projects grade: 87.50

Average exam grade: 97.20

Average quiz grade: 92.45

Final grade: 92.45

You can take cs202




<h2>Constraints</h2>

❏ You must <strong>use for loops </strong>​         to read in the multiple project, quiz, and midterm grades.​




Code for this program should be in a file named ​<em>grade.c </em>




<strong>Challenge:</strong> Deal with the case where you want to know your maximum possible percentage​  grade sometime during the semester and you have not been given all your projects and tests. In this case, reading a -1 for a project or test means that you have yet to receive a grade for this item. You compute the maximum possible percentage by assuming you obtained a 100.00 on this item.

vada, Reno General Catalog.