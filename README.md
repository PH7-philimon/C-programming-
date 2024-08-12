# C-programming
#include <stdio.h>

int main() {
    char grade;

    printf("Enter your grade: ");
    scanf("%c", &grade);

    switch (grade) {
        case 'A':
            printf("Excellent!\n");
            break;
        case 'B':
            printf("Good job!\n");
            break;
        case 'C':
            printf("Average.\n");
            break;
        case 'D':
            printf("Needs improvement.\n");
            break;
        case 'F':
            printf("Failed.\n");
            break;
        default:
            printf("Invalid grade.\n");
    }

    return 0;
}
