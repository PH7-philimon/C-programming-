# C-programming-
https://github.com/PH7-philimon/C-programming-.git
#include <stdio.h>

int main() {
    int i;
    for (i = 1; i <= 10; i++) {
        if (i == 5) {
            break; // Exit the loop when i is 5
        }
        printf("%d ", i);
    }
    printf("\nLoop terminated.\n");
    return 0;
}
