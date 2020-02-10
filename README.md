# OOP244 NAB in-class notes and material 

## OOP244 links 
[Subject outline](https://ict.senecacollege.ca/course/oop244)<br />
[Subject timeline](https://scs.senecac.on.ca/~oop244/pages/timeline.html)<br />
[Online verions of the notes sold in the bookstore](https://scs.senecac.on.ca/~oop244/pages/content/index.html)<br />
[Workshops](https://github.com/Seneca-244200/OOP-Workshops)<br />
[Booking an Appointment -TBA]() <br />
## Online Review Sessions
There may be one or more online review sessions for critical topics.<br />
At the time of the Review Session the following "Join Session" link will be activated <br />
[Join Session (closed)]() <br />
## Creating alias (shortcuts) for submissin command and compilation command:
Add the following two lines to the end of the ".bash_profile" file in the root of your matrix account, then logoff and log back in: <br />
```
alias fsub="~fardad.soleimanloo/submit"
alias g++11="g++ -Wall -std=c++11"
```
After this to submit your work you can simply type "fsub WorkshopName"<br />
And to compile you can type: "g++1  filenames"<br />
## Lab Attendance
In order for your in-lab submission to be valid, you must execute the attendance submission as follows:<br />
First make sure you have only **ONE** terminal client open from a **Lab computer** and then issue the following command: <br />
**~profname.proflastname/submit 244/NXX/WS##/attendance**  (**XX** => lab section   **##** => Workshop number) <br />
If you do not execute the above command during the lab you are attending, any work submitted for that lab will get the mark ZERO
## Quizzes and how to reflect on them 
Your quizzes are marked as follows:<br />
Each question has 2 marks:<br />
- 2 marks if the answer is correct or close to correct.<br /> 
- 1 mark if the answer written is incorrect but relevant. <br />
- 0 if  no answer is written or the answer is irrelevant to the question.<br />
When you receive your marked quiz, you can recover one 1 mark back for each reflection on a mistake.<br /> 
For example: <br />
Say the quiz has total of 8 questions (therefore total of 16 marks) and your mark is "10 / 5" . This means you have recived 10 marks for the quiz and you had 5 mistakes in your quiz. By reflecting on these 5 mistakes you can get 5 marks back and your total mark will increase to 15 out of 16 instead of 10 out of 16.<br /> 
This is how you can reflect:<br /> 
On matrix create a file called q?reflect.txt. Replace the "?" with the number of the quiz. (i.e q2reflect.txt for quiz number 2).<br />
In this file write The quiz version and the questions you made a mistake in. Then write what your mistake was and finally write the correct answer to the question.<br />
To submit this file to me issue the following command:<br />
~fardad.soleimanloo/submit 244_q?_ref&lt;ENTER&gt; (replace the "?" with the number of the quiz)<br />

## Citation and Sources 
In all the DIY parts of your workshops, also Project and assignment deliverables, a file called **sources.txt** must be present. This file will be submitted with your work automatically.<br />   
You are to write either of the following statements in the file "sources.txt":<br /><br />
"I have done all the coding by myself and only copied the code that my professor provided to complete my workshops and assignments."<br />
Then add your name and your student number"<br /><br />
OR:<br /><br />
Write exactly which part of the code of the workshops or the assignment are given to you as help and who gave it to you or which source you received it from. <br />
You need to mention the workshop name or assignment name and also the file name and the parts in which you received the code for help.<br />
Finally add your name and student number at the bottum.<br /><br />
By doing this you will only lose the mark for the parts you got help for, and the person helping you will be clear of any wrong doing. 

## Workshop Submission, Due dates and late penalties
When a submittable work is open for submission the folllowing command will be activated on matrix:
**~profname.proflastname/submit  244/N??/WSXX/lab** or <br />
**~profname.proflastname/submit  244/N??/WSXX/diy** <br />
**~profname.proflastname/submit  244/N??/PRJ/msX** <br />
replace **??** with your section and **XX** with workshop or milestone number to submit your work.<br /><br />
You can always add the flag **-due** to the end of the command line to see what are the due dates,<br />
Example: <br />
**~fardad.soleimanloo 244/NBB/WS05/DIY -due**<ENTER>
The execution of this command with generate something like this:<br/>
<br/>
**===============================================================<br/>
System date and time: Monday, 2019/09/30 - 09:54<br/>
<br/>
Listing Workshop 5 «DIY»  due dates:<br/>
Submissions are open after Sunday, 2019/09/29 - 23:59.<br/>
On time submission before Monday, 2019/10/14 - 23:59<br/>
«late -20%» submission after Monday, 2019/10/14 - 23:59<br/>
«very late -50%» submission after Saturday, 2019/10/19 - 23:59<br/>
Submissions are rejected after Monday, 2019/10/21 - 23:59!**<br/>


## Visual Studio
[How to download and install Visual Studio 2019 and create a simple C Console application](https://www.youtube.com/watch?v=DJsHqi5itao)<br />
## Coding Style:
When writing your code you are advised NOT to have tab character in your C code; this is how to convert tab to code in VI and Vistual studio and codelite: <br />
[Converting tab to spaces in VI](http://vim.wikia.com/wiki/Converting_tabs_to_spaces) <br />
[Converting tab to spaces in Visual Studio](https://www.youtube.com/watch?v=oW4viEA72UI)<br />
[Converting tab to spaces in Codelite](https://www.youtube.com/watch?v=XQMPJpA8fJI&t)<br />
If you know how to do this in any other editors or IDEs, please email me the resource and I will add them here.

## Git
[Pro Git Book](https://git-scm.com/book): This is and online complete reference to git and its commands (command line). I recommend reading chapter 1 and 2 and glancing chapter 6. This will be more than enough to get your through atleast first three semesters of college, if not all. <br />
[Installing git on windows 10](https://www.youtube.com/watch?v=PXQif4EZd3Y)  <br />
[Installing tortoise git (a git integration with windows file explorer)](https://www.youtube.com/watch?v=pttIoMyyMaM) <br />

## Videos
[How to Playlist](https://www.youtube.com/playlist?list=PLxB4x6RkylosAh1of4FnX7-g2fk0MUeyc)<br />

## Lecture Videos
[OOP244 - 2201 Play list](https://www.youtube.com/playlist?list=PLxB4x6RkylovDjQaolbwqJAlgyN8xog7R)<br />
Note: The Audio for Jan17 NAA section recording was not recroded so the video is not postd <br />
[BBB review video - TBA]()<br />
## Fardad's Schedule
<table style="background-color: White; width: 608px; height: 506px;"
bordercolorlight="#72D8D8" bordercolordark="#2D9F9F" border="1"
bordercolor="#38c7c7" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td align="center" valign="middle" width="18">P</td>
<td align="center" valign="middle" width="45">Strt<br>
End</td>
<td align="center" valign="middle" width="101">Monday</td>
<td align="center" valign="middle" width="109">Tuesday</td>
<td align="center" valign="middle" width="102">Wednesday</td>
<td align="center" valign="middle" width="109">Thursday</td>
<td align="center" valign="middle" width="108">Friday</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">1</td>
<td align="center" valign="middle" width="45">08:00<br>
08:50</td>
<td style="background-color: white;" align="center"
bgcolor="White" width="101">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" width="102">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff">&nbsp;</td>
<td
style="width: 108px; text-align: center; background-color: rgb(51, 255, 51);">OOP244NBBL&nbsp;</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">2</td>
<td align="center" valign="middle" width="45">08:55<br>
09:45</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" width="101">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" width="102">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff">&nbsp;</td>
<td
style="text-align: center; background-color: rgb(51, 255, 51);">LAB
C3034<br>
</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">3</td>
<td align="center" valign="middle" width="45">09:50<br>
10:40</td>
<td style="background-color: white;" align="center"
bgcolor="#33ff33">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" width="109">&nbsp;</td>
<td style="width: 102px; text-align: center;"><br>
</td>
<td style="background-color: white;" align="center">&nbsp;</td>
<td
style="text-align: center; background-color: rgb(0, 204, 204);">OOP244NAAL<br>
</td>
</tr>
<tr>
<td align="center" height="38" valign="middle" width="18">4</td>
<td align="center" height="38" valign="middle" width="45">10:45<br>
11:35</td>
<td
style="text-align: center; background-color: rgb(0, 204, 204);">OOP244NAB&nbsp;</td>
<td style="background-color: white;" align="center"
valign="middle" width="109">&nbsp;</td>
<td
style="width: 102px; text-align: center; background-color: rgb(51, 255, 255);">OFFICE<br>
See notes below<br>
</td>
<td style="background-color: white;" align="center">&nbsp;</td>
<td
style="text-align: center; background-color: rgb(0, 204, 204);">LAB
A4526<br>
</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">5</td>
<td align="center" valign="middle" width="45">11:40<br>
12:30</td>
<td
style="width: 101px; text-align: center; background-color: rgb(51, 255, 51);">K3010<br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td
style="width: 102px; text-align: center; background-color: rgb(51, 255, 255);">A3058</td>
<td style="text-align: center; background-color: white;"> <br>
</td>
<td align="center" width="108"><br>
</td>
</tr>
<tr>
<td align="center" height="28" valign="middle" width="18">6</td>
<td align="center" height="28" valign="middle" width="45">12:35<br>
13:25</td>
<td style="background-color: white;" align="center" width="101"><br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td
style="width: 102px; vertical-align: middle; text-align: center;"><br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td
style="width: 108px; vertical-align: middle; text-align: center; background-color: rgb(51, 255, 255);">OFFICE<br>
See notes below<br>
</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">7</td>
<td align="center" valign="middle" width="45">13:30<br>
14:20</td>
<td
style="width: 101px; text-align: center; background-color: rgb(255, 255, 102);">OOP345NEE<br>
</td>
<td
style="width: 109px; text-align: center; background-color: white;"><br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td style="background-color: white;" align="center"><br>
</td>
<td
style="text-align: center; background-color: rgb(51, 255, 255);">&nbsp;A3058</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">8</td>
<td align="center" valign="middle" width="45">14:25<br>
15:15</td>
<td
style="width: 101px; vertical-align: middle; text-align: center; background-color: rgb(255, 255, 102);">K3280<br>
</td>
<td style="background-color: white;" align="center"
valign="middle" width="109"><br>
</td>
<td
style="text-align: center; background-color: rgb(255, 255, 102);">OOP345NEEL</td>
<td style="background-color: white;" align="center"><br>
</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff">&nbsp;</td>
</tr>
<tr>
<td align="center" valign="middle" width="18">9</td>
<td align="center" valign="middle" width="45">15:20<br>
16:10</td>
<td style="text-align: center; background-color: white;"> <br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td
style="text-align: center; background-color: rgb(255, 255, 102);">LAB
C3032<br>
</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" width="108">&nbsp;</td>
</tr>
<tr>
<td align="center" height="37" valign="middle" width="18">10</td>
<td align="center" height="37" valign="middle" width="45">16:15<br>
17:05</td>
<td
style="width: 101px; vertical-align: middle; text-align: center; background-color: white;">&nbsp;</td>
<td
style="width: 109px; vertical-align: middle; height: 37px; text-align: center; background-color: white;"><br>
</td>
<td style="text-align: center; background-color: white;">&nbsp;</td>
<td style="text-align: center; background-color: white;"><br>
</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" valign="middle" width="108">&nbsp;</td>
</tr>
<tr>
<td align="center" height="37" valign="middle">11</td>
<td align="center" height="37" valign="middle">17:10<br>
18:00</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" valign="middle">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" height="37" valign="middle">&nbsp;</td>
<td style="background-color: white;" align="center">&nbsp;</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff"><br>
</td>
<td style="background-color: white;" align="center"
bgcolor="#ffffff" valign="middle">&nbsp;</td>
</tr>
<tr>
<td style="vertical-align: middle; text-align: center;">12<br>
</td>
<td style="vertical-align: top; text-align: center;">18:05<br>
19:00<br>
</td>
<td style="vertical-align: top; background-color: white;"><br>
</td>
<td style="vertical-align: top; background-color: white;"><br>
</td>
<td style="vertical-align: top; background-color: white;"><br>
</td>
<td
style="vertical-align: middle; text-align: center; background-color: white;"><br>
</td>
<td style="vertical-align: top; background-color: white;"><br>
</td>
</tr>
</tbody>
</table>
<br />
Note: For Office hours I will be sitting at the tables in front of the
office door. <br />
If I am not there, please either call me at: 4164915050 x 24120 or <br /> 
go to the reception desk and ask
one of the
secretaries to call me out.<br />
