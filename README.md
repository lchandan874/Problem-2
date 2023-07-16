#include <stdio.h>

void generateOddSeries(int x) {
    int i;
    for (i = 1; i <= x; i++) {
        printf("%d", 2 * i - 1);
        if (i < x) {
            printf(", ");
        }
    }
    printf("\n");
}

int main() {
    int x;

    printf("Enter a number (x): ");
    scanf("%d", &x);

    printf("Output: ");
    generateOddSeries(x);

    return 0;
}
