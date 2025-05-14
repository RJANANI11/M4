# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
![Screenshot 2025-05-14 211022](https://github.com/user-attachments/assets/bf076c49-1fbd-47f7-ae06-477a8e8ac36e)



## OUTPUT
![Screenshot 2025-05-14 211031](https://github.com/user-attachments/assets/82fe23d6-16b7-4110-9b01-e655069948fd)











## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
int m,n;
scanf("%d",&m);
scanf("%d",&n);
if(m==n)
{
printf("Numbers are Equal");
}
else
{
printf("Numbers are not Equal");
}
return 0;
```


## OUTPUT
![Screenshot 2025-05-14 211324](https://github.com/user-attachments/assets/ae6c3e55-1e6a-4630-b1d1-1ec0bc9aef86)


           
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
![Screenshot 2025-05-14 211419](https://github.com/user-attachments/assets/7cf11ebd-db39-404e-829d-b9b1eb87ff85)


## OUTPUT
![Screenshot 2025-05-14 211427](https://github.com/user-attachments/assets/3b49642b-6479-4b89-9d8f-0d5fa89bfb19)





## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
![Screenshot 2025-05-14 211508](https://github.com/user-attachments/assets/41e5120b-8b45-4a86-964c-b441a812747d)


## OUTPUT
![Screenshot 2025-05-14 211515](https://github.com/user-attachments/assets/fded8ea8-ce2a-4861-90aa-7da826f2607d)






## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
int main()
{
char str1[100], str2[100];
int i;
i = 0;
scanf("%[^\n]%*c", str1);
scanf("%[^\n]%*c", str2);
do
{
if(str1[i]<str2[i])
{
printf("str1 is Less than str2");
break;
}
else if(str1[i]>str2[i])
{
printf("str2 is Less than str1");
break;
}
else
{
printf("str1 is Equal to str2");
}
}while(1);
i++;
return 0;
}
```


## OUTPUT
![Screenshot 2025-05-14 211713](https://github.com/user-attachments/assets/e1e1ffe7-1d82-4024-959d-c078e7223890)

 

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

