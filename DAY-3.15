#include <stdio.h>

int reverse(int num);

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    printf("Reverse of %d is %d\n", num, reverse(num));

    return 0;
}

int reverse(int num) {
    static int rev = 0;

    if (num == 0) {
        return rev;
    } else {
        rev = (rev * 10) + (num % 10);
        reverse(num / 10);
    }
}
