Download Link: https://assignmentchef.com/product/solved-embsys105-assignment-1-udebugger
<br>
The goal of this assignment is to write a diagnostic hard fault exception handler that may help you to debug later assignments.

Example of the information you should log:

<h1>Hard fault at PC=0x1234ABCD LR=0xABCD1234</h1>

<ol>

 <li>Download and unzip the uDebugger project contained in the zip file: uDebugger.zip</li>

 <li>Open the uDebugger.eww workspace in the EWARM IDE.</li>

 <li>Make sure the uDebugger project builds and runs. It should print a “Fail” message to the UART (BAUD rate should be 38400).</li>

 <li>Implement the code specified by the TODO comments – do a global search in the project (Ctrl_Shift-F) for the “TODO” string. There are TODO comments in these 3 files:

  <ol>

   <li>c</li>

   <li>c</li>

   <li>s</li>

  </ol></li>

 <li>Clean your project and zip it into a file named uDebugger_&lt;YourUwNetId&gt;.zip

  <ol>

   <li>Clean means delete the “Debug” folder before zipping so you don’t bloat your submission.</li>

   <li>Example submission filename: uDebugger_johndoe.zip</li>

  </ol></li>

 <li>Submit your zip file by the due date.</li>

</ol>

Note: Your program should fault exactly 10 times.

Additional Challenge

If you would like an additional challenge, instead of printing just the PC and LR, modify your program to print the entire stack frame consisting of R0-R3, R12, LR, PC, PSR.