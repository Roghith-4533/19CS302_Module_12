# EX 60 C function to find the peek element of the queue using linked list.
## DATE:5/5/25
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to find peek in Queue using linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
struct Node
{
char data;
struct Node *next;
}*front=NULL,*rear=NULL; 
void peek()
{
printf("peek:"); 
printf("%c\n",front->data);
}
```

## Output:
![image](https://github.com/user-attachments/assets/346fd27f-4626-47de-a094-82ff6793e9c8)



## Result:
Thus the program was executed and the output was verified successfully.
