 #include <stdio.h>

int main() {
    // Declare an array of 5 integers
    int arr[5];

    // Calculate the size of the array
    size_t arr_size = sizeof(arr);

    // Calculate the size of an integer
    size_t int_size = sizeof(int);

    // Print the sizes
    printf("Size of the array (5 integers): %u bytes\n", arr_size);
    printf("Size of an integer: %u bytes\n", int_size);

    return 0;
}
#include <stdio.h>

int main() {
    int arr[6] = {10, 20, 30, 40, 50 ,60};

    printf("Addresses of elements in the array:\n");
    for (int i = 0; i < 5; ++i) {
        printf("Address of arr[%d]: %p\n", i, (void *)&arr[i]);
    }

    return 0;
}
