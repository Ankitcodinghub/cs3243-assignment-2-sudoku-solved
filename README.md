# cs3243-assignment-2-sudoku-solved
**TO GET THIS SOLUTION VISIT:** [CS3243 Assignment 2: Sudoku Solved](https://www.ankitcodinghub.com/product/cs3243-assignment-2-sudoku-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114621&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3243  Assignment 2: Sudoku Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Important: Read all the instructions below carefully before you start working on the assignment, and before you make a submission.

• You must do this assignment in groups of two only. Please write the names and matriculation numbers of your team members in the report and the code.

• Sign up your group on LumiNUS: Class and Groups → Class Groups – This time, you can form groups with anyone in the module.

– i.e., there is no tutorial restriction on group forming.

– Group size is strictly 2 students (No groups of 3 or individuals submissions are allowed. Reason: It helps us to manage logistics and grading).

• Submission instructions (These instructions are different from Assignment 1, please pay attention)

• You need to submit two files on LumiNUS, your python code file and the report PDF. – Make only one submission (i.e., one set of two files) per group.

• File names:

The code filename should be sudoku A2 xx.py

The report filename should be sudoku A2 xx.pdf

E.g. sudoku A2 03.py, sudoku A2 03.pdf (note that it is 03 and not 3).

• Points will be deducted for not following the naming convention. Please follow the file naming system closely.

• Kindly check that the submitted code will be able to run on SoC’s Sunfire account. We will be using Sunfire (our UNIX server) to evaluate all submissions.

1 Background

Sudoku is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid contain all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution. Figure 1 shows a sample Sudoku puzzle .

Figure 1: A sample Sudoku puzzle

2 Problem Statement

Implement an efficient solver to solve the given Sudoku puzzle.

Here are the conditions/minor details you need to take note of/adhere to.

• You need to model the Sudoku puzzle as a CSP.

• You can explore any CSP algorithm/heuristic in this assignment and you are not restricted to the ones mentioned in the textbook. (Rationale: To give you an opportunity to explore things outside the textbook.)

– We will time your solution and use the timing information as one of the (small) components for grading this assignment.

– However, please don’t stress out too much about this! (Reason: Timing alone doesn’t determine the full score for this assignment as such!)

– If you have tried a few different algorithms/heuristics, please submit the solution that is your best. You can write about the other methods you tried in the report, and compare them with your submitted solution.

– For the purpose of comparison and reporting, you can use the sample puzzle given in Figure 1.

3 Logistics – Input/Output

3.1 Input

The input will be provided in a text file containing 9 lines to represent the Sudoku puzzle. Each line contains 9 numbers, which can be 0–9, where 0 represents an empty grid.

The given Sudoku puzzle is always:

1. 9 × 9 size

2. valid (i.e. each column, each row, and each of the nine 3×3 subgrids will not have duplicate non-zero numbers)

3. solvable, and the puzzle is well-formed (i.e., has exactly one solution).

Figure 2: Answer for the Figure 1 puzzle.

For example, the Sudoku Puzzle in Figure 1 is encoded in the text file as follows:

8 0 0 0 0 0 0 0 0

0 0 3 6 0 0 0 0 0

0 7 0 0 9 0 2 0 0

0 5 0 0 0 7 0 0 0

0 0 0 0 4 5 7 0 0

0 0 0 1 0 0 0 3 0

0 0 1 0 0 0 0 6 8

0 0 8 5 0 0 0 1 0

0 9 0 0 0 0 4 0 0

3.2 Output

The output should have the same format of the input. It should be valid, and only contain numbers 1–9 (i.e., there should be no blank space!).

For example, for the input in Figure 1, the only possible solution is shown in Figure 2, which should be encoded in the text file as follows:

8 1 2 7 5 3 6 4 9

9 4 3 6 8 2 1 7 5

6 7 5 4 9 1 2 8 3

1 5 4 2 3 7 8 9 6

3 6 9 8 4 5 7 2 1

2 8 7 1 6 9 5 3 4

5 2 1 9 7 4 3 6 8

4 3 8 5 2 6 9 1 7

7 9 6 3 1 8 4 5 2

4 Submission

Your submissions should contain the following: ONE python code file and ONE report in PDF. You will lose 5 points for not submitting either the report or the code file.

4.1 Code

• Your answer should be returned by the solve() function; the main saves your answer in the correct format we expect. Hence, don’t change the main function.

• Executable: If your program can not be executed, you will get 0 for your code components.

• Correctness: Please make sure your algorithm logic is correct. You will lose mark significantly if you can not pass our test cases.

4.2 Report

Your report must be TYPE-WRITTEN (font size between 10-12pt). It should NOT be more than 2 pages.

Your report should contain at least these components:

• Explanation: Explain the algorithms and/or heuristics you use in your solution and why you choose it.

• Analysis: Discuss the optimization you have made in your implementation (if any). Discuss the time complexity of the algorithm that you implemented. You can also elaborate on other points that you think is valuable to discuss.
