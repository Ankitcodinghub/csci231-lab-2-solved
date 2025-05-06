# csci231-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI231 Lab 2 Solved](https://www.ankitcodinghub.com/product/csci231-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97016&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI231 Lab 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Implement a ​‘replace’ ​program in MIPS assembly language that, given an array of integers Arr​, its ​length​, integers ​x and ​y,​ replaces all ​x with ​y in ​Arr.​ Then your program should print out all values of ​Arr​.

For example, if ​Arr = {21, ​20​, 51, 83, ​20​, ​20​}​, ​length = 6, ​x = ​20​, ​y = ​5 and ​index = 0, then after running your program the values of ​Arr MUST be ​Arr = {21, ​5​, 51, 83,​ 5​, ​5​}​ and the values MUST be printed out.

In the program, we assume the variables (e..g, ​Arr, length, x, y​ and ​index​) should be declared and initialized manually in the ​.data​ section.

Output: ​21 5 51 83 5 5 (​The first (i.e., before 21) or last (i.e., after the last 5) space can be negligible.​) NOTES​: How to print Integers and Strings/space/newline using ‘syscall’

</div>
</div>
<div class="layoutArea">
<div class="column">
.data

.text

main:

# Register assignments

# $s0 = x

# Initialize registers

</div>
</div>
<div class="layoutArea">
<div class="column">
x: msg1: nl: space:

</div>
<div class="column">
.word 5 .asciiz “x=” .asciiz “\n” .asciiz ” ”

</div>
</div>
<div class="layoutArea">
<div class="column">
lw

# Print li

la syscall

# Print li move syscall

# Print li

la syscall

# Exit li syscall

</div>
<div class="column">
$s0, x

msg1

$v0, 4 $a0, msg1

result (x) $v0,1 $a0, $s0

newline $v0,4 $a0, nl

$v0,10

</div>
<div class="column">
# Reg $s0 = x

# print_string syscall code = 4

# print_int syscall code = 1

# Load integer to print in $a0

# print_string syscall code = 4

</div>
</div>
</div>
</div>
