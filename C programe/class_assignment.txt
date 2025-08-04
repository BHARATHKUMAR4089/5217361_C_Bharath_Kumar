#include <stdio.h>

int main() {
    int day;

    while (1) {
        printf("Enter any day between 1 to 7: ");
        scanf("%d", &day);

        switch (day) {
            case 1:
                printf("Sunday\n");
                return 0;
            case 2:
                printf("Monday\n");
                return 0;
            case 3:
                printf("Tuesday\n");
                return 0;
            case 4:
                printf("Wednesday\n");
                return 0;
            case 5:
                printf("Thursday\n");
                return 0;
            case 6:
                printf("Friday\n");
                return 0;
            case 7:
                printf("Saturday\n");
                return 0;
            default:
                printf("Invalid input. Please try again.\n");
        }
    }

    return 0;
}