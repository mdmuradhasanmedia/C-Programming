// Contest Link - https://codeforces.com/group/MWSDmqGsZm/contest/219774/problem/M



#include <stdio.h>

int main() {
    int N;
    scanf("%d", & N);
    int arr[N];
    for (int i = 0; i <= N - 1; i++) {
        scanf("%d", &arr[i]);
    }


    int max = arr[0];
    int max_position = 0;
    for (int i = 0; i <= N - 1; i++) {
        if (max < arr[i]) {
            max = arr[i];
            max_position = i;
        }
    }


    int min = arr[0];
    int min_position = 0;
    for (int i = 0; i <= N - 1; i++) {
        if (min > arr[i]) {
            min = arr[i];
            min_position = i;
        }

    }

    for (int i = 0; i <= N - 1; i++) {
        if (i == max_position) {
            arr[i] = min;
        } else if (i == min_position) {
            arr[i] = max;
        }
    }

    for (int i = 0; i <= N - 1; i++) {
        printf("%d ", arr[i]);
    }


}
