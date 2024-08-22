#include <stdio.h>

// Function to calculate simple interest
float calculateSimpleInterest(float principal, float rate, float time) {
    return principal * rate * time;
}

int main() {
    float principal, rate, time, interest;

    // Input principal amount
    printf("Enter the principal amount: ");
    scanf("%f", &principal);

    // Input annual rate of interest (as a fraction, e.g., 0.05 for 5%)
    printf("Enter the annual rate of interest (as a fraction): ");
    scanf("%f", &rate);

    // Input time period in years
    printf("Enter the time period in years: ");
    scanf("%f", &time);

    // Calculate simple interest
    interest = calculateSimpleInterest(principal, rate, time);

    // Output the result
    printf("The simple interest is: %.2f\n", interest);

    return 0;
}
