Download Link: https://assignmentchef.com/product/solved-ai-exams-schedule-generator-using-genetic-algorithm
<br>
<h2>Problem<sub>      </sub></h2>

The assignment is to find generic solution that will facilitate generating schedule for university using “<strong>Genetic Algorithm</strong>”.




<ul>

 <li>You have to write code from scratch.</li>

 <li>Make sure your notebook is well documented</li>

 <li>You cannot use any built-in library for the implementation of Genetic Algorithm except Pandas        and NumPy.</li>

 <li>You can use any kind of crossover discussed in class.</li>

 <li>You can choose any rate of mutation (which can be justifiable)</li>

 <li>You have to roulette wheel selection for selecting potentially useful solutions for recombination (Chromosomes).</li>

</ul>




The success of solution is estimated on fulfillment of given constraints and criteria. Results of testing the algorithm show that all hard constraints are satisfied, while additional criteria are optimized to a certain extent. You have to submit. ipynb with a one-page report of your implementation .pdf.




<h2>Constraints<sub>            </sub></h2>

There are set of constraints that need to be fulfilled.




<h3>Hard Constraints</h3>

<ul>

 <li>An exam will be scheduled for each course.</li>

 <li>A student is enrolled in at least 3 courses. A student cannot give more than 1 exam at a time.</li>

 <li>Exam will not be held on weekends.</li>

 <li>Each exam must be held between 9 am and 5 pm</li>

 <li>Each exam must be invigilated by a teacher. A teacher cannot invigilate two exams at the same time.</li>

 <li>A teacher cannot invigilate two exams in a row.</li>

</ul>

<strong>The above</strong> <strong>-mentioned constraints must be satisfied.</strong>

<h3>Soft Constraints</h3>




<ul>

 <li>All students and teachers shall be given a break on Friday from 1-2.</li>

 <li>A student shall not give more than 1 exam consecutively.</li>

 <li>If a student is enrolled in a MG course and a CS course, it is preferred that their MG course exam be held before their CS course exam.</li>

</ul>




<ul>

 <li>Two hours of break in the week such that at least half the faculty is free in one slot and the rest of the faculty is free in the other slot so the faculty meetings shall be held in parts as they are now.</li>

</ul>

<h2>Input &amp; Output<sub>   </sub></h2>

<strong>Input data </strong>for each exam are <em>teachers’ names, students’, exam duration</em>, <em>courses (course codes)</em>, and list of <em>allowed classrooms</em>.




<strong>Output data </strong>are classroom and starting time for each exam along with course code and invigilating teacher. Time is determined by day (Monday to Friday) andstart hour of the exam.




<ul>

 <li>Output will be a chromosome which satisfies all hard constraints and soft constraints at least     (as much as you can)</li>

 <li>You have to display a list of all hard and soft constraints which are fulfilled in the output.</li>

 <li>Don’t forget to show fitness values at each iteration.</li>

</ul>







<ul>

 <li></li>

</ul>