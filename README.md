<div align="center">

## Loops For Beginers


</div>

### Description

This tutorial is for those beginers, who dont know about loops. Just read it, and see for yourself. http://thadood.ath.cx/~fatal
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[tehfatal](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tehfatal.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tehfatal-loops-for-beginers__3-2051/archive/master.zip)





### Source Code

<b><font face="Arial Narrow" size="5" color="#666666">Loops<br>
 </font></b><font face="Arial Narrow" size="5" color="#666666"><font size="4">Writen
 By: fatal<br>
 <a href="http://thadood.ath.cx/%7Efatal">Feed Your Compiler</a></font></font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Hey you beginners, in this
 tutorial i will cover, loops(for, do/while, and while). If you dont have a clue
 about what i just said keep reading, and all questions will be answered.</font></p>
<p><b><font face="Arial Narrow" size="4" color="#666666">Loops:<br>
 </font></b><font face="Arial Narrow" size="3" color="#666666">for loop:<br>
 The sytax for a for loop is<br>
 <br>
 . &nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;<br>
 </font><font face="Arial Narrow" size="3" color="#FF0000">for( x = 0; x &lt;
 10; x++ )<br>
 {<br>
 statements;<br>
 }</font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Now to Explain it the for
 loop<br>
 1: This its the starting point; x = 0 at the beginning<br>
 2: This is the number in which it will be looping till; the loop will end at
 9<br>
 3: This is how x will be incermented or decremented; you can put x++, x- -,
 x = x + 2, ect....</font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Statements: It can be anything
 you want to have done repeatedly,<br>
 ex: cout&lt;&lt; x &lt;&lt; endl;<br>
 Using that withe the example will output 0 - 9, because the stoping point is
 set to less than 10 so 9 is the closest number w/o equaling it.</font></p>
<p><b><font face="Arial Narrow" size="3" color="#666666">Put it all together,
 sample program using for loop:<br>
 <font color="#FF0000">#include &lt;iostream.h&gt;</font></font></b></p>
<p><b><font face="Arial Narrow" size="3" color="#FF0000">int main()<br>
 {<br>
 int x;</font></b></p>
<p><b><font face="Arial Narrow" size="3" color="#FF0000">for( x = 0; x &lt; 10;
 x++ )<br>
 {<br>
 cout&lt;&lt; x &lt;&lt; endl;<br>
 }</font></b></p>
<p><b><font face="Arial Narrow" size="3" color="#FF0000">return 0;<br>
 }</font></b></p>
<p><font face="Arial Narrow" size="3" color="#666666">Run that, and mess around
 with the numbers, thats the best way to understand. If you can predict the output
 from what you set the numbers to, then you have mastered the for loop :-)</font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Do/ While Loops:<br>
 Sytac:</font></p>
<p><font face="Arial Narrow" size="3" color="#FF0000">do<br>
 {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font color="#666666">1</font><br>
 statements;<br>
 } &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font color="#666666">2</font><br>
 while( condition );</font><font face="Arial Narrow" size="3" color="#666666"><br>
 <br>
 1. The statemnets you want to have looped<br>
 2. The Controll of the loop, untill the condition can no longer equal true</font></p>
<p><b><font face="Arial Narrow" size="3" color="#666666">Put it all together,
 An example using the do/while loop:<br>
 <font color="#FF0000">#include &lt;iostream.h&gt;</font></font></b></p>
<p><b><font face="Arial Narrow" size="3" color="#FF0000">int main()<br>
 {<br>
 int x = 0;</font></b></p>
<p><b><font face="Arial Narrow" size="3" color="#FF0000">do<br>
 {<br>
 cout&lt;&lt; x &lt;&lt; endl;<br>
 x++;<br>
 }<br>
 while( x &lt; 10);</font></b></p>
<p><font face="Arial Narrow" size="3" color="#666666">Once again the do/while
 loop will count from 0 - 9, based on the incremation and the condition.</font></p>
<p><font face="Arial Narrow" size="3" color="#666666">While Loop:<br>
 Sytac:</font></p>
<p><font face="Arial Narrow" size="3" color="#666666"><font color="#FF0000">while(
 conditions )<br>
 {<br>
 statements;<br>
 }</font></font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Now you must be saying whats
 the difference between the too loops? But their is a simple answer to that which
 is, in the do/while<br>
 loop the condition is checked at the bottom of the statement, and the other
 is checked at the top. Just depends on what the user<br>
 wants the loop to do.....</font></p>
<p><b><font face="Arial Narrow" size="3" color="#666666">You Put it an example
 together im tired of typing....heh.<br>
 </font></b><font face="Arial Narrow" size="3" color="#666666">I think its time
 you try to make an example from it, as a programer you have to slove problems.
 You cant be told what to do all the time, try it out and tell me the example
 :P<br>
 </font></p>
<p><font face="Arial Narrow" size="3" color="#666666">Good Luck :-)<br>
 </font><font face="Arial Narrow" size="5" color="#666666"><font size="4"><a href="http://thadood.ath.cx/%7Efatal">Feed
 Your Compiler</a></font></font><font face="Arial Narrow" size="3" color="#666666">
 </font></p>
<p>&nbsp;</p>

