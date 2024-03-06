// Practicing how to use structures, using a profile of me structure.

#include <stdio.h>
#include <string.h>

#define SIZE 15

struct student_ID
{

    char firstName[SIZE];
    char lastName[SIZE];
    int age;
    char school[SIZE];
    char fav_subject[SIZE];
    int result;

};

int main(void)
{
    // Initialising structures
    struct student_ID c23322253;
    char name[SIZE];

    // Prompt user for inputs.
    printf("\n\nPlease enter students name and then their age:\n");
    scanf("%s", c23322253.firstName);
    //scanf("%s", name);
    //strcpy(c23322253.firstName, name); // Must use this, if assigning variable PRE-running of the program. Scanf will work if during the running of the program.
    scanf("%d", &c23322253.age);

    printf("\n\nName: %s\nAge: %d\n", c23322253.firstName, c23322253.lastName, c23322253.age);
    
    return 0;

} // end main