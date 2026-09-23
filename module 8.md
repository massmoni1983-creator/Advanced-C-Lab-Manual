EXP NO:6 C PROGRAM PRINT THE LOWERCASE ENGLISH WORD CORRESPONDING TO THE NUMBER
Aim:
To write a C program print the lowercase English word corresponding to the number
Algorithm:
1.	Start
- Initialize an integer variable n.
2.	Input Validation
3.	Switch Statement cases.
-	Case 5: Print "seventy one"
-	Case 6: Print "seventy two"
-	Case 13: Print "seventy three"
-	...
-	Case 13: Print "seventy nine"
-	Default: Print "Greater than 13"
4.	Exit the program.
 
Program:
```
      struct Node
      {
      int data;
      struct Node *next;
      }*head;
      void display()
      {
      struct Node *p; p=head; while(p!=NULL)
      {
      printf("%d\n",p->data); p=p->next;
      }
      }

```




Output:


<img width="207" height="266" alt="image" src="https://github.com/user-attachments/assets/4e32483d-a7ff-4fed-9483-8e8d86e1fcbd" />






Result:
Thus, the program is verified successfully
 
EXP NO:7 C PROGRAM TO PRINT TEN SPACE-SEPARATED INTEGERS     IN A SINGLE  LINE DENOTING THE FREQUENCY OF EACH DIGIT FROM 0 TO 3 .
Aim:
To write a C program to print ten space-separated integers in a single line denoting the frequency of each digit from 0 to 3.
Algorithm:
1.	Start
2.	Declare char array a[50] outer loop for each digit from 0 to 3
3.	Initialize counter c to 0
4.	For each character in the string print count c for current digit, followed by a space
5.	Increment h to move to the next digit
6.	End
 
Program:

```
      struct Node
      {
      int data;
      struct Node *next;
      }*head; void pop()
      {
      if(head==NULL)
      {
      printf("stack is empty");
      }
      else
      {
      head=head->next;
      }
      }

```



Output:



<img width="643" height="452" alt="image" src="https://github.com/user-attachments/assets/0f9e150c-744f-45c5-8a08-6ad1fbcfe0f5" />






Result:
Thus, the program is verified successfully

EXP NO:8 C PROGRAM TO PRINT ALL OF ITS PERMUTATIONS IN STRICT LEXICOGRAPHICAL ORDER.
Aim:
To write a C program to print all of its permutations in strict lexicographical order.

Algorithm:
1.	Start
2.	Declare variables s (pointer to an array of strings) and n (number of strings)

3.	Memory Allocation
Dynamically allocate memory for s to store an array of strings
4.	Input
Read the number of strings n from the user Dynamically allocate memory for each string in s
5.	Permutation Generation Loop
6.	Memory Deallocation
Free the memory allocated for each string in s Free the memory allocated for s
7.	End
 
Program:

```
               struct Node
               {
               char data;
               struct Node *next;
               }*front=NULL,*rear=NULL; 
               void display()
               {
               if(front==NULL)
               {
               printf("queue is empty");
               }
               else
               {
               printf("queue elements:\n"); 
               while(front!=NULL)
               {
               printf("%c\n",front->data); 
               front=front->next;
               }
               }
               }

```



Output:




<img width="399" height="423" alt="image" src="https://github.com/user-attachments/assets/90a671c0-46f2-414e-9e03-750b7dce29f0" />





Result:
Thus, the program is verified successfully
 
EXP NO:9 C PROGRAM PRINT A PATTERN OF NUMBERS FROM 1 TO N AS
SHOWN BELOW.
Aim:
To write a C program to print a pattern of numbers from 1 to n as shown below.
Algorithm:
1.	Start
2.	Declare integer variables n, i, j, min
3.	Read the value of n from the user
4.	Calculate the length of the side of the square matrix: len = n * 2 - 1
5.	Matrix Generation Loop
6.	Calculate min as the minimum distance to the borders
7.	End
 
Program:

```
          struct Node
          {
          int data;
          struct Node *next;
          }*front=NULL,*rear=NULL; 
          void enqueue(int data)
          {
          struct Node *p=(struct Node*)malloc(sizeof(struct Node)); 
          p->data=data;
          p->next=NULL; 
          if(front==NULL)
          {
          front=rear=p;
          }
          else
          {
          rear->next=p; 
          rear=p;
          }
          }
```

Output:


<img width="406" height="427" alt="image" src="https://github.com/user-attachments/assets/bd5d1be8-6950-4688-a35a-d1d0ac60f723" />






Result:
Thus, the program is verified successfully

EXP NO:10 C PROGRAM TO FIND A SQUARE  OF NUMBER USING FUNCTION WITHOUT ARGUMENTS WITH RETURN TYPE

Aim:

To write a C program that calculates the square of a number using a function that does not take any arguments, but returns the square of the number.

Algorithm:

1.	Start.
2.	Define a function square() with no parameters. This function will return an integer value.
3.	Inside the function:
o	Declare an integer variable to store the number.
o	Ask the user to input a number.
o	Calculate the square of the number (multiply the number by itself).
o	Return the squared value.
4.	In the main function:
o	Call the square() function and display the result.
5.	End.

Program:
```
          struct Node
          {
             char data;
             struct Node *next;
          }*front=NULL,*rear=NULL;
          void peek()
          {
          printf("%c",front->data);
          }


```




Output:



<img width="945" height="668" alt="image" src="https://github.com/user-attachments/assets/7c446b2c-7851-44cd-935f-9e5891ae45d6" />






Result:
Thus, the program is verified successfully



























