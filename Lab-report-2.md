*Disclaimer, I read the instructions as us being able to use our 
group member's repository's and since I wasn't here for this lab 
I did that. If this is not allowed I will be more than happy to 
redo the lab report and the other lab as well. 

# Code Change Number 1

## Code Change
<img width="1430" alt="Screen Shot 2022-05-03 at 8 10 16 PM" src="https://user-images.githubusercontent.com/102937267/166618740-7528e2b9-54fe-4c57-80b4-000b24d233a9.png">

## Link to failure-inducing input
[Test-file3](https://github.com/Pathe-Seck/markdown-parser/blob/5bcb06db044e743072d50e9cd83aa5629476fd89/test-file3.md)

## Symptom
<img width="1219" alt="Screen Shot 2022-05-03 at 8 26 43 PM" src="https://user-images.githubusercontent.com/102937267/166619598-23d6bc92-d7f6-43fd-b59f-8f94eca7f9d8.png">

The previous code before the change didn't take into account the extra parentheses.
This would always result in an error in the code that immediately threw an error.
In order to fix this, any sort of additional parentheses were accounted for 

# Code Change Number 2

## Code Change 
<img width="873" alt="Screen Shot 2022-05-03 at 8 41 10 PM" src="https://user-images.githubusercontent.com/102937267/166620409-2d568d2d-0842-4efa-a5ed-dc304896d322.png">

##Link To Failure-Inducing Input 
[Test-file5](https://github.com/Pathe-Seck/markdown-parser/blob/09f7024fede3d688f8c448f146ad98baee8b2b91/test-file5.md)

## Symptom
<img width="877" alt="Screen Shot 2022-05-03 at 8 53 56 PM" src="https://user-images.githubusercontent.com/102937267/166621020-4e9e86aa-f68c-4832-8abf-0c56825c388d.png">

The issue with the code before the changes was that images weren't taken 
account for and would either just end up returning two empty brackets or 
just the link to the image itself. With the change you are now able to 
take into account the exclamation mark.



# Code Chagne Number 3

## Code Change
<img width="881" alt="Screen Shot 2022-05-03 at 8 41 59 PM" src="https://user-images.githubusercontent.com/102937267/166620461-afcc2b65-f61f-473f-b056-7567069b0ae4.png">

## Link To Failure-Inducing Input 
[Test-file7](https://github.com/Pathe-Seck/markdown-parser/commit/4b41d5d4780dcfc1bca2bf208003fa5d77aa5fa1)

## Symptom 
<img width="919" alt="Screen Shot 2022-05-03 at 9 00 52 PM" src="https://user-images.githubusercontent.com/102937267/166621898-edc45ff1-46ff-40b9-a7d6-6b2262583f48.png">

Before the changes the code was getting overloaded and would run out of 
memory I was able to make changes to the code so that it took into that 
if the two brackets were different or didn't match it would just return 
empty brackets. 
