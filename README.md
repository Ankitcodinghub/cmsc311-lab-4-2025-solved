# cmsc311-lab-4-2025-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cmsc311-lab-4-2025-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132178&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC311 Lab 4 2025 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
For this lab you will implement a basic LC3 assembly program which calculates the sum of all odd numbers stored between x3200 and x32FF inclusive.

Program Details

Your program will start at x3000 in memory and sum all odd numbers stored at memory locations x3200 to x32FF. Please note that while the autograder will populate these memory address with data values, when testing your program, you will need to place these values into memory manually. I recommend doing so by modifying the memory values via the simulator rather than using assembly code. Because the range of values is so large, I recommend placing a few values at the start of the memory range and a few at the end leaving the middle addresses empty. This will allow you to both confirm that your program is covering all necessary memory locations and also produce a result which is easy to verify.

&nbsp;

The final sum will be stored at memory location x3300. Once stored, your program will halt the machine using the HALT command.

&nbsp;

You <strong>must</strong> place any .FILL pseudo-ops after your HALT command. Placing .FILL pseudo-ops before the HALT will cause the data stored at those locations to be executed as instructions. This can cause your code to produce unexpected results <strong><em>and </em></strong>prevent Gradescope from executing correctly.

&nbsp;

<strong>Bonus: </strong>+10 points for making and using an IsEven subroutine to determine if a specific value is even or odd. The subroutine must start at a label named IsEven and expect a single input parameter (a 2s complement number) in R0. If the given number is even, the subroutine will return 0. If the number is odd, it will return any non-zero value. The result of the subroutine will be stored in R0. You must define your subroutine after your halt instruction so that the subroutine will only execute if jumped to.

&nbsp;

The IsEven subroutine must also implement callee save and preserve the values of registers R1-R5. <strong>NOTE:</strong> If your subroutine doesn’t touch a register (i.e. modify its value) then you don’t need to push that registers value onto the stack!

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Development Notes

&nbsp;

If you are looking for algorithmic inspiration (specifically for how to determine if a number is even or odd) I highly recommend the Unit 6 Lecture Slides along with the First50PrimesDemo.asm file on Canvas and their associated lecture recordings

&nbsp;

When testing if a number is odd or even, please remember that a number can be negative or positive and to account for that in your program. Also note that if you use the user stack, you will need to initialize R6 with the stack pointer value first. The user stack should always start at xFDFF per the LC3 ISA.

&nbsp;

For developing and testing your assembly program I recommend using the online LC3 simulator at: <a href="https://wchargin.com/lc3web/">https://wchargin.com/lc3web/</a> . While this is the simulator I recommend, you are allowed to use any LC3 simulator to develop this project. **I also <strong>highly</strong> recommend downloading the LC3’s ISA from Canvas to use as a reference for this project. It is an invaluable resource which is vital for the project.** When saving your assembly program for Gradescope, you will need to use a text editor such as sublime text or notepad++

&nbsp;

Please note that all lab submissions are required to have comments of some kind documenting the behavior of your program. Comments should describe the purpose / high level behavior of groups of instructions. They should not describe what an individual instruction literally does. For the statement:

&nbsp;

AND R0,R0,#0

&nbsp;

A good comment would be: ;sets R0 to 0

&nbsp;

A poor comment would be: ;ANDs the value of R0 to 0 and stores the result

&nbsp;

Final Notes

&nbsp;

When completed, save your assembly program as Lab4.asm and submit your completed file to Gradescope. Although Gradescope is expected to descriptively report all errors it may sometimes produce errors which are opaque or unclear. In such case please do not hesitate to reach out to me via email or DM

&nbsp;

Rubric

&nbsp;

<table>
<tbody>
<tr>
<td width="198">Category</td>
<td width="96">Points</td>
</tr>
<tr>
<td width="198">Autograder</td>
<td width="96">70</td>
</tr>
<tr>
<td width="198">Code Formatting</td>
<td width="96">15</td>
</tr>
<tr>
<td width="198">Comments</td>
<td width="96">15</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;
