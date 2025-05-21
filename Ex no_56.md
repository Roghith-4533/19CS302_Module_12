# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:5/5/25
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm:
1. Start.
2. Define a variables.
3. Write a program to display stack elements using linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
Struct Node
{
int data;
struct Node *next;
}*head;
void display()
{
struct Node *temp= head; 
while(temp!=NULL)
{
printf("%d\n",temp->data); 
temp=temp->next;
}
}
```

## Output:
![image](https://github.com/user-attachments/assets/1ba03d38-cf2e-4727-92de-90ebaffb2ae6)



## Result:
Thus the program was executed and the output was verified successfully.
