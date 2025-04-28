# it5001-lab-3--function-scope-and-recursion-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Lab 3- Function Scope and Recursion Solved](https://www.ankitcodinghub.com/product/it5001-week-3-function-scope-and-recursion-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119252&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001 Lab 3- Function Scope and Recursion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
What are the outputs of the code snippets in Part 1 and 2?

Part 1 Variable Scope

Code Output

x = 0 def foo_printx(): print(x) foo_printx() print(x)

x = 0 y = 999 def foo_printx(y):

print(y) foo_printx(x) print(x)

x = 0 def foo_printx(): x = 999 print(x)

foo_printx() print(x)

Part 2 Nested Functions

Code Output

x = 1 y = 2 def foo(y): def bar(x):

return x+y return bar(y) print(foo(x))

x = 1 y = 2 def foo(x): def bar(x):

return x+y return bar(y) print(foo(x))

Part 3 Recursion

Previously, we have shown that we can create a customized burger. Here are the ingredient prices for your convenience:

Ingredient Price

‘B’ stands for a piece of bun $0.5

‘C’ stands for cheese $0.8

‘P’ stands for patty $1.5

‘V’ stands for veggies $0.7

‘O’ stands for onions $0.4

‘M’ stands for mushroom $0.9

Your task was to write a function burgerPrice(burger) that takes in a string representing a burger and returns the price of the burger. Your task now is to write the same function burgerPrice(burger) using recursion.

Part 4 Recursion vs Iteration

B. Factorial: Given a positive number 𝑛𝑛, the value of factorial of 𝑛𝑛 (written as 𝑛𝑛!) is defined as 𝑛𝑛! = 𝑛𝑛 × (𝑛𝑛− 1)!. Additionally, the value of 0! is 1. Write one recursive and one iterative version of function fact(n) which computes the value of n!.

Part 5 Recursion vs Iteration (cont.)

A. Final Sum: Given a positive number 𝑛𝑛, the final sum is obtained by repeatedly computing the sum of all the digits of 𝑛𝑛, until the final sum is a single digit. For example, sum(52634) = 20, which is not a single digit. We then continue with sum(20) = 2 which is now a single digit. Therefore, final_sum(52634) = 2. Write one recursive and one iterative version of the function final_sum(n) which computes the final sum of n.

B. Euler Constant: The value of 𝑒𝑒𝑥𝑥 can be approximated using the formula 𝑒𝑒𝑥𝑥 𝑥𝑥0 𝑥𝑥1 𝑥𝑥2 𝑥𝑥3 . Write one recursive and one iterative version of function find_e(x, n) to find the approximation of 𝑒𝑒𝑥𝑥 up to 𝑛𝑛 + 1

𝑥𝑥𝑛𝑛 steps, i.e. the last term in the summation is .

𝑛𝑛!
