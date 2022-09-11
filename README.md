# Typedef
This is a program for use of typedef as it be an alternative path for defining datatypes in C programming.


#include <stdio.h>

typedef struct Employees
{
    char Name[20];
    char Position[30];
    int Mobile_number;
    int Section_id;
    int working_hours;
} emp;

int main()
{
    emp e1 = {"Prerna", "Software Engineer", 98765, 1345, 5};
    emp e2 = {"Shanvi", "Data Scientist", 97864, 1200, 6};
    printf("e1's name = %s\n", e1.Name);
    printf("e1's position = %s\n", e1.Position);
    printf("e1's Mobile number = %d\n", e1.Mobile_number);
    printf("e1's section id = %d\n", e1.Section_id);
    printf("e1's working hours = %d\n", e1.working_hours);
    printf("e2's name = %s\n", e2.Name);
    printf("e2's position = %s\n", e2.Position);
    printf("e2's Mobile number = %d\n", e2.Mobile_number);
    printf("e2's section id = %d\n", e2.Section_id);
    printf("e2's working hours = %d\n", e2.working_hours);
    return 0;
}

Output:
e1's name = Prerna
e1's position = Software Engineer
e1's Mobile number = 98765       
e1's section id = 1345
e1's working hours = 5
e2's name = Shanvi
e2's position = Data Scientist   
e2's Mobile number = 97864       
e2's section id = 1200
e2's working hours = 6
