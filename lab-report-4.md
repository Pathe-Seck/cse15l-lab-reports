## The links used for this lab report:
My group: https://github.com/Barakar13/markdown-parser.git

Reviewed group: https://github.com/gabrielseventhucsd25/markdown-parser.git

# Snippet 1

Expected output from CommonMark:

<img width="154" alt="Screen Shot 2022-05-30 at 9 26 02 PM" src="https://user-images.githubusercontent.com/102937267/171093046-32d85114-f1ee-4cbb-89e3-6daaf39b095e.png">

<img width="548" alt="Screen Shot 2022-05-30 at 9 34 56 PM" src="https://user-images.githubusercontent.com/102937267/171093739-bce8ae6e-9a3c-4c61-9d25-3da92abd5957.png">

Expected output:['google.com, google.com, ucsd.edu]

# Snippet 2

Expected output from CommonMark

<img width="209" alt="Screen Shot 2022-05-30 at 9 26 57 PM" src="https://user-images.githubusercontent.com/102937267/171093191-82fe78e2-fafd-471b-9f2f-0cdd56cefbb5.png">

<img width="526" alt="Screen Shot 2022-05-30 at 9 35 28 PM" src="https://user-images.githubusercontent.com/102937267/171093806-3d16d9cb-6102-4080-b9a7-528fc87aea74.png">

Expected output: [a.com, a.com(()), example.com]

# Snippet 3

Expected output from CommonMark

<img width="564" alt="Screen Shot 2022-05-30 at 9 27 57 PM" src="https://user-images.githubusercontent.com/102937267/171093293-0d1f4586-7a00-4fd9-b189-76da21a9651c.png">

<img width="645" alt="Screen Shot 2022-05-30 at 9 35 58 PM" src="https://user-images.githubusercontent.com/102937267/171093845-637c5898-05b4-4881-a88a-eafabee4506b.png">

Expected output: [https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]

# Output for my MarkdownParse implementation:

<img width="854" alt="Screen Shot 2022-05-30 at 10 18 21 PM" src="https://user-images.githubusercontent.com/102937267/171100341-dfd75cda-b370-47e6-9518-6e08615c61cc.png">

# Ouput for other MarkdownParse implementation:

<img width="773" alt="Screen Shot 2022-05-30 at 10 23 18 PM" src="https://user-images.githubusercontent.com/102937267/171100522-c986eba0-98a3-48c2-9cb7-84f074573f61.png">

# Question 1 : Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
Yes, just do what you did for the brackets and parentheses. Keep track of the backticks and when there is an even number of backticks then you don't have to worry about them. Otherwise, you would update the current index (currIndex) with a backtick.

# Question 2 : Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
This one is a bit more tricky because you have to take into account the number of nest parnetheses, brackets, and escaped brackets that are in the test file. This would require additonal variables and if else blocks to be able to make sure that you keep track of all the brackets/ parentheses.

# Question 3 : Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.
It is definitely possible if you go line by line and take into account if there is are newlines in brackets and parentheses. You would evalute whether this is true or not and then from there look for the correct parentheses and begin doing what the original MarkdownParse file does. 



