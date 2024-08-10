#include <stdio.h>

int main() {
    char op;
    double num1, num2, result;

    printf("Enter an operator (+, -, *, /): ");
    scanf("%c", &op);

    printf("Enter two numbers: ");
    scanf("%lf %lf", &num1, &num2);

    if (op == '+') {
        result = num1 + num2;
    } else if (op == '-') {
        result = num1 - num2;
    } else if (op == '*') {
        result = num1 * num2;
    } else if (op == '/') {
        if (num2 == 0) {
            printf("Error: Division by zero\n");
            return 1;
        }
        result = num1 / num2;
    } else {
        printf("Invalid operator\n");
        return 1;
    }

    printf("%.2lf %c %.2lf = %.2lf\n", num1, op, num2, result);

    return 0;
}
