#include <stdio.h>

int main() {
    char name[20], section[10];
    int a, b, c, d;

    printf("Enter Complete Name: ");
    scanf("%[^\n]%*c", name);

    printf("Enter Section: ");
    scanf("%[^\n]%*c", section);

    printf("First Quarter Grade: ");
    scanf("%d", &a);

    printf("Second Quarter Grade: ");
    scanf("%d", &b);

    printf("Third Quarter Grade: ");
    scanf("%d", &c);

    printf("Fourth Quarter Grade: ");
    scanf("%d", &d);

    printf("\nStudent Name: %s\n", name);
    printf("Section: %s\n", section);
    printf("Grades: %d, %d, %d, %d\n", a, b, c, d);

    return 0;
}
