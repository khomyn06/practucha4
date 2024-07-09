Практична робота №4 Хомин Михайло

#include <stdio.h>

int main() {
    int n, count = 0;
    scanf("%d", &n);

    for (int m = 1; m < n; ++m) {
        if (n % (m + 1) == 0) {
            count++;
        }
    }

    printf("%d\n", count);
    return 0;
}
