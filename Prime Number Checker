#include <stdio.h>
#include <math.h>

int main() {
    int N, i, isPrime = 1;  
    scanf("%d", &N);
    if (N <= 1) {
        printf("Not Prime\n");
        return 0;
    }
    for (i = 2; i <= sqrt(N); i++) {
        if (N % i == 0) {
            isPrime = 0;
            break;
        }
    }
    if (isPrime)
        printf("Prime\n");
    else
        printf("Not Prime\n");

    return 0;
}
