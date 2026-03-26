# program-6-c-
C module 6
EXP.No:6-c-Student information using structure.

Date: 26.03.2026
Name: SAAGAR S
Ref no: 25013937

AIM:
Create a C Program to store the student information and display it using structure.

PROGRAM:
```
#include<stdio.h>
struct student
{
    char name[100];
    int roll;
    float marks;
};

int main()
{
    struct student s;
    scanf("%s %d %f",s.name,&s.roll,&s.marks);
    printf("Displaying Information:\n");
    printf("Name: %s\n",s.name);
    printf("Roll number: %d\n",s.roll);
    printf("Marks: %.1f",s.marks);
}
```
OUTPUT:

<img width="547" height="142" alt="Screenshot 2025-10-21 at 8 53 47 AM" src="https://github.com/user-attachments/assets/d972c677-31d7-4a13-a648-c108304a0b39" />

RESULT:

Thus the C program to  store the student information and display it using structure is executed successfully.










