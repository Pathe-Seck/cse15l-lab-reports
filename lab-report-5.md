# Lab Report 5

For some reason my tests wouldn't work but I can show what tests didn't work 
for the group members that had the same code as me. 

## Test #170
<img width="1225" alt="Screen Shot 2022-06-10 at 11 19 46 PM" src="https://user-images.githubusercontent.com/102937267/173175986-adae644b-8bb0-4c38-a6be-e42e893c18e3.png">

My implementation was incorrect because Nidhi's expected output was:
**[]**

while my group's implementation was an infinite loop because my group and I
originally only accounted for the beginning of a link to start with an exclamation
mark. If it didn't begin with one our code began to run infinitely until we found 
an exclamation mark.


## Test #360
<img width="1217" alt="Screen Shot 2022-06-10 at 11 20 26 PM" src="https://user-images.githubusercontent.com/102937267/173176245-f4dcf464-1030-49aa-ace9-c3674622edfb.png">

My implementation was incorrect because Nidhi's expected output was:
**[]**

My group and I originally only accounted for links that had an exclamation
mark. As previously mentioned, we would encounter an infinite loop when there 
was no exclamation mark found. When going back to the markdown parse code
we made a modification that was actually pointed out to us by another 
group which allows us to return emptybrackets even when there is no 
exclamation mark to indicate the start of a link.


## The modification 

<img width="836" alt="Screen Shot 2022-06-10 at 11 32 19 PM" src="https://user-images.githubusercontent.com/102937267/173176374-2eae8aa0-dea1-4989-b489-523966178de7.png">

As you can see we have an arraylist variable that returns the links of the file 
in that arraylist. The condition we made was that if the current index we were on
was not a bracket or exclamation mark we would either break out the while loop as 
as whole or continue to the next part of the file. With these specific test cases
neither of the conditions were met so empty brackets were returned.

## Outcome of Code Changes
<img width="521" alt="Screen Shot 2022-06-10 at 11 23 08 PM" src="https://user-images.githubusercontent.com/102937267/173176451-8fd92c29-bb3b-47e2-9214-8498606a8a88.png">



