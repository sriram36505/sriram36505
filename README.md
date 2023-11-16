[16:22, 15/11/2023] Sriram R: #include <stdio.h>
#include <string.h>

struct Student {
    char name[50];
    int rollNumber;
    float marks;
};

int main() {
    struct Student students[100]; // Assuming a maximum of 100 students
    int numStudents = 0;
    int choice, i, roll;

    do {
        printf("\nStudent Management System\n");
        printf("1. Add Student\n");
        printf("2. Remove Student\n");
        printf("3. View Student Details\n");
        printf("4. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch(choice) {
            case 1:
                printf("Enter student name: ");
                scanf("%s", students[numStudents].name);
                printf("Enter roll number: ");
                scanf("%d", &students[numStudents].rollNumber);
                printf("Enter marks: ");
                scanf("%f", &students[numStudents].marks);
                numStudents++;
                break;
            case 2:
                printf("Enter roll number to remove: ");
                scanf("%d", &roll);
                for(i = 0; i < numStudents; i++) {
                    if(students[i].rollNumber == roll) {
                        // Remove student by shifting elements
                        for(int j = i; j < numStudents - 1; j++) {
                            students[j] = students[j + 1];
                        }
                        numStudents--;
                        printf("Student removed successfully.\n");
                        break;
                    }
                }
                if(i == numStudents) {
                    printf("Student not found.\n");
                }
                break;
            case 3:
                printf("Enter roll number to view details: ");
                scanf("%d", &roll);
                for(i = 0; i < numStudents; i++) {
                    if(students[i].rollNumber == roll) {
                        printf("Name: %s\n", students[i].name);
                        printf("Roll Number: %d\n", students[i].rollNumber);
                        printf("Marks: %.2f\n", students[i].marks);
                        break;
                    }
                }
                if(i == numStudents) {
                    printf("Student not found.\n");
                }
                break;
            case 4:
                printf("Exiting program. Goodbye!\n");
                break;
            default:
                printf("Invalid choice. Please try again.\n");
        }

    } while(choice != 4);

    return 0;
}
