# csc410-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CSC410 Assignment 5 Solved](https://www.ankitcodinghub.com/product/csc410-solved-7/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120311&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC410 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Assignment Format and Guidelines on Submission

Submit a properly typed PDF on Markus. No handwritten assignment will be accepted. Unless otherwise

specified, no English words will be marked.

This assignment will be longer than the previous ones. Around 7 problems are planned. Keep in mind that it is designed for a group of 3 or 4 students and you have collectively 20 days to get it done. List of files to submit:

• a5.pdf which will include the cleanly typed solutions to the problems.

Problem 1: Symbolic Testing (20 points)

Consider the following function foo

1 int foo ( int x , int y)

2 {

3 if (x &lt; y) {

4 x = −x ;

5 y = −y ;

6 }

7 if (x &lt;= y){

8 x = −x ;

9 y = −y ;

10 } else{

11 int z = x ;

12 x = y ; 13 y = z ;

14 }

15 assert (x &lt; y );

16 }

(a) Enumerate all the paths (regardless of feasibility) in foo where each path is given as a sequence of line numbers (e.g. 3,4,5,10,11,12,18) .

(b) Are all the paths listed above feasible? Prove the paths are not feasible as such by filling instances of a table in the below format (please check tutorial 4 slide 8 and 10 for the format). At the end of each, write a short English description to sum up the result of the table.

Line No. Assignment Path Condition

(c) Of all the feasible paths, would any result in an assertion violation? Prove your claim using symbolic execution. Fill in a table in the above format again and conclude your argument using a short English description.

Line No. Assignment Path Condition

1

LTL Problems

Problem 2 (12 points)

Let us assume we have a system with only one observable component: a colour LED light bulb. This light bulb can be of colours white (w), red (r), green (g), and blue (b) when it is on, or it can be off (o). The system changes state every second, and the status of the light accordingly changes (or remains the same).

Note that it is assumed that the light is always exactly one colour.

Translate each of the following English specification for this simple system to an LTL formula.

(a) The light bulb turns red exactly once (but it can remain red for any duration).

(b) The light bulb stays on forever, changes colour every second, and alternates between red and white.

(c) The light bulb stays on forever, alternates between colours red, blue, and white (in that order), staying at each colour for an arbitrarily long (non-zero but finite) amount of time.

(d) The light bulb can only turn white if it has been previously at least once blue, once green, and once red (but not necessarily in that order).

Problem 3 (30 points)

(a) ϕU¬ϕ ≡ true

Problem 4 (10 points)

Recall that satisfiability and validity of LTL formulas are defined in the same way as propositional logic formulas. An LTL formula ϕ is satisfiable if and only if there exists a path π that satisfies it (∃π : π |= ϕ). An LTL formula ϕ is valid if and only if all paths π satisfy it (∀π : π |= ϕ). Note that validity of ϕ can also be reformulated as the equality ϕ ≡ true.

For the formulas below, determine if the formula is satisfiable, unsatisfiable, or valid. Formally justify your answer.

(a) ♦b =⇒ (aUb).

CTL Problems

To be released later …

2
